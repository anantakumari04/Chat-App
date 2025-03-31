Overview

A real-time chat application built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js) along with Socket.io for seamless messaging. Users can send and receive messages instantly with a user-friendly interface.

Features

Real-time Messaging using WebSockets (Socket.io)

User Authentication (JWT-based authentication)

One-on-One & Group Chats

Online/Offline Status Tracking

Message Timestamps & Read Receipts

Media Sharing (Images, Files, etc.)

Typing Indicators

User Profile & Avatars

Search & Filter Conversations

Dark Mode & Theme Customization

Responsive UI

Tech Stack

Frontend:

React.js (with Redux for state management)

Tailwind CSS / Material UI for styling

Backend:

Node.js & Express.js

MongoDB (Mongoose for database management)

Socket.io for real-time communication

JWT for authentication

Installation

Prerequisites

Make sure you have Node.js and MongoDB installed on your system.

Steps to Run

Clone the repository:

git clone https://github.com/your-username/chat-app.git
cd chat-app

Install dependencies:

npm install
cd client && npm install

Configure environment variables:

Create a .env file in the root directory and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Start the backend server:

npm run server

Start the frontend:

cd client
npm start

Open http://localhost:3000 in your browser.

API Endpoints

Method

Endpoint

Description

POST

/api/auth/register

Register a new user

POST

/api/auth/login

User login

GET

/api/users

Fetch users

POST

/api/messages

Send a message

GET

/api/messages/:chatId

Get chat messages

Contributing

Feel free to contribute! Fork the repo, make changes, and create a pull request.
