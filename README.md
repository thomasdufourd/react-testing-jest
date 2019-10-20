The code comes from [this tutorial](https://www.robinwieruch.de/react-testing-jest) 

The app was bootstrapped with [Create React App](https://github.com/facebook/create-react-app)

## Install dependencies
`npm install`

## How it works
The test runner gets the tests to run from the config located in `jest.config.json`

Tests are located in `src/App.spec.js`

Snapshots are saved here: `src/__snapshots__`


### run the app
`npm start`

### run the tests
`npm test`

### Notes
Stuffs that has been installed (don't need to run those commands)
`npm install --save-dev jest`

In `package.json` at `scripts`: don't use `"test": "jest"` but `"test": "react-scripts test"`
