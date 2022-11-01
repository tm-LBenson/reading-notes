
# Readings: CRUD


## Reading
[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)


In your own words, describe what each group of status code represents:

100’s =  
>Informal status codes, the header part of the request has been received. 


200’s =  
>These are the success codes


300’s =  
>These are the redirection codes. 


400’s =  
>These are the invalid client error codes


500’s =  
> These are the server errors and some generic errors

What is status code 202?  
> This is accepted but not yet complete

What is status code 308?  
> This indicates a permanent redirect, meaning the URI has changed. 

What code would you use if an update didn't return data to a client?  
>204 would be used after an update if data isn't returned to the client. 

What code would you use if a resource used to exist but no longer does?  
> 202 If the client tried to delete something that used to exist, or 404 if the resource is not found. 

What is the 'Forbidden' status code?  
>403

Videos
[Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

Why do we need to pull our MongoDB database string from our server and put it into our .env?  


>The database string includes the login and password for the database and must be protected  


What is middleware?  
>middleware is code that runs before a response or before a request to modify and check the data, and it is typically called with the .use() method  



What does app.use(express.json()) do?  
> It is used to parse incoming Data as JSON  




What does the /:id mean in a route?  
>Any text after the slash will be considered an ID, and the route will attempt to target that path. The id is a parameter. 


What is the difference between PUT and PATCH?  

>Put is used for a full update, PATCH is used during a minor edit or partial update  



How do you make a default value in a schema?  
>with the default property assigned to the options  
>

What does a 500 error status code mean?  
> 500 is on the server side and is a generic error response  



What is the difference between a status 200 and a status 201?  
> 200 means understood, 201 means understood and created a resource.  



