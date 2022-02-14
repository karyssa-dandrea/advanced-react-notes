- Prop drilling is not the best, can get lost in the sauce
- Providing data with context, we can pass down the data directly to the components, without having to drill down
- You can have as much context as you want in your app
- usecontext and create context are built in from react
- most of the time when context isn't working, it's related to your provider
- <EntryContext.provider value={{}}
- the value prop is the state you want to share with this context
- we are turning the key and value into an object
- {children} the children components from the home page on guestbook
- thats where we are putting that context in
- call usecontext with the context you want to use
- use a custom hook
- the if statement is making sure entry provider is being used
- export the provider and the custom hook
- make sure you wrap your application with <EntryProvider>

- a custom hook is a function that uses other hooks

- custom hooks allow you to share the code to do something, context allow you to share state. I think I have that right
