# Simple Java Chat Application

This is a simple multi-user chat application built using Java sockets.

## Features
- Multiple clients can connect to the server.
- Messages sent by a client are broadcasted to all other connected clients.
- Each client is assigned a unique user ID.
- Simple text-based user interface for message input and display.

## How to Run

### 1. Run the Server:
   - Open a terminal.
   - Navigate to the directory containing the source code.
   - Compile and run the `ChatServer.java` file:
     ```bash
     javac ChatServer.java
     java ChatServer
     ```
   - The server will start on port 12345.

### 2. Run the Client(s):
   - Open a terminal.
   - Navigate to the directory containing the source code.
   - Compile and run the `ChatClient.java` file:
     ```bash
     javac ChatClient.java
     java ChatClient
     ```
   - You can run multiple clients in separate terminals to simulate a chat session.

## Dependencies
- This project uses standard Java libraries. No external dependencies are required.

## Known Issues
- This is a simple implementation. Further improvements such as client disconnection handling, user authentication, and a GUI can be added.
