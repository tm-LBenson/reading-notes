<!-- @format -->

# Reading: Context API - Behaviors

## Reading

[Hooks and Context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

### With regard to the React Context API, what does a “provider” do?

With regard to the React Context API, a "provider" is a component that is responsible for displaying the local state of a function or object, and for exposing an API for globally managing them. This allows other components in the application to subscribe to context changes and access the global state.

### With regard to the React Context API, how would we implement a “consumer” role?

With regard to the React Context API, a "provider" is a component that is responsible for displaying the local state of a function or object, and for exposing an API for globally managing them. This allows other components in the application to subscribe to context changes and access the global state.

To implement a "consumer" role using the Context API, you would use the "useContext" hook and wrap the component you want to subscribe to context changes. This hook allows a component to access the current context value and re-render whenever the context value changes.

### Specifically with Context, how are we “wrapping” components to achieve our goals?

Specifically with Context, wrapping components is used to make the context "public" and allow other components to subscribe to context changes and access the global state. This is done by wrapping a component in a Provider component, which allows any component that is a descendant of the Provider to access the context and re-render when the context value changes.

[Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
Takeaway 1:

The Context.Consumer is a React component that can be used to subscribe to changes in the context within a function component. When used, it requires a function as its child, which is passed the current context value as an argument.

Takeaway 2:

When the Provider's value prop is changed, all components that are descendants of the Provider will automatically re-render. This updating process is not affected by the shouldComponentUpdate method, and it ensures that Consumers will be updated even when an ancestor component skips an update.
