# Redux - Asynchronous Actions

## [async actions](https://redux.js.org/advanced/asyncactions)

1. Because Redux reducers must be pure functions, they do not deal well with async functions. Middleware allows us to write functions that have side effects.

2. When an action is performed, the event handler triggers a dispatch. Before the dispatch reaches Redux's processing, the middleware checks to see if it is a function. If so, it executes (e.g. making an api request). Only when that async function is completed is the dispatch sent to Redux, at which point it acts normally, goint through the reducer, modifying state, and rerendering the page with the new information.

3. We will be using Redux Thunk.

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

1. thunk allows you to write functions that interact with redux's `dispatch` and `getState` methods, allowing for building async functions that can cooperate with redux.

2. thunk allows you to return a function instead of an action object.

3. dispatch is passed into the function as an argument, meaning anything inside the function can be sent to dispatch from there.
