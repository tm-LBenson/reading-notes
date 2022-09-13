Understanding semantics is essential when working for anyone or with anyone.
It will keep everyone on the same page. Furthermore, proper semantics can lead to better SEO, which developers and companies need to be successful. 
## Introduction to HTML
## HTML Text Fundamentals. HTML Advanced Text Formatting.

Why is it essential to use semantic elements in our HTML?
>"Some of the benefits of writing semantic markup are as follows:

>Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
>Screen readers can use it as a signpost to help visually impaired users navigate a page
>Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
>Suggests to the developer the type of data that will be populated
>Semantic naming mirrors proper custom element/component naming" from https://developer.mozilla.org/en-US/docs/Glossary/Semantics


How many levels of headings are there in HTML?
>Headings go from ```<h1>``` to ```<h6>``` making 6 levels of headings in HTML


What are some uses for the <sup> and <sub> elements?
  >```<sup>``` is for superscript when writing above some text. For example, for exponents, also, it can be seen on Wikipedia to note a reference to a particular part of an article. 
  >```<sub>``` is for subscript which can be used to write a chemical formula or in Mathcad to index an array as a variable.
  
When using the <abbr> element, what attribute must be added to provide the full expansion of the term?
>the title attribute can be used to expand the full abbreviation per https://developer.mozilla.org/en-US/docs/Web/HTML/Element/abbr


## How CSS Is Structured
  
What are ways we can apply CSS to our HTML?
  >CSS can be applied inline, with a styles tag, or through a CSS file linked in the head of the document.
  
  
Why should we avoid using inline styles?
  >It makes the HTML challenging to read  
  >inline styles override style sheets with the highest level of specificity  
  >They can also negatively affect performance, making the HTML take longer to load.  
  
Review the block of code below and answer the following questions:  
 ```
  h2 { 
     color: black;
     padding: 5px;
   }
```   
  What represents the selector?  
  h1 is the selector for all ```<h1>``` elements  
  
  
  Which components are the CSS declarations?   
  ```
  color: black;
  padding: 5px;
  ```   
  >the entire code block above are the declarations. In this case there are 2 declarations  
    
  Which components are considered properties?  
  >the first half of the declaraction is the property; color and padding are both properties. 
  
    ## Learn JS
  
What data type is a sequence of text enclosed in single quote marks?
  >String is the data type inside quotes
  
List 4 types of JavaScript operators.  
  ```&&``` and  
  ```||``` or  
  ```??``` nullish coalescing
  ```++``` incrementing  
  
  
Describe a real-world Problem you could solve with a Function.  
>I am bad with anniversaries. I could write a function to take in a date as a parameter, and it would return how many years anniversary I am currently on 
  
  
## Making Decisions In Your Code – Conditionals.

  An if statement checks a __ and if it evaluates to ___, then the code block will execute.
  >condition(boolean)  
  >true
  
What is the use of an ```else if```?
  >the ```else if``` is used to check for a boolean; after the first ```if``` was found false, the condition has more than one possible result. See example below  
  ```
  if (condition === true){
  return `first condition was true`
  }
  else if (newCondition === true){
  return `second condition was true`
  }
  else{
  return `no conditions were true`
  }
  ```  
  
List 3 different types of comparison operators.
  ```< > = != <= >= ``` 
What is the difference between the logical operator ```&&``` and ```||```?
  for ```&&``` all conditions must be ```true``` or it will return ```false```
  for ```||``` 1 or more conditions needs to be ```true``` for it to return ```true```
  
## Things I want to know more about

