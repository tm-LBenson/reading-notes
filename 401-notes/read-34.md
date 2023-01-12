<!-- @format -->

# Reading: API Integration

## Reading

[Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

### Explain the different between a query string parameter and a path parameter.

Query string parameter and path parameter are both ways to pass information to an API, but query string parameters are passed in the URL itself, while path parameters are part of the URL path.

### What would our API URL with a path id parameter be given the following information:

1. Domain: http://our-site.com

2. `v3`

3. model name: stuff

4. id: things

`http://our-site.com/v3/stuff/things`

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

A dynamic API with an "interface" allows a user to interact with a database by performing CRUD operations through a set of pre-defined routes and methods.
CRUD is Create Read Update Delete, and used to change data on a website

[Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

### Describe how you would use middleware to implement basic and bearer auth.

Middleware is used to implement basic and bearer auth by checking the request headers for the correct authentication credentials before allowing access to the protected routes.

### Describe the handshake necessary to implement OAuth.

OAuth is an open standard for authentication that allows users to authorize third-party applications to access their information without sharing their login credentials. It involves a handshake process in which the user grants permission for the application to access their information.

### Describe how Role Based Access Control works to a non-technical friend.

Role Based Access Control (RBAC) is a system that controls access to certain parts of a website or application based on the user's role or permission level. It allows different levels of access to different users based on their role in the organization.
