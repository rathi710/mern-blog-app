## Introduction

A blog application using the MERN stack (MongoDB, Express js, React js, and Node js) deployed on Kubernetes.

## Images

![image](https://user-images.githubusercontent.com/85077087/222977075-494d7800-1baf-4d14-84c5-ca952663ff12.png)

![Screenshot (236)](https://github.com/rathi710/mern-blog-app/assets/85077087/a75638b3-5e9d-46ae-b394-de162d5e71e7)

![Screenshot (237)](https://github.com/rathi710/mern-blog-app/assets/85077087/8a88fcce-8782-413a-aa82-eeec3411e270)

![Screenshot 2023-09-05 024420](https://github.com/rathi710/mern-blog-app/assets/85077087/361ab2a9-1db7-4385-8b2c-3a99623825e3)

## Technologies Used

Some of the technologies used in the development of this web application are as follow:

-   [MongoDB Atlas](https://www.mongodb.com/cloud/atlas): It provides a free cloud service to store MongoDB collections.
-   [React.js](https://reactjs.org/): A JavaScript library for building user interfaces.
-   [Node.js](https://nodejs.org/en/): A runtime environment to help build fast server applications using JS.
-   [Express.js](https://expressjs.com/): A popular Node.js framework to build scalable server-side for web applications.
-   [Mongoose](https://mongoosejs.com/): An ODM(Object Data Modelling)library for MongoDB and Node.js
-   [Heroku](http://heroku.com/): A platform(PaaS) to deploy full stack web applications for free.
-   [Docker](https://www.docker.com/): A containerization platform that packages your application and its dependencies into a container for consistent and portable deployment.
-   [Kubernetes](https://kubernetes.io/): An open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications.

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
