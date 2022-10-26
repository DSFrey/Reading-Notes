# Component Lifecycle / useEffect Hook

## [effects hook](https://reactjs.org/docs/hooks-effect.html)

1. `useEffect` combines the functionality that `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` take care of in class components.

2. When using the `useEffect` hook:

    1. `useEffect` tells React to do something after a render.

    2. Putting `useEffect` inside the component means it can easily access state and props.

    3. `useEffect` runs after *every* render.

3. Cleaning up effects is important so that you don't introduce memory leaks.
