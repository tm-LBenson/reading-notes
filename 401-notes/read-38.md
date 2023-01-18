<!-- @format -->

# Readings: Redux - Asynchronous Actions

## Reading

[async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

### Why use Redux middleware?

Redux middleware allows for the handling of async logic and side effects in a centralized and composable way.

### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

The UI receives the current state, and when an event is triggered, it dispatches a Thunk containing both the state and the action. This Thunk is intercepted by middleware, which then calls an API. Once the API returns data, the middleware dispatches it along with the current state to the reducer. The reducer uses this information to update the state, which is then sent back to the UI.

### How are we accommodating async in our Redux app?

We are using the thunk middleware to handle async logic in our Redux app.

[thunk middleware](https://github.com/reduxjs/redux-thunk)

### Why would you need redux-thunk middleware?

Redux-thunk middleware is needed to handle async logic and side effects in a Redux app, such as making API calls.

### Redux Thunk middleware allows you to write action creators that return a \_\_\_\_ instead of an action.

Redux Thunk middleware allows you to write action creators that return a function instead of an action.

### Describe how any return value from the inner thunk function will be made available.

Redux Thunk middleware allows you to write action creators that return a function instead of an action.

## Reflection

### What are your learning goals after reading and reviewing the class README?

My learning goals would be to understand how to handle async logic and side effects in a Redux app using thunk middleware and to understand the flow of async actions in a Redux app.
