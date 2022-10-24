
Reading
[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

What does REST stand for?  
>Representational State Transfer

REST APIs are designed around a ____.  
Copied from the reading above:
> REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

What is an identifier of a resource? Give an example.  
> A URI is a unique resource identifier. It can be found in the URL and typically has a uinique ID imbedded into the query string which represents specific data to pull during a request. 

What are the most common HTTP verbs?  
>GET, and POST are the two most common verbs, because the browser can support them by default. PUT, PATCH, and DELETE requests can be sent as well. 

What should the URIs be based on?  
> URIs should be based on nouns

Give an example of a good URI.  
>.com/orders

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?  
> A 'Chatty' web API is making to many calls creating a large load of data. 

What status code does a successful GET request return?  
>200 OK

What status code does an unsuccessful GET request return?  
>It could return a status code 400 if its a bad request, 404 if not found or 204 if there is no content

What status code does a successful POST request return?  
>201 created 

What status code does a successful DELETE request return?  
>204 no content 
