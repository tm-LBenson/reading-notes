
## Reading
React Docs - Forms

## [What is a ‘Controlled Component’?](https://reactjs.org/docs/forms.html)  

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.  
>If I want to store the user responses to local storage from the forms, updating state would be the best choice, if I do not want to store the data, I will update state after submission



How do we target what the user is entering if we have an event handler on an input field?  
> we can can pass in the event into the event hanlder fuction, and use the event.target on the input element. I can use React.createRef() method to target a specific input field as well.   



## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)  

Why would we use a ternary operator?  
>the ternary operator ```?``` is used as a conditional expression. It can be used anywhere an expression is used.

Rewrite the following statement using a ternary statement:  

```if(x===y){  
  console.log(true);  
} else {  
  console.log(false);  
} 
```    
   
```   
x===y ? console.log(true) : console.log(false) 
```    
  
  
