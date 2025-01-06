# Bank-Backend
Bank Backend API
This repository contains the backend code for a simple bank application built with Node.js and MongoDB. The application provides RESTful APIs to manage bank accounts and perform money transfers between accounts. It uses Express.js as the web framework and Mongoose as the MongoDB object modeling tool.

Features:
Account Management:
Create a new account
Get account details
Money Transfer:
Transfer money between accounts with atomic transactions to ensure data integrity
MongoDB Integration:
Connects to a local MongoDB database (bankDB)
Technologies Used:
Node.js
Express.js
MongoDB (using Mongoose)
Nodemon for auto-reloading during development
Install dependencies:
npm install
Run the application:
npm start (or npm run dev for development mode with Nodemon)
MongoDB Connection:
The application connects to MongoDB (either local or MongoDB Atlas). By default, it connects to a local MongoDB instance at mongodb://127.0.0.1:27017/bankDB.

If you wish to connect to MongoDB Atlas, you can modify the mongoURI in the code to point to your MongoDB Atlas URL.


