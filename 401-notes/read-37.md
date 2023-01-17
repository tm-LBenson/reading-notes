<!-- @format -->

# Readings: Redux - Combined Reducers

## Reading

[Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE&ab_channel=LearnCode.academy)

### Why create multiple reducers?

With each being responsible for managing a specific slice of the state, it becomes easier to reason about the code, test it, and make changes without affecting other parts of the codebase.

### How would you combine multiple reducers?

Multiple reducers can be combined using the `combineReducers` utility function provided by the Redux library. This function takes an object whose values are different reducing functions and turns it into a single reducing function that can be passed to the `createStore` function.

### How will you manage state as an immutable object? why?

State in a Redux application should be managed as an immutable object to ensure that the state is not accidentally modified by any of the reducers. This is important to maintain the integrity of the state and to ensure that the application behaves correctly.

[Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

### combineReducers is a utility function to simplify the most common use case when writing **\_\_**.

`reducers`

### Explain how combineReducers assembles the new state tree.

`CombineReducers` takes an object whose values are different reducing functions and turns it into a single reducing function that can be passed to the `createStore` function, when the store's dispatch function is called, the action is passed to each of the individual reducers, which each update their respective parts of the state and the new state is then assembled into a single object.

### How would you define initial state in an app using combineReducers?

Pass an object to combineReducers where the keys of the object correspond to the keys of the state and the values correspond to the initial state for each key.

[Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

### Why will you want to split your reducing functions as your app becomes more complex?

### The **\_\_** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to **\_\_**.

`combineReducers`
`createStore`

### What is a popular convention when naming reducers?

use the name of the state slice that the reducer is responsible for managing, with a "reducer" suffix, for example, categoriesReducer.

## Reflection

### What are your learning goals after reading and reviewing the class README?

To become more comfortable with the syntax used to create Redux state, and use the combineReducer method.
