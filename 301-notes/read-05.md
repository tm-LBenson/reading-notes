
##Reading
###[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

What is the single responsibility principle, and how does it apply to components?  
>A component should only do 1 thing, if it does more it should be broken into smaller components. 


What does it mean to build a ‘static’ version of your application?  
>Build a site that has no interactivity. For example, it shows the componant hierarchy but does not pass any data or use state. 


Once you have a static application, what do you need to add?  
>After the static application is build, next is to figure out where state lives. More components may be required to handle state for multiple children elements sharing the same state. 



What are the three questions you can ask to determine if something is state?  
> ```  Is it passed in from a parent via props? If so, it probably isn’t state.```  
> ```Does it remain unchanged over time? If so, it probably isn’t state.```  
> ```Can you compute it based on any other state or props in your component? If so, it isn’t state.```  





How can you identify where state needs to live?  
>If there are multiple elements that require the state, then the state needs to live in the element above those elements so it can be passed down. More components may be required to hold state. 


[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

What is a “higher-order function”?  
>A higher-order function takes in a function as an arguement and returns a function


Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?  
> it is returning an anonymous arrow function that checks if m is greater than n


Explain how either map or reduce operates, with regards to higher-order functions.  
> Both map and reduce are methods that can be called on an array. When map is called, a callback funcation is passed into the method as an aruguement. 
> The function is returned for each item in the array. A new array will be returned when the map method is finished on every element of the array it was called on.
> higher-order functions take in a functions as an argument, and return a function just like the map and reduce methods. 

