# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

### Clone a Local Version

Before running this repo, please fork and clone this repo. The easiest way to fork this repo is by clicking 'Fork' on the Github page.

When finished, browse to your version, select the green 'Code' button. On the 'Local' tab, copy the HTTPS url.

Back in your local terminal, use `git clone [HTTPS URL]`, being sure to paste the URL. Use `cd` to enter the repo.

### Start Docker

Check to be sure Docker is loaded onto your device by running `docker -v` in the terminal. If it is, continue. If not, browse to [Docker's install page](https://docs.docker.com/get-docker/) to download the latest edition of Docker for your machine.

Once you are in the root directory of this repo, run the command `docker-compose up` to begin load Anythink's front- and back-end.

You can verify Docker is working correctly by browsing to our [API backend](http://localhost:3000/api/ping) as well as our [frontend sign-up](http://localhost:3001/register).
