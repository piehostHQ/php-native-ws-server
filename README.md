# WebSocket Client-Server Project
This project demonstrates a simple WebSocket server and client communication. The server is written in PHP, and the client is a basic HTML/JavaScript WebSocket client that allows users to connect to the WebSocket server, send messages, and receive messages from other clients connected to the server.

### Features
WebSocket server written in PHP that listens for connections and relays messages between clients.
A simple web-based client that allows users to send and receive messages via WebSocket.
Real-time communication where clients can send and receive messages instantly.
Requirements
PHP (7.x or later)
A web browser for the client-side application
### Getting Started
Clone the repository
Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/websocket-client-server.git
cd websocket-client-server
```
### Start the WebSocket Server
Make sure you have PHP installed on your system. Open your terminal or command prompt and navigate to the project directory. Run the following command to start the WebSocket server:

```bash
php websocket_server.php
```
This will start the WebSocket server on ws://127.0.0.1:8080.
### Open the WebSocket Client
Open the index.html file in your web browser. This will load the WebSocket client that you can use to connect to the server.

Click on the "Connect" button to connect to the WebSocket server.
Type a message in the input field and click on "Send Message" to send it to the server.
Messages sent will be broadcast to all connected clients.
### Testing
Once the server is running and you have opened the client in your browser, you can test real-time communication between multiple clients:

Open the index.html in different browser windows or tabs.
Connect each client by clicking the "Connect" button.
Send a message from any client, and it will be broadcasted to all other connected clients.
