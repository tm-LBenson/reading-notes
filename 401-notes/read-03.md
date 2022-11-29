# Readings: Express REST API

## Readings
[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)  
  
#### Classes are a template for creating ____.  

Objects
  
#### Can a class declaration be hoisted?  
  
  Class declarations can not be hoisted like a function declaration.
  
#### How would you describe a constructor and contextual “this” to a non-technical friend?  
  
  A class constructor is like the blueprints for a house. You can build several houses from 1 set of blueprints, and each house will look the same, but they are all different houses. The word 'This' refers to the current house built by the blueprints. Each time the blueprints are read and a house is being constructed, the 'This' keyword refers to that current house.  
   
[Using Express Routing](https://expressjs.com/en/guide/routing.html)  
  
#### Within Express, what does routing refer to?  
  
> Routing refers to how an application’s endpoints (URIs) respond to client requests.
  
#### What is the difference between a route path and a route method?  
  
The route path is a string, string pattern, or regular expression that works like an address for the HTTP request. The route method is the type of request sent to the path, such as get, post, or patch requests. Route methods also include ```app.use()```, and ```app.all()```.  
  
#### When is it appropriate to add next as a parameter to a route handler, and what must you do if next has been passed to your middleware as a parameter?  
  When using multiple callback functions in a route, the ```next()``` function can be called to go to the next callback function. It can be used conditionally for error handling to prevent sending a specific response when an error has occurred. In addition, it is used in middleware to tell the middleware to move to the next callback.  
  
[Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)  
  
#### What is an Express Router?  
  
  Express Router is a mini version of Express for handling the route methods.  
  
#### By what mean do we initialize Express.Router() in an express server?  
  
We create an instance of Express.Router() for each path allows for the chaining of route methods and making the routes modular. 
  
#### What do we use route middleware for?  
  
Route middleware runs code on a request before the route handler is run. So, for example, it can be used for authentication before sending a response. 
  
## Reflection  
  
#### What are your learning goals after reading and reviewing the class README?  
  
My learning goals remain to retain and study as much information as possible before the end of 401. I will note the information I wish to dive deeper into. I will keep working toward my professional development each day. 
