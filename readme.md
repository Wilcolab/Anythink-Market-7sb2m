# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) git clone this repo
2) install [Docker](https://docs.docker.com/get-docker/) if you don't have already
3) cd into root of project dir
4) run `docker-compose up`
5) open http://localhost:3000/api/ping in a browser and you should see a pong
6) create a new user on http://localhost:3001/register

