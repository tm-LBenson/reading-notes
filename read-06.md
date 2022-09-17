
# Reading
## JavaScript Object Basics

How would you describe an object to a non-technical friend you grew up with?  
> an Object is a key value pair. The key is the work you say to get the data. So if the key is FavoriteFruit, and the value is apple, When I say FavoriteFruid, I get the answer apple. 



What are some advantages to creating object literals?  
>  Object literals are great for building a data template with predefined properties. It can make the code more readable and allow storing templates on their JS file.  




How do objects differ from arrays?  
> Arrays store data in a numeric sequence that can be accessed by indexing. Objects have no proper series, and the 'key' can access the values.  



Give an example for when you would need to use bracket notation to access an object's property instead of dot notation.  
``` const cardsInHand = {
 Card1 : 'Ace of Spaces',
 Card2 : 'Two of Hearts',
 Card3 : 'Four of Diamonds'
 }
 
 cardsInHand[Card1]
```  

>in the above code block, Card1 could be a variable to check which card a user is holding in their hand. The variable must reference a string.

Evaluate the code below. What does the term this refer to and what is the advantage to using this?  
```
const dog = {  
  name: 'Spot',  
  age: 2,  
  color: 'white with black spots',  
  humanAge: function (){  
    console.log(`${this.name} is ${this.age*7} in human years`);  
  }  
}  
```

>In the case of the code block above, 'this' refers to the dog object.  

#[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)  


What is the DOM?  
>DOM is the Document Object Model. It represents the webpage and all its contents. 


Briefly describe the relationship between the DOM and JavaScript.  
> JavaScript can access the DOM to manipulate HTML content programmatically. 




