<!-- @format -->

# Reading: Component Based UI

## Reading

[react hello world](https://reactjs.org/docs/hello-world.html)

#### What are the building blocks of a React app?

Elements are the smallest building blocks of a React app and represent DOM nodes or trees of DOM nodes. Components are functions or classes that produce elements and can be reused throughout the app.

#### What is the difference between an element and a React component?

Elements are the smallest unit of building a React app, and represent a DOM node or tree of DOM nodes. Components are the functions or classes that create and return elements, and can be customized and reused throughout an app.

#### What are some advantages of React’s component based architecture?

React's component-based architecture allows for the reuse, modularity, and separation of concerns in building an app. It also improves performance and is easy to learn.

[introducing JSX](https://reactjs.org/docs/introducing-jsx.html)

#### What is JSX and why do we use it?

JSX is a syntax extension for JavaScript that allows you to write HTML-like code in your JavaScript files. It is used to describe what the UI of a React app should look like and is typically used with React to build user interfaces.

#### Describe the process of embedding JavaScript expressions in JSX.

To embed a JavaScript expression in JSX, you can wrap it in curly braces and place it inside the JSX code. For example, you can use the expression `{2 + 2}` inside a JSX element, or you can call a JavaScript function such as `{formatName(user)}` and embed its return value in JSX. You can also use curly braces to specify an attribute value, such as `<img src={user.avatarUrl}>`. It is important to use either quotes (for string values) or curly braces (for expressions) in JSX, but not both in the same attribute.

#### Is it safe to embed user input in JSX? Explain.

JSX automatically escapes user input to prevent injection attacks, making it safe to embed user input in JSX code.

[rendering elements](https://reactjs.org/docs/rendering-elements.html)

#### Explain what a React Component is to a non-technical friend.

A React component is a reusable piece of code that represents a part of a user interface. It can be customized and can have its own internal state and behavior. Components help to make a user interface easier to understand and manage by breaking it down into smaller pieces.

#### Describe mutability and React Components, specifically, how is the UI updated?

In React, components can have mutable state, which means that their data can change over time. When the state of a component changes, React uses a virtual DOM to automatically update the corresponding parts of the UI to reflect these changes. This helps to optimize the performance of the app by minimizing the number of DOM manipulation operations required.

#### If changes are made to the UI, what does React update?

React updates specific parts of the UI when changes are made, using a virtual DOM to efficiently update the necessary components. The virtual DOM helps to optimize the performance of the app by minimizing the number of DOM manipulation operations required to update the UI.

#### Looking ahead at this module’s course schedule, What do you look forward to learning?

I am looking forward to finally having full access to React hooks. I have been waiting for these for awhile. 

#### What are your learning goals after reading and reviewing the class README?

I want to be proficient and comfortable with all the React syntax. 