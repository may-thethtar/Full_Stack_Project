
# Full_Stack_Project
React + Node.js + Express + MySQL example: Build a CRUD App

Project Description
==================
In this project, I had to learn about the React for the front end and Express framework of Node.js for Backend. As a first step, I will build step by step to build Node.js Restful CRUD API using Express, Sequelize with MySQL database. The main function of this web application is CRUD but we implement the functions by using express node.js for the backend.

 I had to  build a full-stack Tutorial Application in that: 
 1. Tutorial has id, title, description, published status.
 2. User can create, retrieve, update, delete Tutorials.
 3. There is a search box for finding Tutorials by title

.

 Project Structure of Node.js Express backend 
======================

 1. Configure parameters for MySQL connection and Sequelize in db.config.js
 2. Initialize and run Express REST APIs in server.js, where we also configure CORS
 3. Add configuration for MySQL database in models/index.js
 4. Create a Sequelize data model in models/tutorial.model.js
 5. Define a controller for handling business logic in controllers/tutorial.controller.js
 6. Create routes for handling CRUD operations and custom finders in routes/tutorial.routes.js

Things that need to install in backend for the project
============================================

 1. express: a popular Node.js web framework used to build web applications and APIs
 2. sequelize: an Object-Relational Mapping (ORM) library that provides a way to interact with relational databases using JavaScript
 3. mysql2: a MySQL client for Node.js that allows you to connect to and query MySQL databases
 4. cors: a middleware that enables Cross-Origin Resource Sharing (CORS) for a web application, allowing it to make requests to resources from different domains
	 Together, these packages provide the foundation for building a web application or API with Node.js that can connect to a MySQL database and handle cross-origin requests.
	 ```
	npm install express sequelize mysql2 cors --save  ``


Project Structure of React Frontend 
=========================================

 1. package.json contains 4 main modules: react, react-router-dom, axios & bootstrap.
 2. App is the container that has Router & navbar.
 3. There are 3 components: TutorialsList, Tutorial, AddTutorial.
 4. http-common.js initializes axios with HTTP base Url and headers.TutorialDataService has methods for sending HTTP requests to the Apis.
 5. .env configures port for this React CRUD App.

Things that need to install in backend for the project
======================
-bootstrap

-axios

-
