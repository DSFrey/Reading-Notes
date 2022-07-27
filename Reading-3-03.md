# Passing Functions as Props

## React Docs - lists and keys

1. `.map` returns an array with the same length as the input array.

2. `const outputElements = inputArray.map((value) => <outputValue />)`

3. Each list item needs a unique key.

4. >Keys help React identify which items have changed, are added, or are removed. — reactjs.org

## The Spread Operator

1. >“When ...arr is used in the function call, it ‘expands’ an iterable object arr into the list of arguments.” — JavaScript.info

2. The spread operator can be used to

    1. Copy an array

    2. Use the items in an array as arguments

    3. Concatenate arrays

    4. Combine objects

3. `const newArray = [...[arrayOne], ...[arrayTwo]]`

4. `const newArray = [newItem, ...[array]]`

5. `const newObject = {...{obectOne}, ...{objectTwo}}`

## How to Pass Functions Between Components

1. The first step is creating the function inside the parent component.

2. It loops through the people array to find the right name and increments that person's count by one.

3. A method can be passed as a prop from a parent to child component.

4. Call a parent method by using `this.props.functionName`.