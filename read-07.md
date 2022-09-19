
Understanding how to lay out objects is vital to implementing efficient modular code. Building objects with literal can work in some small applications, but adding new Objects programmatically could be challenging and create bugs. In addition, debugging would be a challenge when methods are located in hundreds of different objects instead of just the prototype.

## Readings: Object-Oriented Programming, HTML Tables

# Reading
[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)  

Explain why we need domain modeling.
> a correctly modeled domain is flexible and able to handle the required data when building new objects. Storing methods on the prototype will save memory and allow the function to be updated in one location instead of every object created, saving valuable time and can prevent potential bugs from manipulating so much code at once.


[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

Why should tables not be used for page layouts?  
> Tables can over complicate the layout of a page making screen readers full data from random spots on a page. It can be very confusing for users with acessability issues. The complex layout of a table can make updating and debugging code very difficult.



List and describe 3 different semantic HTML elements used in an HTML <table>.  
>   ```<td>``` This element is the table data element, and represents a single table cell  
  > ``` <tr>``` This element is the table row element, and will create a new row with ```<td>``` elements as child elements  
  > ``` <th>``` This element is the table heading element, and will create the top row of a table (styles to bold by default)  
  
  
  
  
[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)  
  
What is a constructor and what are some advantages to using it?  
>  a constructor is like a Schema for objects to be created using the ```new``` keyword. It can create entire objects to include their methods in just a few lines of code saving memory and making the code easier to modify.
  
  
  
How does the term ```this``` differ when used in an object literal versus when used in a constructor?  
>  in an object literal ```this``` refers to the object that the method is contained in.  
  > in a constructor ```this``` refers to the future object that the constructor is going to create.  
  
  
[Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)  
 
Explain prototypes and inheritance via an analogy from your previous work experience.  
NOTE: This is a very common front end developer interview question  
>  Growing up on a farm, tools were a common Christmas present as a younger teenager. I had an old pickup truck that I would use to travel across the fields to tend the fences or check on horses. I would use the tools kept in my toolbox to maintain this old truck; however, not every tool I used could be found in my toolbox; I would have to inherit tools from my grandfather's toolbox. This is like having methods stored on the prototype. With my ```new``` Toolbox and its collection of tools, some of the tools I used were from a different toolbox.
  
