# tiny-npm-deploy

This project is a simple Express.js server written in TypeScript.

## How it works

The server is started by running the `index.ts` file. This file does the following:

1. Imports the Express.js module.
2. Creates an instance of an Express.js application.
3. Sets up a route handler for GET requests made to the root URL (`/`). When a GET request is made to the root URL, the server responds with "Hello World".
4. Starts the server on port 3005 and logs a message to the console when the server starts.

## Running the server

To start the server, run the following command:

```bash
npm start
