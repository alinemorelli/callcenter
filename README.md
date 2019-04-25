# Call center

**Call center full stack challenge**

The "call center challenge" is an app developed to automate the registration and customer service integrated with [Teravoz API](https://developers.teravoz.com.br/).

## Technology
* [Node.js](https://nodejs.org/en/)
* [Postgresql](https://www.postgresql.org/)
* [React](https://reactjs.org/)

## Requirements
* [Docker](https://docs.docker.com/install/#server) **Linux only**
* [Docker Compose](https://docs.docker.com/compose/install/)

## Getting started

### Development
To start the development process is necessary to run the solution locally following the steps below:
* Clone the repository.

* Run `docker-compose up` to run the database and API
* The API services will be available at localhost:4000
* The web dashboad will be available at localhost:3000

Go to callcenter-api path using `cd callcenter-api`
* Run `yarn install` to install all the necessary dependecies.

**The first time running the project will be necessary run the migration and database seed**
* After run docker containers use `yarn docker:migrate` and `yarn docker:seed` inside callcenter-api directory

### Scripts

To run lint and tests go to each module directory




