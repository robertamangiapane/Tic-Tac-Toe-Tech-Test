## Demo
`https://game-tic-tac-toe-react.herokuapp.com/`

## Project Setup

- Setup Jasmine:
  - npm init
  - npm install --save-dev jasmine
  - node node_modules/jasmine/bin/jasmine init
  - create SpecRunner.html  

- Setup Eslint:
  - npm install eslint  —save-dev
  - ./node_modules/.bin/eslint --init
  - ./node_modules/.bin/eslint yourfile.js (to run eslint)
  - npm install --save-dev eslint-plugin-jasmine
  - Add “plugins": ["jasmine"] to eslint json file
  - Add "jasmine": true to eslint json file
  - Add "extends": "plugin:jasmine/recommended"

- To create a React APP:
  - npx create-react-app my-app
  - cd my-app
  - yarn start

- Setup cypress:
  - yarn add cypress —dev
  - yarn run cypress open (to run the tests)

---------
## Development
User Stories:

- As a player X,/O so I can play TTT, I would like to see when is my turn
- As a player X/O, so I can play TTT, I would like to be able to see available fields
- As a player X/O, so I can play TTT, I would like to be able to claim a field
- As a player X/O, so I can play with another player, I would like to see that my turn is ended
- As a player X/O, so I can win, I should be able to claim all fields in a row, column or diagonal
- As a player X/O, so I know if I won or not, I would like to see a result of the game
- As a player X/O, so I can start a new game, I would like to know when the game is over

Class:
- Game(turns, board, players, result)
- Player(name)
- Board(rows and columns)

Game Methods:
- Start new game
- Check game over
- claim_field(index)

Player Methods:
- Input name

Board Methods:
- claim_field
- field_status

---------
## Makers Instructions

### Tic-Tac-Toe-Tech-Test

Try our Tic Tac Toe Tech Test!
This is a very common tech test as it demonstrates a candidate's knowledge of basic data structures.

### The brief
The rules of tic-tac-toe are as follows:

* There are two players in the game (X and O)
* Players take turns until the game is over
* A player can claim a field if it is not already taken
* A turn ends when a player claims a field
* A player wins if they claim all the fields in a row, column or diagonal
* A game is over if a player wins
* A game is over when all fields are taken
* Build the business logic for a game of tic tac toe. It should be easy to implement a working game of tic tac toe by combining your code with any user interface, whether web or command line.

---------

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
