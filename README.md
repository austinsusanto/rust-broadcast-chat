# Reflection

## 2.1. Original code of broadcast chat.

![Broadcast chat server & 3 clients](assets/1.png)
In this test, we can see the original server and client program. The server program is run first and the client program is run afterwards. Everytime a new client connects to the server, the server will show a new connection message. The client also has the ability to type a message. The message the will be sent to the server and the server forwards it to the other clients.

## 2.2. Modifying the websocket port

In this tutorial, the port in both sides is edited into 8080. In the client.rs we can edit it from the ClientBuilder and in the server.rs we can edit it from the TcpListener. The program will work like normal and no function will change. The port is only used for connection so that the client and server can interact well.
