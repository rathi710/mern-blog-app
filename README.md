## Introduction

A blog application using the MERN stack (MongoDB, Express js, React js, and Node js).

## Demo

![Image description](screenshot-1.png)

This application is deployed on Heroku and can be accessed through the following link:

[MERN Blog on Heroku](https://mern-blog-01.herokuapp.com/)

## Technologies Used

Some of the technologies used in the development of this web application are as follow:

-   [MongoDB Atlas](https://www.mongodb.com/cloud/atlas): It provides a free cloud service to store MongoDB collections.
-   [React.js](https://reactjs.org/): A JavaScript library for building user interfaces.
-   [Node.js](https://nodejs.org/en/): A runtime environment to help build fast server applications using JS.
-   [Express.js](https://expressjs.com/): A popular Node.js framework to build scalable server-side for web applications.
-   [Mongoose](https://mongoosejs.com/): An ODM(Object Data Modelling)library for MongoDB and Node.js
-   [Heroku](http://heroku.com/): A platform(PaaS) to deploy full stack web applications for free.

## Features

A blog app with the following features.

Unlogged users can do the following:

- View all posts.
- Signup or Login.

In addition to the above points, logged in users can do the following:

- Login or logout.
- Create a new post.
- View/Edit/delete their posts.

## Database

All the models can be found in the models directory created using mongoose.

### User Schema:

- userName (String)
- email (String)
- password (String)

### Post Schema:

- title (String)
- content (String)
- imagePath (String)
