To run:

1. run `npm install`
2. `cd public/`
3. `npx webpack` --> this will build an app.js file in /public
4. `cd ../`
5. run `npm start`
6. go to localhost:8000

#### Less than ideal things about current local dev setup

- webpack config should be global, not in `/public`
- build output should go to a `/build` folder
- should have hot reloading with webpack & node

# Goals:

1. Refactor meltdown game using React
2. Setup react + node project from scratch
3. Use new firebase API

## Reasons:

1. All packages (nmp and bower) are way out of date
2. Find out how does Phaser.js interact with React
   i. Renders fast?
3. Angualr 1 is dead

### Tasks:

1. Hot reloading with weback middleware in node
1. setup initial joining room - simple button click for now
   a. room name
   b. guest name
