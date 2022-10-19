## Reading  
[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)  


What does .map() return?  
  >using the '''.map()''' on an array will return a new array  



If I want to loop through an array and display each value in JSX, how do I do that in React?  
  > using curley braces ```{} ``` to escape JSX into javascript, you can use the ```.map()``` method to iterate over an array, and return the new array of JSX.
  > React under the hood will unpack the array of JSX and display each item per index. 
  
  
Each list item needs a unique ____.  
> ```key```


What is the purpose of a key?
> A Key on each list item will prevent react from re-rendering an entire array each time a single component is updated. The key shows react the order to render an array.


### [The Spread Operator]((https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)  

What is the spread operator?  
>Semantically speaking, there is no such thing as a ```spread operator``` only ```spread syntax``` or ```spread element```; The Spread syntax is used to take all elements of an array and move them into a new element with each index seperated by a comma.  
>For example: ```const arr = [0,1,2,3]``` after using the spread syntax to call a function ```func(...arrr)``` would be the same as writing ```func(0,1,2,3)```


List 4 things that the spread operator can do.  
>From the [reading](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab) The spread syntax can do the following:  
> - Copying an array
> - Concatenating or combining arrays
> - Using Math functions
> - Using an array as arguments
> - Adding an item to a list
> - Adding to state in React
> - Combining objects
> - Converting NodeList to an array



Give an example of using the spread operator to combine two arrays.  
> ```const arr = ['a','b','c'];```  
> ``` const arr2 = [1,2,3];```  
> ```const newArr = [...arr, ...arr2];```
> ```console.log(newArr);```
> Expected output:  
> ``` ['a', 'b', 'c', 1, 2, 3]```



Give an example of using the spread operator to add a new item to an array.  
> ```let newArr = [...arr, 7]```


Give an example of using the spread operator to combine two objects into one.  
> ```const obj1 = { a : 1, b : 2 };```  

> ```const obj2 = { c : 3, d : 4 };```  

> ```const obj3 = {...obj1, ...obj2 };```  
> ```console.log(obj3)```
> Expected output:  
> ```{a: 1, b: 2, c: 3, d: 4}```


## Videos  
### [How to Pass Functions Between Components]()  

In the video, what is the first step that the developer does to pass functions between components?  
> The developer created a a function, and passed in a person object

In your own words, what does the increment function do?  
> It iterates over the people to find a matching name. Then adjusts the state to increment 

How can you pass a method from a parent component into a child component?  
> You can pass the method as props in the parent element


How does the child component invoke a method that was passed to it from a parent component?  
> ```this.props.PropMethodName(state)```


