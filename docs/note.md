# Learning End-to-End Testing with Jest

## Project Setup: Recipe App

#### Jest Setup

> npm install --save-dev jest supertest

> npm install -D cross-env

```js
{
  "scripts": {
    "test": "cross-env DATABASE_URI=mongodb://localhost:2707/recipe_app_test jest --collectCoverge --forceExit --detectOpenHandles"
  },
  "jest": {
    "testEnvironment": "node"
  },
  "devDependencies": {
    "cross-env": "^7.0.3",
    "jest": "^30.0.0",
    "supertest": "^7.1.1"
  }
}
```

