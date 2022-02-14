## The switch component renders the first component that matches the URL path

- A router component will only render a component that matches the path, or it will render null.
- useParams will always look to the path in your route -url parameters -returns an object
- useLocation will alwys point to the URL and getting access to the query parameter
- query means a question
- f12 to click on a component, click inside of it and press F12
- useLocation is related to what's after the question mark in your search
- const search = location.search;
- const searchedConference, grabs the keys and tell it which key we want to get
- const conference = searcgedConference.get -- grabs the specific key that we want using the get() function
- use URL search params to grab the keys on our query paramaters
- the key is before the = sign
- the useLocation is searching in the URL

* - useHistory - redirect someone to their last page

- it programatically navigates to pages

- for deliverable - create routes matching the links
- create route and switch to render components inside screen color

- url params and query paramters
  URL parameter for clean, small, search engine friendly URLs that lead to a static resource
  Query parameters for longer, more readable URLs, which are followed by dynamic content, not relevant to search engines.
