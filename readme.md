# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install [Docker](https://docs.docker.com/get-docker/)
- Check if everthing is ok by running the following commands in your terminal:
```bash
docker -v 

docker compose version
```
- Then, run ```docker compose up``` from the project root directory to load Anythink's backend and frontend.
- Test your backend on http://localhost:3000/api/ping
- Check the frontend and make sure it's connect to the backend on http://localhost:3001/register
