# Reading: Component Lifecycle / useEffect Hook

## Reading
[effects hook](https://reactjs.org/docs/hooks-effect.html)

### What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?

useEffect serves the same purpose as the componentDidMount, componentDidUpdate, and componentWillUnmount lifecycle methods in class components. It allows a function component to perform side effects, such as making an API call or setting up a subscription.

### When using the useEffect Hook:

### What does useEffect do?

useEffect is a hook that allows a function component to perform side effects. It is called with a function that contains the code for the side effect.

### Why is useEffect called inside a component?

useEffect is called inside a component to specify the side effect that the component should perform.

### Explain the importance of properly implementing effects with Cleanup

Properly implementing effects with cleanup is important because it ensures that effects are properly cleaned up when a component is unmounted or the effect itself changes, which can help avoid memory leaks and other issues.

## Reflection

### What are your learning goals after reading and reviewing the class README?

Understanding how to use the useEffect hook in a function component and understanding the importance of properly implementing effects with cleanup.