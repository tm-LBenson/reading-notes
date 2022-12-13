# Readings: Socket.io

## Reading

[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)

#### What is a Web Socket?

- A web socket is a communication protocol used for client - server communication. It provides full-duplex communication channels over a single TCP connection.

#### Describe the Web Socket request/response handshake and what happens once the connection is established.

- > The handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once the connection is established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol.

#### Web Sockets provide a standardized way for the server to send content to a client without first receiving a \_\_\_\_ from that client.

- `request`

<br>
  
[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

#### What does the event handler `io.on()` do?

- The on method is an event handler that handles connection, disconnection, etc...

#### Describe some possible proof of life or proof that the code works as expected

- An example code block:

```js
const app = require('express')();
const http = require('http').Server(app);

app.get('/', function (req, res) {
  res.sendFile('E:/test/index.html');
});
//Whenever someone connects this gets executed
io.on('connection', function (socket) {
  console.log('A user connected');
  //Whenever someone disconnects this piece of code executed
  socket.on('disconnect', function () {
    console.log('A user disconnected');
  });
});

http.listen(3000, function () {
  console.log('listening on *:3000');
});
```

- call `nodemon app.js` in the terminal, and you should be able to render the index.html document in the browser. Upon visiting the root route, you should see in the console that "A user connected" When you leave the browser, you should see "A user disconnected"

#### What does `socket.emit()` do?

- It is the method to broadcast an event to all the clients

<br>

[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

#### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

- A websocket is communication between the Client and the Server over a TCP connection;

- Socket.Io is a library that allows event driven communication between clients and Web Servers.

#### When would you use Socket.IO?

- It can broadcast to multiple sockets at a time.

- It can automatically upgrade the requirements to WebSocket if needed

- IO works on work-based events.

#### When would you use WebSockets?

- When you need real time communication between a client and destination.

- When you don't require persistent connections between two systems

- The communication is one-to-one

## Videos

[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0&ab_channel=TechTerms)

#### What are a couple of key takeaways from this video?

- Open System Interconnection
  The OSI model was introduced to allow different computers to be able to communicate with each other
- Each layer of the OSI are protocols, not applications.

- The session layers are what are required to control the flow of all data between devices.
  Including which data a user is authorized to access, how to data is transmitted, how fast the data is moved, and error control.

- The 7 layers include:

  `7.` Application  
  `6.` Presentation  
  `5.` Session  
  `4.` Transport  
  `3.` Network  
  `2.` Data Link  
  `1.` Physical

<br>

[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk&ab_channel=SunnyClassroom)

#### Translate the gist of this video to a non-technical friend

- TCP is a 3-way handshake performed between the computer and server.
  The computer asks the server to sync.
  The server acknowledges the handshake with a sequence number
  The computer acknowledges the handshake by increasing the sequence number

- After the handshake is performed the computer and server can open a line of communication.

## Reflection

#### What are your learning goals after reading and reviewing the class README?

My goal is to be comfortable with web sockets, and have a firm grasp on the basic syntax, and how to implement the tool in my applications.
