# Putting it all together

## Thinking in React

1. Each component should do only one thing; this helps design be more consistent as a good map will have UI and data structures have the same architecture.

2. Build the UI before building any of the interactivity, sort of like wireframing with code.

3. Figure out the minimal complete representation of your state.

4. Three questions you can ask to determine if something is state:

    >1. Is it passed in from a parent via props? If so, it probably isn’t state.
    >2. Does it remain unchanged over time? If so, it probably isn’t state.
    >3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. Take all of the components that uses that state and find (or create) their common ancestor.

## Higher-Order Functions

1. >Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

2. It returns a new function with n set by the current function and m as a parameter for the new function.

3. The reduce method takes in an array and a function. It uses the function to operate on the first two items in the array, then takes that result and uses the function to operate on it and the next item and so forth until there are no more items and a single result remains.