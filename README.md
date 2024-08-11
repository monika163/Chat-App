# Chat App using MERN Stack

It is a real-time application built using the MERN stack. It provides users with a seamless and interactive chatting experience.

Deployed link : https://food-delivery-app-1-ervk.onrender.com/

## Chat App with MERN Stack (MongoDB, Express, React & Nodejs)

- [Key Features](#key-features)
- [Technologies used](#technologies-used)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database](#database)
- [Configuration and Setup](#configuration-and-setup)
- [📸 Screenshots](#screenshots)
- [Author](#author)

## Key Features

- Tech stack: MERN + Socket.io + TailwindCSS + Daisy UI
- Authentication && Authorization with JWT : User Authentication, The application supports user registration and authentication, ensuring secure access to the chat functionality.- Real-time messaging with Socket.io : Real-time Messaging:, Users can chat with each other in real time, sending and receiving messages instantly without the need to refresh the page.
- Message History: The application keeps a history of previous messages, allowing users to view their chat history and scroll through past conversations.
- Online user status (Socket.io and React Context)
- Global state management with Zustand
- Error handling both on the server and on the client

## Technologies used

This project was created using the following technologies.

#### Frontend

- [React js ](https://www.npmjs.com/package/react) - JavaScript library that is used for building user interfaces specifically for single-page applications
- [React Hooks ](https://reactjs.org/docs/hooks-intro.html) - For managing and centralizing application state
- [react-router-dom](https://www.npmjs.com/package/react-router-dom) - To handle routing
- [axios](https://www.npmjs.com/package/axios) - For making Api calls
- [Css](https://developer.mozilla.org/en-US/docs/Web/CSS) - For User Interface
- [Socket.IO](https://www.npmjs.com/package/socket.io-client) - A library that enables real-time, bidirectional communication between the server and the clients, facilitating instant messaging.

#### Backend

- [Node js](https://nodejs.org/en/) -A runtime environment to help build fast server applications using JS
- [Express js](https://www.npmjs.com/package/express) -The server for handling and routing HTTP requests
- [cors](https://www.npmjs.com/package/cors) - We cangive permission to frontend to connect with the database.
- [Dotenv](https://www.npmjs.com/package/dotenv) - Using this we can use the environment variables in our projects.
- [Mongoose](https://mongoosejs.com/) - Help us to connect with the database
- [Nodemon](https://www.npmjs.com/package/nodemon) - Using this package when we will save our project, the server will be restarted.
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Using this we will create the authentication system.
- [Bcryptjs](https://www.npmjs.com/package/bcryptjs) - Using this we will encrypt the users data and store in the data base.
- [concurrently](https://www.npmjs.com/package/concurrently) - allow coders to run multiple scripts with one command.
- [cookie-parser](https://www.npmjs.com/package/cookie-parser) - The cookie-parser middleware simplifies the process of parsing and managing cookies in ExpressJS applications, providing developers with convenient access to client-side cookies for various purposes, including session management and security.
- [socket.io](https://www.npmjs.com/package/socket.io) - Socket.IO enables real-time bidirectional event-based communication.

#### Database

- [MongoDB ](https://www.mongodb.com/) - It provides a free cloud service to store MongoDB collections.

## Configuration and Setup

### Setup .env file

```shell
PORT = 8080
MONGO_URI  = ADD_YOUR_MONGO_URI_HERE
JWT_SECRET_KEY = ADD_YOUR_JWT_SECRET_HERE

```

### Installation

```shell
Install dependencies for backend
npm install

Install dependencies for frontend
cd client
npm install

Run the backend & frontend with concurrently
npm run dev

Run the backend server only
npm start

Run the frontend clients only
npm start
```

## Screenshots

#### Sign Up

![1  sign up](https://github.com/user-attachments/assets/41e27966-f7d2-440c-915b-2f69798c064c)

---

#### Login

![2 login](https://github.com/user-attachments/assets/405485de-a662-48cf-9b99-05d0c9dcd843)

---

#### Page after uset login

![3 after login abhishek](https://github.com/user-attachments/assets/5b4cb6b3-479d-47aa-8115-6c521ae299c4)

---

#### Users Chat

![4  users chat](https://github.com/user-attachments/assets/d0c93134-6805-469f-82f7-02cdcf27044d)
![5  users chat](https://github.com/user-attachments/assets/c1daba20-fb05-456d-9695-41b5ab034750)

---

## Author

- Portfolio: [monika163](----)
- Github: [monika163](https://github.com/monika163)
- Linkedin: [monika163](https://www.linkedin.com/in/monika-dewangan-78a427149/)
