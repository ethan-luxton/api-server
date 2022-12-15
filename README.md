# LAB - Class 04

## Project: Express API Server and Testing

### Author: Ethan Luxton

### Problem Domain

Build a REST API using Express, by creating a proper series of endpoints that perform CRUD operations on a **Postgres SQL Database**, using the REST standard

### Links and Resources

[ci/cd](https://github.com/ethan-luxton/api-server/actions/workflows/node.js.yml) (GitHub Actions)
[Main Deployment - Backend](https://api-server-k0de.onrender.com/food)

### Setup

#### .env requirements

-   PORT: 3001
-   DATABASE_URL=postgres://localhost:5432/postgres (Local variable)

#### How to initialize/run your application

npm start

#### Features / Routes

-   Feature One: Use of all CRUD operations, Postgresql14 database.
    GET : /food OR clothes - Gets all food OR clothes items
    GET : /food OR clothes/id - Gets one food OR clothes item.
    POST : /food OR clothes (with a JSON body request) - Creates a new food OR clothes item.
    PUT : /food OR clothes/id - (with a JSON body request and specific ID) - Updates an existing food OR clothes item.
    DELETE : /food OR clothes/id - (with a specific ID) - Deletes an existing food OR clothes item.
-   Feature Two: Testing
-   Feature Three: Deploy to Dev
-   Feature Four: Deploy to main

#### Tests

-   How do you run tests?
    -   npm test
-   Any tests of note?
    -   404 on a bad route
    -   404 on a bad method
    -   Tests for: GET, POST, PUT and DELETE

### UML

![UML](https://i.imgur.com/UoQyuin.png)