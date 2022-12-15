# Readings: Message Queues

## Reading

[Socket.io Chat Example](https://socket.io/get-started/chat/)

#### Explain to a non-technical recruiter what the Chat Example (above) does.

The above chat example is creating a relationship between client and server, sort of like a phone call. Once the client is connected to the server by visiting the root url, the user is able to emit messages, and the server will receive the messages. The express server is being used to serve an html page to the user to interface on, as well as power the socket server.

#### What proof of life are we getting on the backend from the above app?

`'a user connected'`

#### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

`broadcast`

[Rooms](https://socket.io/docs/v4/rooms)

#### What is a room and how might a room be useful?

A room is a server side area that a client can connect to. The client can emit and receive data while connected to the room, and the server can emit to several rooms at the same time. In a chat application it would be a way to create a private group chat.

#### How do you join a room?

Can you join a room with the `.join()` method, and pass in the user id as an argument.

#### how do you leave a room?

To leave a room a client can simple disconnect, and no special "tear down" is required.

[Namespaces](https://socket.io/docs/v4/namespaces/)

#### What is a Namespace and what does it allow you to do?

> A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").

#### Each namespace potentially has its own what? (hint: 3 things)

- Event Handlers
- Rooms
- Middleware

#### Discuss a possible use case for separate namespaces

- > you want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application
- > your application has multiple tenants so you want to dynamically create one namespace per tenant

Reflection

#### What are your learning goals after reading and reviewing the class README?

In lab 12, I ran my socket server to push "packages" this caused a socket to emit, but unless I turned on my listening server, all the data pushed would be lost. I am looking forward to being able to build a queue to persist that data until my listener is ready to read it.
