# Google Docs Clone

## Authors

- [@JosipHowler](https://github.com/JosipHowler)

## Run Locally

Clone the project

```bash
  git clone https://github.com/JosipHowler/google-docs-clone.git
```

Go to the project directory

```bash
  cd google-docs-clone/client
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm start
```
Can also open the client folder on github to follow the React README

Open new terminal and go to the server directory

```bash
  cd google-docs-clone/server
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run devStart
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`MONGODB_URI`

https://mongoosejs.com/docs/connections.html - follow the documentation to get the MONGODB_URI in order to connect with mongoose in server.js

## Tech Stack

**Client:** React, React Router, Socket.io, uid, quill

**Server:** Node, Nodemon, dotenv, mongoose, scoket.io

## Features

- Document loading
- Creating new document
- Document editing
- Editing the document with other people in real time
