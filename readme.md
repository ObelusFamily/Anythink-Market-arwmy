# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

First, clone the respository into a directory on your computer. To setup the repository for the first time, you will need Docker. Once you have docker, run `docker -v` and `docker-compose -v` to make sure that everything was installed correctly.

Now, run `docker-compose up` in the root directory of the repository you cloned. Now, wait a few minutes and make sure that everything is running and no errors have occured. To test that everything is working, visit `http://localhost:3000/api/ping` to test the backend, and `http://localhost:3001/register` to test the frontend.

Ta-da! You have succesfully gotten Anythink to run on your system.
