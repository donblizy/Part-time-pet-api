# Northcoders Final Project API

## Part-Time Pet API :dog: :rabbit: :cat:

## [Front-end Repo](https://github.com/donblizy/nc_project)

## Project Description

Part-Time Pet API is the middleware created to handle all queries to the database.
Part-Time Pet uses Firebase as a database, however, this API is handling ALL the requests to firebase and to a separate geolocation API except authentication which is handled through front-end exclusively.

This allowed front-end to have fewer responsibilities as data is handled here and served to the front-end in a desired format.

## Available endpoints:

- GET /api/users
- GET /api/users/:userid
- GET /api/pets/:petId
- GET /api/users/:userId/pets
- GET /api/users/:userId/reviews
- POST /api/users
- POST /api/users/:userId/pets
- POST /api/users/:userId/reviews
- PATCH /api/users/:userid
- PATCH /api/pets
- PATCH /api/pets/:petId
- DELETE /api/users/:userid
- DELETE /api/users/:userId/reviews
- DELETE /api/pets/:petId

## Testing

This API was built using Test Driven Development (TDD). Extensive testing has been conducted using [Mocha](https://mochajs.org/) and [Chai](https://www.chaijs.com/).

## Rest of Tech Stack

[Google Firebase ](https://firebase.google.com/) <br>

[Express](https://expressjs.com/)

### Things to note:

This repo is not intended to be cloned and used. It is part of Part-Time pet app and specific files that link this repo to our firebase database cannot be shared for security reasons. Tests also use data in a separate firebase database that gets reseeded on each test run.
