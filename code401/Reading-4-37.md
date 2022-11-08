# Redux - Combined Reducers

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

1. Putting all of your logic in a single reducer makes it difficult to maintain; splitting it up allows you to organize related logic together.

2. The `combineReducers` function allows you to put multiple reducers into the same object.

3. The state object is not mudified in place; rather a copy is made, modified, and saved replacing the old state.

## [Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

1. >`combineReducers` is simply a utility function to simplify the most common use case when writing Redux reducers.

2. >`combineReducers` takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys.

3. `createStore` can either take an initial state as its second argument, or it can pull its initial state from the reducers that were combined.

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

1. Putting all of your logic in a single reducer makes it difficult to maintain; splitting it up allows you to organize related logic together.

2. >The `combineReducers` helper function turns an object whose values are different reducing functions into a single reducing function you can pass to `createStore`.

3. Naming reducers after the state slices they manage allows you to use property shorthand notation.
