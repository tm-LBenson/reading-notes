<!-- @format -->

# Reading: Application State with Redux

## Reading

[Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)

### What is the first principle of Redux?

The first principle of Redux is that the state of the application should be kept in a single store, and the only way to change the state is through dispatching actions.

### what is a store and what do we use our reducers for within that store?

A store is the container for the state of the application. We use reducers within the store to handle the actions and update the state accordingly.

### Name three Redux store methods given to us by createStore and describe their use.

`getState()` - which allows us to retrieve the current state of the store.  
`dispatch(action)` - which allows us to dispatch actions to the store, which will be handled by the reducers to update the state.  
`subscribe(listener)` - which allows us to subscribe a listener function that will be called whenever the state is updated.

### Explain to a non-technical recruiter what combineReducers() does and why it is useful.

`combineReducers()` is a tool that helps us organize our code by breaking it down into smaller, manageable parts. It's like having different drawers for different items in your room. Each drawer would have its own function to organize the items inside it. `combineReducers()` allows us to have multiple functions that each manage a specific part of our application's state. It helps to keep our code organized and easy to understand, so it's easier to make changes and fix issues.

### Looking ahead at this module’s course schedule, What do you look forward to learning?

What are your learning goals after reading and reviewing the class README?

After reading and reviewing the class README, I am looking forward to learning more about the different concepts and principles of Redux such as actions, reducers, and the store. My learning goals include gaining a better understanding of how to manage application state using Redux, and how to use it effectively in my own projects.

