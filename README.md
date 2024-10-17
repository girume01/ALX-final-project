# Real-Time Chat Application

This project is a real-time chat application built using the **MERN stack** (MongoDB, Express, React, and Node.js) with **Socket.io** for instant messaging. Users can register, log in, and communicate in real-time with other users in private conversations.

## Features

- **User Authentication**: Users can sign up and log in securely.
- **Real-Time Messaging**: Instant messaging using Socket.io.
- **User Status**: Shows active users online.
- **Conversation History**: Displays previous conversations with users.
- **Responsive UI**: A clean and modern interface designed with mobile responsiveness.
- **REST API**: Backend API for user management and message retrieval.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.io
- **API Testing**: Postman
- **Authentication**: JSON Web Tokens (JWT)

## Project Structure

### Key Frontend Files

- `App.js`: Main routing component with protected routes.
- `Dashboard/index.js`: Chat dashboard that displays conversations, active users, and messages.
- `Form.js`: Handles user login and registration.

### Key Backend Files

- `server.js`: Sets up Express server and Socket.io communication.
- `/routes`: Contains API routes for user registration, login, and messaging.
- `/models`: MongoDB schemas for users and messages.

## Getting Started

### Prerequisites

- **Node.js** and **npm** installed on your local machine.
- **MongoDB** (Make sure you have a MongoDB instance running locally or use MongoDB Atlas).
