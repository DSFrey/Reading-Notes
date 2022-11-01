# Context API - Behaviors

## [Hooks and Context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

1. A provider is responsible for displaying its local state and making and providing a way to manage it from anywhere.

2. Create a custom hook that to wrap the `useContext` hook.

3. All of out content is inside the provider wrapper, so it as access to the context it is providing.

## [Awesome React Context links](https://github.com/diegohaz/awesome-react-context)

1. react-broadcast is a library that interacts with class-based components that make use of `shouldComponentUpdate` to optimize for performance. It takes advantage of context to pass state through/around components that should not update to components that should.

2. constate is a library that can be used to easily let your curstom hooks be accessed from te application's context.
