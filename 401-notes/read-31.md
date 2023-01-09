<!-- @format -->

## Reading: Context API

## Reading

[Context API](https://reactjs.org/docs/context.html)

### What can React Context provide your app?

React Context provides a way to pass data through the component tree without having to pass props down manually at every level.

### Why might we use Context?

We might use Context to share data between components without the need for props drilling.

### Why should we use it sparingly?

We should use it sparingly because it can make it harder to understand how the data is being passed through the component tree and can make the code more difficult to maintain. Additionally, the Context API is an experimental feature and the implementation may change in the future. Support may fade.

[Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

Consume content from (at least) two of the Awesome React Context links. Share your take-away from each:

[Takeaway 1:](https://egghead.io/lessons/react-creating-providers-and-consumers-with-the-react-context-api)
The React Context API can be used to pass data from a parent component to a distant descendant component, without the need for props drilling, which can be useful when there are intermediate components between the parent and the descendant.

[Takeaway 2:](https://www.youtube.com/watch?v=XLJN4JfniH4&ab_channel=WesBos)
The Context API should be used with caution because it can make it harder to understand how the data is flowing through the component tree, and it can make the code more difficult to maintain. In general, it is recommended to use props or Redux for managing state in larger applications.
