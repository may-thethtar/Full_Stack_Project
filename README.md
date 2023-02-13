# Full_Stack_Project
React + Node.js + Express + MySQL example: Build a CRUD App

Project Description
==================
In this project, I had to learn about the React for the front end and Express framework of Node.js for Backend. As a first step, I will buid step by step to build Node.js Restful CRUD API using Express, Sequelize with MySQL databse. The main function of this web apllication is CRUD but we implemt the functions by using express node.js for the backend.
 I had to  build a full-stack Tutorial Application in that:
-Tutorial has id, title, description, published status.
-User can create, retrieve, update, delete Tutorials.
-There is a search box for finding Tutorials by title.

 Project Structure of Node.js Express backend 
=========================================
-Configure parameters for MySQL connection and Sequelize in db.config.js
-Initialize and run Express REST APIs in server.js, where we also configure CORS
-Add configuration for MySQL database in models/index.js
-Create a Sequelize data model in models/tutorial.model.js
-Define a controller for handling business logic in controllers/tutorial.controller.js
-Create routes for handling CRUD operations and custom finders in routes/tutorial.routes.js



Things that need to build the project
-express: a popular Node.js web framework used to build web applications and APIs
-sequelize: an Object-Relational Mapping (ORM) library that provides a way to interact with relational databases using JavaScript
-mysql2: a MySQL client for Node.js that allows you to connect to and query MySQL databases
-cors: a middleware that enables Cross-Origin Resource Sharing (CORS) for a web application, allowing it to make requests to resources from different domains
   Together, these packages provide the foundation for building a web application or API with Node.js that can connect to a MySQL database and handle cross-origin requests.


