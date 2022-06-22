# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1) Download and install docker from https://docs.docker.com/get-docker/

2) Verify docker installed by these cmd(or other terminals) commands:
    docker -v
    docker-compose -v

3)  run the docker from the project root directory by using the command:
    docker-compose up
    wait for couple of minutes for docker to finish setting up everything

4) check http://localhost:3000/api/ping for verify everything is running ok

5) open http://localhost:3001/register and create a new user
