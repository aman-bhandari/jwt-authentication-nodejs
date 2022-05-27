# jwt-authentication-nodejs

# Simple JWT in Node
Simple JWT in Node.js

## Usage
Project Setup In order to run the project, setup .env and set MONGO_URI variable equal to DB connection string.

In order to avoid port collisions, in the source code port value is 3000

## Route API

| **HTTP Method**  | **Route**  | **Result**  |
| :------------: | :------------: | :------------: |
|  POST |  api/v1/login |  Create a new user and JWT |
|  GET |  api/v1/dashboard |  Use token to see lucky number |
