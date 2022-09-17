# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
1. Install [Docker](https://docs.docker.com/get-docker/).
2. Verify installation with `docker -v` and `docker-compose -v`.
3. Run `docker-compose up` from the project root directory to load frontend and backend.
4. Visit http://localhost:3000/api/ping from the browser to verify backend is live.
5. Visit http://localhost:3001/register to from the browser to verify frontend is live.
6. Use `docker exec` to run commands in the running containers.
