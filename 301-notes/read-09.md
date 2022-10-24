# Reading
## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

What is functional programming?  
Copied from [this](https://www.infoworld.com/article/3613715/what-is-functional-programming-a-practical-guide.html) article
>functional programming means using functions to the best effect for creating clean and maintainable software


What is a pure function and how do we know if something is a pure function?  
>A pure function does not rely on dynamic data such as state, and will always produce the same results with the same arguments provided 


What are the benefits of a pure function?   
> pure functions can be reused without worrying about any dynamic data or state.


What is immutability?  
> Unable to be modified or changed. 


What is Referential transparency?  
> A function that can be replaced by its value. Some function expressions could be used to represent data, have that data stored to a varible and replace the function with that data. 


Videos
[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k&ab_channel=TheNetNinja)

What is a module?  
>Its a section of code that can be called in when needed with the require keyword. Usually a bit of utlity code, and build like a component. 


What does the word ‘require’ do?  
> require tells Node to import the code specified to use in the application


How do we bring another module into the file the we are working in?
>The module needs to be exported with module.exports and each function that will be used needs to be specified. 
> the require function is on the global object. use require('./fileName')


What do we have to do to make a module available?  
>export the code in the module, and require the module in the app that will use the functions that are being exported as a module. 


