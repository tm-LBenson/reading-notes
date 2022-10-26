# Readings: In memory storage



## Reading
## [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

What is a 'call'?  
> On a high-level a call is the next task the script will perform. Such as function declaration, variable declaration, function calls. 

How many 'calls' can happen at once?  
>The call stack is single execution. 

What does LIFO mean?  
> Last in - first out; Like in an array with array.push(), array.pop()

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.  
![Call Stack](https://user-images.githubusercontent.com/105423307/198051862-2eabd046-efb9-4540-84d2-6f538e499ac9.png)


What causes a Stack Overflow?  
>If a function calls it self, with no way to stop calling it self, it will create a stack error.

## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)  

What is a 'reference error'?  
>When calling a variable or function expression before its declaration

What is a 'syntax error'?  
> When the code cannot be parsed properly due to invalid syntax. Such as a typo, missing curly brace, misplaced parenthesis, etc... 

What is a 'range error'?  
>When trying to manipulate an object with an invalid length, such as indexing an empty array to the last index.

What is a 'type error'?  
> When the property of the value is incompatible with what you are attempting to access. Such as reading a property that doesn't exist in an object. 

What is a breakpoint?  
> it's a point in the debugger that pauses execution to evaluate the code at that spot for debugging. 

What does the word 'debugger' do in your code?  
>it creates a breakpoint in the code to pause the code at that point. 

