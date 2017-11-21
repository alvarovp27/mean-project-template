# mean-project-template
This is a personal template for developing projects using the MEAN stack


## Introduction

## Dependencies
* 


## Project structure
The project structured is oriented to features. The root directory contains the basic js files for running the backend:
* server.js: It's the entry point to the application
* app.js: This file is responsible for configuring the Express application. Basically, we define the main path of the API as well as the frontend static route.
* db.js: The db.js file is intended to connect the application to the MongoDB database by using mongoose.
* config.yml: This is the config file of our web application. By this moment, it just contains the connection URI of MongoDB.

We have the following directories:
* public: contains the frontend of the application, developed with AngularJS v1

## Steps that I've followed for starting the project
# Backend
1. I ran the npm init command ```npm init```. I defined the server.js file as the entry point.
2. I installed the dependencies that I mentioned above by executing the command ```npm install <module_1> ... <module_n> --save```. It generated these lines in the packages.json:
```
  "dependencies": {
    "body-parser": "^1.18.2",
    "config-yml": "^0.8.0",
    "express": "^4.16.2",
    "helmet": "^3.9.0",
    "minimist": "^1.2.0",
    "mongodb": "^2.2.33",
    "mongoose": "^4.13.4",
    "path": "^0.12.7",
    "swagger-node-express": "^2.1.3"
  }
  ```
  
  
  # Frontend
  1. I ran the command ```npm install bower -g``` in order to install bower globally.
  2. I created the public directory in the root path of the project
  
