# User Management Application
In this project, we are going to create node CRUD application with express and mongodb, mvc.

#### To Run this project Clone it and install modules using
```
npm install
```

Then Create config.env file and create PORT and DB_STRING Variable and specify Value.
That's it. You are ready to go. To execute this project just type
```
npm start
```

## Project Structure
- **assets** folder contains the css files, images and JavaScript files in their respective sub folders
- **server** folder contains all server side code and imitates the *MVC* (Model-View-Controller) pattern to categorize each part of the codebase
  - controller folder deals with user requests for resources from the server
  - routes to handle different routes
  - services to handle different services
  - database to manage database connections
  - model folder will work with MongoDB data, perform data validation, processing data, creating Mongo schemes
- **views** contains the HTML files and using *EJS* (Embedded JavaScript) template engine, dynamic HTML pages are created and stored here

Enjoy...!
