
# Readings: More CRUD  

## Reading  
[CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)  

Which HTTP method would you use to update a record through an API?  
> I would use PUT for an update. 

Which REST methods require an ID parameter?  
> PATCH, PUT, DELETE, sometimes GET  

## Videos  
[Speed Coding: Building a CRUD API (Watch a Twitch streamer code an Express API in 20 minutes!)](https://www.youtube.com/watch?v=EzNcBhSv1Wo&ab_channel=CodingGarden)  

What’s the relationship between REST and CRUD?   
>the REST methods are used to complete each task of CRUD. POST for Create, GET for READ, PUT for update, and DELETE for Destroy.   

If you had to describe the process of creating a RESTful API in 5 steps, what would they be?  
> Step 1, build the primary server including the required middleware  
> 
> Step 2, create all the endpoints with the 5 methods for READ one, CREATE one, UPDATE one, and DELETE one.   
> 
> Step 3, Bring in the database, like mongoose, and create Schema/models  
> 
> Step 4, Create the controllers for each endpoint and the logic for each DB method.  
> 
> Step 5, add Auth and optional middleware such as JOI. Add any error handling, and conduct testing.  
> 
> 
