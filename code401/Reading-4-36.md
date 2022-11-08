# Application State with Redux

## [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

1. The state of the whole application is contained within a single javascript object.

2. Store is the single source of truth for a redux app; it contains the state and uses reducers to create the new state.

3. Three important methods:

    1. `getState()` returns the current state of the store.

    2. `dispatch()` lets you perform an action to update state from elsewhere in the application.

    3. `subscribe()` lets a component treat the store as state, rerendering when it is updated.

4. `combineReducers()` assembles all of your application's reducers into a single object, allowing you to use a single reducer for all necessary actions throughout your tree.
