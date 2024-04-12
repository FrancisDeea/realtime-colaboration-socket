# Realtime-colaboration-socket

Custom server built with Node and Express, to establish a bidirectional communication through websockets with the socket.io library.

This repository serves as a continuation of the main project: [movie-library-asafe](https://github.com/FrancisDeea/movie-library-asafe)

Developed by [Francisco Javier Bernal Cabra](https://www.linkedin.com/in/francis-bernal-full-stack-developer/)

## Tech Stack

**Server:** Node, Express, Morgan, Socket.io, @libsql/client (SQLite/Turso)

## Run Locally on dev mode

Clone the project

```bash
  git clone https://github.com/FrancisDeea/movie-library-asafe
```

Go to the project directory

```bash
  cd movie-library-asafe
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

## Environment Variables

You need to create a database in Turso (SQLITE) that works together with our server to store the chat messages. The variables you need are basically the authentication token and the database address.

You can find everything you need to [create the database here](https://docs.turso.tech/quickstart).

Add the following environment variables to your .env file

`DB_TOKEN`

`DATABASE_URL`

`CORS_ORIGIN`

Here you must set the public address of our deployed film project to allow cross-origin access (CORS).

## Deployment

This project has been deployed using the easy to use [render panel](https://docs.render.com/).
