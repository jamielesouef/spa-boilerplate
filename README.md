# Single Page App Boilerplate

My attempt at creating a fancy boilerplate thing, which I can reuse to get new projects started quickly.

WARNING: This has all sorts of bells and whistles that not every project will need. You should only attempt to use this boilerplate project if you understand what all of the features listed below are, to the point where you can:

1. judge whether or not you need them;
2. rip out what you don't need.

## Cool JS stuff:
  * React
  * Redux
  * ES6
  * Webpack
  * Babel
  * Hot Module Reloading (see below)
  * Source maps
  * eslint
  * Flow
  * seamless-immutable

## Still TODO:
  * Jasmine + karma + phantomJS
  * redux-thunk? redux-saga?

## Other TODO:
  * Remove dependency on estraverse. See:
    * https://github.com/babel/babel-eslint/issues/267
    * https://github.com/eslint/eslint/issues/5476
  * Add @flow to configureStore. Potentially waiting on: https://github.com/babel/eslint-plugin-babel/issues/55

### On HMR
  * HMR for components works normally.
  * HMR for reducers requires this Chrome plugin:
    https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd
