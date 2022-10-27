# Advanced State with Reducers

## [useReducer hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

1. ^

2. >`useReducer` is usually preferable to `useState` when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. `useReducer` also lets you optimize performance for components that trigger deep updates because you can pass `dispatch` down instead of callbacks.

3. Initial state can be set directly with the second argument of `useReducer`; alternatively, if a third argument is given, the second argument is passed through the callback in the third argument and the return is the initial value.

## [Ultimate Guide to useReducer](https://blog.logrocket.com/guide-to-react-usereducer-hook/)

1. `useReducer` accepts a reducer function and an initial state as parameters

2. It returns an array containing the current state at [0] and a dispatch function at [1].

3. A `dispatch` function accepts an object that tells it what kind of action it should use to update the state.
