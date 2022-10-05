# Class 13 Reading


Explain to a non-technical recruiter what the Chat Example (above) does.

It's an example of a web socket(browser to server) and socket (client to server) and their handshake

What proof of life are we getting on the backend from the above app?

The user connected console log

Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

i0.on()


## Rooms

What is a room and how might a room be useful?

its basically a channel that sockets can join and leave it useful because it can help broadcast events to clients

How do you join a room?

To Join:
 io.on("connection", (socket) => {
  socket.join("some room");
});

how do you leave a room?
To Leave :
io.on("connection", (socket) => {
  socket.leave("some room");
});

## Namespaces

What is a Namespace and what does it allow you to do?

a communication channel that allows you to seperate the logic of your app over a single connection that is shared

Each namespace potentially has its own what? (hint: 3 things)

- event handlers
- room
- middleware

Discuss a possible use case for separate namespaces

if you want to create a namespace for people who are specifically authorized.