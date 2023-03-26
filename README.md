<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Description

Projeto para avaliação.

## Installation

Make sure you have a local instance of the following services below and their respective credentials or changes in the environment (.env) file:

- MongoDB

- RabbitMQ

## Running the app

```bash

# install dependencies
$ npm install

# watch mode
$ npm run start:dev

```

## Test

```bash
# tests
$ npm run test

# test coverage
$ npm run test:cov
```

## Endpoints

- POST /api/users
<p align="left">
  <img src="https://i.ibb.co/xJMG5JX/create-user.png" width="500" /></a>
</p>

<p align="left">
  <img src="https://i.ibb.co/syd7YY5/create-user-mongo.png" width="500" /></a>
</p>

- GET /api/user/{userId}
<p align="left">
  <img src="https://i.ibb.co/J36849X/find-user.png" width="500" /></a>
</p>

- GET /api/user/{userId}/avatar

First Execution
<p align="left">
  <img src="https://i.ibb.co/74rW8Hp/find-avatar-by-user-first-execution.png" width="500" /></a>
</p>

Second Execution
<p align="left">
  <img src="https://i.ibb.co/ccDPCFr/find-avatar-by-user-second-execution.png" width="500" /></a>
</p>

open saved Base64
<p align="left">
  <img src="https://i.ibb.co/d0fcd55/teste-open-base64-image.png" width="500" /></a>
</p>

Mongo
<p align="left">
  <img src="https://i.ibb.co/Ybb7NR0/find-avatar-by-user-mongo.png" width="500" /></a>
</p>


- DELETE /api/user/{userId}/avatar

<p align="left">
  <img src="https://i.ibb.co/dm5D8gZ/delete-avatar-by-user.png" width="500" /></a>
</p>


<p align="left">
  <img src="https://i.ibb.co/q79S5YZ/delete-avatar-by-user-mongo.png" width="500" /></a>
</p>

- Coverage Files

<p align="left">
  <img src="https://i.ibb.co/PYZZH6h/coverage-files.png" width="500" /></a>
</p>

- RabbitMQ Messages

<p align="left">
  <img src="https://i.ibb.co/ZX4dGdJ/a.png" width="500" /></a>
</p>

- Mailtrap Mail

<p align="left">
  <img src="https://i.ibb.co/k34g4gy/mailtrap.png" width="500" /></a>
</p>


## Technologies

- Node.js
- Nest.js
- MongoDB
- RabbitMQ

## Support

- Author - Diego Mota Christ
- diego.christ@outlook.com
- t.me/diego_christ
