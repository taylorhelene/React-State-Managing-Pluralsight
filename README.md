## Quick Start

Run the following commands:

```
npm install
npm start
```

This will install dependencies, then start the app and mock API.

## Starter Project Overview

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

I made the following enhancements:

1. Added mock API using [json-server](https://github.com/typicode/json-server) and configured `npm start` to run the app and mock API at the same time. See [Building Applications with React and Flux](https://app.pluralsight.com/library/courses/react-flux-building-applications/table-of-contents) for details on how to set this up from scratch.
1. Added some React components to help us get started.
1. Added App.css with basic styles
1. Added some images to `/public`.
1. Added functions for fetching data in `/src/services`.



## Exercises

1. Add backpacks to the store
2. Finish the checkout process
3. Accept billing info and payment
5. Save partially completed checkout
6. Display final order confirmation Display cart quantity in nav Deduplicate requests in 
7. useFetchAll Add init arg to useFetch hook
8. Try caching via react-query or swr
