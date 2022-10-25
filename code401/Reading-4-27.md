# `useState()` Hook

## [Introducing Hooks](https://reactjs.org/docs/hooks-intro.html#motivation)

1. Hooks were introduced to simplify code reuse and organization.

2. Hooks allow you to use more of React's features without classes, which in turn allows for better optimization.

3. >Hooks allow you to reuse stateful logic without changing your component hierarchy.

## [hooks api](https://reactjs.org/docs/hooks-overview.html)

1. Rules of hooks:

    1. >Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.

    2. >Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.

2. Custom hooks are useful for reusing stateful logic without having to refigure your component tree to allow for a higer order component. By convention, their name starts with a `use` and their logic calls other hooks.

## [the state hook](https://reactjs.org/docs/hooks-state.html)

1. > A Hook is a special function that lets you “hook into” React features.

2. You can use the `useState` anytime you need to use React's state functionality outside a class.

3. Adding React state:

    1. Calling `useState` declares a state variable that persists across function calls.

    2. `useState` gets passed the initial value of state as an argument.

    3. `useState` returns a pair of values: the current state and a function to change that state.
