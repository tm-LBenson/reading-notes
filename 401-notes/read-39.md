<!-- @format -->

# Readings: Redux - Additional Topics

## Reading

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

### What concerns are addressed by Redux Toolkit?

Redux Toolkit addresses concerns such as "boilerplate" and "complexity" in setting up a Redux store.

### What does configureStore() do?

configureStore() is a utility function that helps set up the store with the necessary configuration. It allows you to specify the initial state, middleware, and other options for the store, and returns a configured store that can be used in your application.

### How would I use createSlice()?

createSlice() is a utility function that allows you to create a slice of the store to manage a specific piece of state. You would pass it an initial state, and any actions and reducers you want to use for that slice, and it will return a configured slice that you can use in your application.

[MobX](https://mobx.js.org/getting-started.html)

### What is Mobx?

MobX is a library that makes it easy to manage the state of your application. It is similar to Redux in that it provides a way to manage the state of your application, but it has a different approach and a different set of tools for handling state updates.

### How does MobX make it “impossible” to produce an inconsistent state?

MobX uses a strict set of rules for handling state updates, which makes it "impossible" to produce an inconsistent state. It uses a mechanism called "transactions" to ensure that all state updates are atomic and consistent, which makes it difficult to accidentally create an inconsistent state. This is different from Redux which uses a more explicit approach to manage state updates through actions and reducers.

### How would we build a reactive user interface?

A reactive user interface can be built with MobX by using its decorators and observer component. Decorators are used to mark data as "observable", and observer component is used to automatically update the component when the data changes. This creates a seamless, reactive experience for the user, unlike Redux which requires more manual setup to connect components to the store.

## Tutorial

[Tutorial](https://redux-toolkit.js.org/tutorials/overview)

### What take-away(s) did this tutorial provide?

The tutorial collection on the link provided offers a range of guides for learning about Redux. It includes a quick start guide for getting up and running quickly, a tutorial on using Redux in a real-world scenario, and a guide that goes in-depth on how Redux works. Additionally, there is a live-streamed tutorial that covers the basics of setting up and using Redux, as well as updates on its development. The last 4 tutorials are specifically on using Redux Toolkit, including migrating existing applications to use it and using it with TypeScript.

Bookmark and Review
Redux Toolkit (RTK)

HookState

Reflection
What are your learning goals after reading and reviewing the class README?
