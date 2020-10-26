# JS Meltdown Game Refactor

Back in 2015, I wrote a javasript web game with a few other folks at Hack Reactor. I think it was a pretty fun idea for a game and I've always wanted to refactor it into React and a more modern setup. 

This repo has both the 

## Local development

### Server
1. `cd server`
1. run `nvm use`
1. run `npm i && npm start`
1. The server is running on port 8080

### Client
1. `cd client`
1. run `nvm use`
1. run `npm i && npm start`
1. The client app is running on port 3000 (this is just the default create-react-app port)

_note: all requests from the client will be proxied to the server via a proxy line in the package.json_
_the proxy setup tip was from this site https://flaviocopes.com/how-to-serve-react-from-same-origin/_ 

## Goals:

1. Refactor meltdown game using React
2. Setup react + node project from scratch
3. Use new firebase API

### Reasons:

1. Find out how does Phaser.js interact with React
   i. Renders fast?
1. Angualr 1 is dead

#### Tasks:

1. setup initial joining room - simple button click for now
   a. room name
   b. guest name
