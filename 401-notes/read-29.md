<!-- @format -->

# Reading: Advanced State with Reducers

## Reading

[useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

### Name an alternative to the useState Hook.

An alternative to the useState Hook is the useReducer Hook.

### Why might the useReducer Hook be preferable to the useState Hook?

The useReducer Hook may be preferable to the useState Hook because it can handle more complex state changes and supports reducer functions.

### What are two ways to set the initial state?

Pass an initial value as an argument to the useReducer Hook  
Use the getInitialState method within a class-based component

[Ultimate Guide to useReducer](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)

### In terms of state, what does useReducer expect to receive as a parameter?

useReducer expects to receive a reducer function and an initial state as parameters.

### What does useReducer return?

useReducer returns the current state and a dispatch function.

### Explain dispatch to a non-technical recruiter.

Dispatch is a function that sends updates to a special part of your code. This part of your code is called the reducer, and it decides what to do with the updates and how to change the state of your application based on them. Dispatch is a way to talk to the reducer and tell it to change the state.

Reflection
What are your learning goals after reading and reviewing the class README?

Today I hope to have a strong understanding of the useReducer hook and why I would need to use this hook in a real world application