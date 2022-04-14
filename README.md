# What-A-Sap

Socket.io is a Javascript library for web apps that allows real-time communication between clients and servers. It's built on top of the Websockets API (client) and Node.js (server). The most common use cases for Websockets and socket.io are chat applications or a social media feeds in which a user's page (client) receives messages or posts from other users.

# Chat server responsibilities
- Serve the HTML, CSS and JavaScript client files to the users
- Start the Socket.io connection
- Receive events from clients (like a new chat message) and broadcast them to other clients

# Chat client responsibilities
- Load socket.io client library from a CDN
- Establish connection with the Socket.io running in our server
- Ask the user to enter his name so we can identify him in the chat
- Emit and receive events to/from Socket.io running in our server
- Add our own messages to the chat via JavaScript
