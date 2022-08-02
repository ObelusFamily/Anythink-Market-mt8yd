# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1) Clone the repository on your machine
2) Install Docker (https://docs.docker.com/get-docker/)
3) To verify that Docker has been installed, run these commands on your terminal: `docker -v` and `docker-compose -v`
4) Then run `docker-compose up` from project root directory to load Anythink's frontend and backend.
5) Go to http://localhost:3000/api/ping to verify that backend is working 
6) Next, head over to http://localhost:3001/register and create a new user. If you're able to do this, it verifies that the frontend is connected to the backend.
