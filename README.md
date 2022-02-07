# About:-
This is a API based sample project where we tried to define the basic architecture for a NodeJs + MongoDB project. It also includes JWT authentication for the api's as well.

# Prequisites:-
Node

NPM

MONGODB

# Installation:-
After you clone this project, do the following:

##### create a .env file
```cp .env-example .env```

##### install npm dependencies
```npm install```

##### update the following configurations in your .env file as per your requirements
```
dbName = ''
port = ''
```

##### create uploads and compiled folder in the backend
```
mkdir uploads
mkdir compiled
```

##### start backend server and watch for changes
```nodemon app.js```