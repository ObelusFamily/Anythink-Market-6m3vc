# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* first clone the repo
* install *docker* and *docker-compose*
* change to the root directory of the project and execute **docker-compose up**
* the backend is accessable on port 3000 (e.g. http://localhost:3000/api/ping)
* the frontend is accessable on port 3001 (http://localhost:3000)
