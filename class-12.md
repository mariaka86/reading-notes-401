# Class 12 readings

What is a Web Socket?

it is a computer communications protocol

Describe the Web Socket request/response handshake and what happens once the connection is established.

it begins with the client sending the Web Socket a handshake request then the server returns a Websocket handshake response.Once a connection is established the client and server can now send Websocket data or text frames back and forth in full duplex mode

Request

Socket.io Tutorial

What does the event handler io.on() do?

it enables real-time bidirectional event-based communication.


Describe some possible proof of life or proof that the code works as expected

getting a message from the server

What does socket.emit() do?

it sends a message to all the connected clients

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

Socket.IO is a js library while WebSocket is a communications protocol

When would you use Socket.IO?

when trying to communicate with the server and client to get a message to the client

When would you use WebSockets?

when trying to communicate between the browser and a server and being able to send messages to a server.

What are a couple of key takeaways from this video?

Please     (Physical Layer)
Do           (Data Link Layer)
Not          (Network Layer)
Tell          (Transport Layer)
Secret      (Session Layer)
Password (Presentation Layer)
Anyone    ( Application Layer )



Translate the gist of this video to a non-technical friend
     

Message	Description
Syn   Used to initiate and establish a connection. (client asks server to open connection)
ACK	    Helps to confirm to the other side that it has received the SYN.(server says yes and asks client to do the same)
SYN-ACK	SYN message from local device and ACK of the earlier packet.


