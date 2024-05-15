# MERN: Full-stack Chat Application

#### Introduction

The MERN stack which consists of **Mongo DB**, **Express.js**, **Node.js**, and **React.js** is a popular stack for building full-stack web-based applications because of its simplicity and ease of use. In recent years, with the explosive popularity and the growing maturity of the JavaScript ecosystem, the MERN stack has been the goto stack for a large number of web applications. This stack is also highly popular among newcomers to the JS field because of how easy it is to get started with this stack.
<br/><br/>
Its frontend is built with  React and MaterialUI.
The backend is built with Express.js and Node.js.
Real-time message broadcasting is developed using [Socket.IO](https://socket.io/).

### Features

This application provides users with the following features
<br/>
* Authentication using **JWT Tokens**
* A **Global Chat** which can be used by anyone using the application to broadcast messages to everyone else.
* A **Private Chat** functionality where users can chat with other users privately.
* Real-time updates to the user list, conversation list, and conversation messages

### How to use

You can have this application up and running with just a few steps because it has both the frontend and the backend in a single repository. Follow the steps below to do so.

1. Clone this repo
2. Go to the client folder using the terminal and install dependencies using npm i and for the server go to the parent folder and perform npm i and connect to Mongodb database I use mongodb compass for connection
5. The frontend of the application will be automatically opened in your web browser and you can test it away.


### Things to note

* The frontend is created using [create-react-app](https://github.com/facebook/create-react-app)
* Database connections in the backend are handled using the [Mongoose ORM](https://mongoosejs.com/)
* Code quality is ensured using (ESLint)[https://eslint.org/]

