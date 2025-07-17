# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

COMPANY : CODTECH IT SOLUTIONS

NAME : R NAVYA

INTERN ID : CT08DN1419

DOMAIN : FULL STACK WEB DEVELOPMENT

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH

# Real-Time Collaborative Editor

This project is a full-stack real-time collaborative text editor built using React, Node.js, WebSocket, and MongoDB.

Multiple users can connect, edit a shared document simultaneously, and see each other's changes live.

It serves as a minimal yet powerful demonstration of WebSocket-based collaboration tools.

# Key Features

 Live Editing – Real-time updates for all connected users.

 User Identification – Prompts each user for a name before joining.

 Persistent Storage – Document changes are saved to MongoDB.

 WebSocket Communication – Efficient real-time broadcasting via native WebSockets.

 Frontend in React – Fast and dynamic user interface.

 Backend with Express & MongoDB – Scalable, persistent data storage and routing.

# How It Works

When a user opens the app, they are prompted for a username.

On connection, the server sends the current document content.

Any edits by a user are sent through WebSocket to the server.

The server updates the document in MongoDB and broadcasts the changes to other clients.

All connected users see the real-time updates with the editor reflecting live changes.

#  File Overview

App.js – Handles user input, displays the textarea, manages socket messages and user info.

index.js – React app entry point that renders the App component.

server.js – Connects to MongoDB, handles WebSocket events, manages edit broadcasts.

.env – Contains the MongoDB URI for secure and flexible environment config.

index.html – The HTML template loaded by React.

# Output

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/5a0b420b-f5cb-4fc0-92d8-a13a518ee324" />


 

