# Reading: Bearer Authorization


## Reading
[Intro to JWT](https://jwt.io/introduction/)

### What is a JSON Web Token (JWT)?  
  
  A JSON Web Token is a 3-part token sent as encoded JSON to a client from a server during authentication. The header contains the method of encoding and the type of token. The second part is the payload which contains JSON with the user's data, metadata, and any relevant data the server will require. The third part is the signature, which comprises an encrypted secret. 
  
### When should we use JSON Web Tokens?  
  
  JWT is a fast and easy way to handle authentication and prevent the user from having to reverify their identity each time data is attempted to be accessed. 
  
### Claims are expected in which structural component of a JWT?  
  
  Claims are expected in the payload of the JWT.
  
[Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)  

### If I get a JWT and I can decode the payload, how can we call that secure?  
  
  The payload shouldn't contain any sensitive data. If someone attempts to modify the payload, the server will reject the JWT because it needs to be signed if the data is changed. Unless the person trying to modify the payload knows the secret for the signature, the JWT will not be altered. 
  
### If sending a JWT, what must the sender and receiver both know? Hint, it's appended in the signature.  
  
  Both the receiver and sender must know a secret. 
  
### Explain how concatenated content and secret can be sent and received securely by a non-technical recruiter.  
  
  The content is changed into a different text format, and the secret is encrypted so that the only way to duplicate the signature is to know the true secret used in the signature. 
  
## Videos  

[JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo&ab_channel=Bitfumes)  

### Why use JWT?  
  
  JWT is fast, and because they use the signature system and do not contain sensitive data, they are secure. They can be stored in a cookie and accessed only through HTTP, and they cannot be modified with javascript. 
  
### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.  
  
  Being compact and self-contained allows the JWT to be stored in a cookie, making it more secure because the cookie cannot be accessed with JavaScript. 
  
### What are the three components (the structure) of a JWT signature?  
  
  The header contains the method of encoding and the type of token. The second part is the payload which contains JSON with the user's data, metadata, and any relevant data the server will require. Finally, the third part is the signature, which comprises an encrypted secret. 
  
Reflection  
### What are your learning goals after reading and reviewing the class README?  
  My goal today is to learn how to implement JWT during the auth process.
  I want to learn the syntax for building virtual fields to manipulate data without storing the new data in the database. 
  
  
