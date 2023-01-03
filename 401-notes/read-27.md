<!-- @format -->

# Reading

## [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

### What was the motivation for introducing Hooks?

The motivation for introducing Hooks was to allow developers to use state and other React features in functional components, rather than just in class-based components.

### What changes are important regarding implementing Hooks versus Component Classes?

When implementing Hooks, you can use functional components instead of class-based components, and you can manage state and side effects using Hooks instead of using the this keyword and lifecycle methods.

### Hooks allow you to reuse stateful logic without changing **\_ **\_\*\*\*\*.

the component hierarchy

## [hooks api](https://reactjs.org/docs/hooks-overview.html)

### Name two rules imposed by React Hook usage.

Only call Hooks at the top level. Don't call Hooks inside loops, conditions, or nested functions.
Only call Hooks from React function components. Don't call Hooks from regular JavaScript functions.

### How would you identify a custom Hook and why might you create one?

You can identify a custom Hook by the `use` prefix in the function name. You might create a custom Hook to share stateful logic that is useful in multiple components.

## [the state hook](https://reactjs.org/docs/hooks-state.html)

### What is a Hook?

A Hook is a function that lets you "hook into" React features from functional components.

### When would I use the useState Hook?

You would use the useState Hook to add state to a function component.

### If you were to add React state to a function component by declaring a state variable:

- ### What does calling useState do?

  Calling useState adds state to a function component and returns a pair of values: the current state value and a function that updates the value.

- ### What do we pass to useState as an argument?

  You pass to useState the initial value of the state.

- ### What does useState return?
  useState returns a pair of values: the current state value and a function that updates the value. They are in an array that can be destructured.
