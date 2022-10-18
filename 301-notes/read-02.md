Reading
[React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?  
>based on the diagram render happens before componentDidMount

What is the very first thing to happen in the lifecycle of React?  
>The mounting phase begins with the constructor. 


Put the following things in the order that they happen: 

>```constructor``` ```render```  ```componentDidMount```  ```React Updates```   ```componentWillUnmount```


What does componentDidMount do?  
> componentDidMount is a method that will call after the component is rendered. 
> It runs only once after the mount finishes. 


Videos
[React State Vs Props](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

What types of things can you pass in the props?  
>expressions, functions, primitive data types, and objects/arrays can all be passed as props.


What is the big difference between props and state?  
>props are data being passed from parent to child as "html attributes", props are immutable and cannot be modified 
> state can be modified and changed, and can be passed to parent elements through 2 way binding.

When do we re-render our application?
>during the update phase of the life cycle
>Anytime state is changed, the application will re-render


What are some examples of things that we could store in state?  
>some things that can be stored in state are Form data, strings, Objects, Time/Dates, arrays, expressions, events


