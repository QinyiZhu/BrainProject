# Brain Project

## Getting Started

This is the backend of the Brain Project. This application uses the Clarifai machine learning API to identify faces in photo URLs. Users can register, login, and keep track of how many submissions they have made. This app securely stores user information in a PostgreSQL database through strong encryptions and secure sessions.

## Prerequisite
1. Redis 
2. PostgreSQL server

## Installing

1. Clone this repo
2. Grab Clarifai API key [here](https://www.clarifai.com/), and add your own API key in the `controllers/image.js` file to connect to Clarifai API.
3. Let a redis server and a postgreSQL server running on your machine for this to work. Connect them in your server.js based on your own details.
4. Run `npm install`
5. Run `npm start`

## Built With
* [Node.js](https://nodejs.org/en/) - The backend server framework
* [Express.js](https://expressjs.com/) - Node.js web application framework
* [NPM](https://www.npmjs.com/) - Dependency Management
* [Redis](https://redis.io/) - Im-memory database used for Session on server
* [PostgreSQL](https://www.postgresql.org/) - SQL database for user information storage
* [JSON Web Token](https://jwt.io/) - HTTP Authorization standard
* [Bcrypt](https://www.npmjs.com/package/bcrypt) - A library to hash user password
* [Knex](http://knexjs.org/) - An SQL query builder in Node.JS 


