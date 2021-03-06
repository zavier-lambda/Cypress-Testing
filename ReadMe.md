# Quotes

## Running this project

This project is set up with [Parcel Bundler](https://parceljs.org/), an npm package
that compiles our frontend assets and comes with an integrated development server.

The dev server for the React page runs on port `1234` by default, but will use another if `1234` is
being used by another application.

The quotes API runs on port `3333` and this port needs to be free, or the server won't be able to start.

- Clone the repo.
- Navigate into the project folder.
- Run `npm i` to download the project's dependencies listed in the `package.json`.
- Run `npm run server` to spin up the quotes API on `http://localhost:3333/api/quotes`.
- Run `npm start` to compile the React project and spin up the app on `http://localhost:1234`.
- Run `npm test` to run tests using Cypress.
- A window will appear with a list of example tests. Scroll down to the bottom and click on `form_tests.js` to run.
