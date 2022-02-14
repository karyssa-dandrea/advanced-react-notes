- Action: A JavaScript object with a key of `type` and an optional key of `payload`. The action `type` describes the state change you intend to make. The `payload` is any additional information you need to provide to make that state change (e.g. a new item to add to the list would be in the payload).

- Dispatch: A function React provides that sends your actions to a reducer function.

- Reducer: A function you write that takes the current state and the incoming action and a returns a new state object.

- Type and case go together in the reducer, there connected

- you tell the dispatch what to do, and invoke what we are changing
- whatever you return from the reducer is the state, after the update
- the dispatch is being read from the action in the itemsReducer function

- worked on shopping component first
- than work on dispatch

- you should never get the default in your switch statement, means it didnt work

- reducer hook will take reducer and state
- reducer function takes state and action
