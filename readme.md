# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To set this up on a new machine, first [Install Docker](https://docs.docker.com/desktop/install/windows-install/).

After installing Docker, make sure that this repository is cloned locally on your machine and then navigate to the directory.

After navigating to the directory run `docker-compose up`. This will start the container for the repository. After the setup is done navigate to [http://localhost:3000/api/ping](http://localhost:3000/api/ping). You should receive a response from the page.

Then navigate to [http://localhost:3001/register](http://localhost:3001/register) and create an account.
