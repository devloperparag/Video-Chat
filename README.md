# Realtime Video Chat Application

### Prerequisites
You need to have [Node.js and npm](https://nodejs.org/en/)
- Support Node v4 - latest
- Support npm v3 - latest

## Introduction
In this application, we're going to build and deploy a React Video Chat Application using WebRTC.

## Development Server:
- run ```npm i && npm start```.
- go to inside client folder and run ```npm i && npm start``` to start react client.
- browse `http://localhost:3000/` on two diffrent browser to make video calls.

## Application Structure
- Server is written in index.js file which is using nodejs socketio module.
- React frontend is written in client folder using react and WebRTC.

## Build
- run ```npm build```.
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
