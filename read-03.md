## Learn HTML  

When should you use an unordered list in your HTML document?    
>Any time you list items that do not need to be in a particular order or wish to add bullets to your content.  


How do you change the bullet style of unordered list items?   
>You can change the list-style-type property in CSS or change the HTML attribute for the type of bullet  


When should you use an ordered list vs. an unordered list in your HTML document?    
>You should use an ordered list when you need to number items to give them some "order."  


Describe two ways you can change the numbers on items an ordered list provides.    
>You can change the list-style-type property in CSS or change the start, type, and reversed attributes in HTML, which will change the numbers on list items.  

## Learn CSS

# The Box Model 

Describe the CSS properties of margin and padding as characters in a story. For example, what is their role in a story titled: "The Box Model"?  
> Meet Margin, the local police of the parking lot known as "The Page". He keeps everyone away from the outside edges of the lot. His best friend is named Padding; he saves everyone from touching each other. Social Distancing is critical to Padding.

List and describe the four parts of an HTML elements box referred to by the box model.  
>Margin: Outside edge of the element.  
>Border: Sits between margin and padding. Can be styled and colored  
>Padding: space between the main content and the border.  
>Content: Can be anything on the page that has a size, such as text or an image.   


## Learn JS

# Arrays. Operators and Expressions. Conditionals. Loops.

What data types can you store inside of an Array?
>from https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays  
>strings, numbers, objects, and even other arrays   

```const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];```  
Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?  
>The people array is valid JavaScript; you can access the data by using the index of the nested array you wish to select, followed by the index of the item in the nested array you want to. 
>example: ```people[0][0]``` will access 'pete'
