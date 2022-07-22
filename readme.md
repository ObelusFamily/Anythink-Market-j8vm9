# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. clone this repo
2. ensure that you have docker desktop installed
3. cd into root directoy for this project 
4. run `docker-compose up`
5. test if successful by pointing your browser to `http://localhost:3000/api/ping`
    - response should be `{"msg":"Pong! Seems like Everythink is working, great job!"}`
