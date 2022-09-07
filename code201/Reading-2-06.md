# Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. > An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects). - [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

2. It can be more efficient to send all data in a single object than in several pieces. Also, it can be much easier to refer to data points by a name instead of keeping track of indexes in a heterogenous data set.

3. Objects store data using a string as an index instead of a number.

4. Bracket notation is needed if you want to add a property to an object using a name that is stored in a variable.

5. `this` refers to the oject the code is being written inside, in this case `dog`. Using `this` means you can reuse code in multiple objects, allowing the use of constructors to automatically build objects from a single definition.

## Introduction To The DOM

1. The DOM is the computer's internal representation of a web page, allowing programming languages to interact with it.

2. The DOM is an application programming interface, designed to be independent of any particular programming language, but making the socument structure available to any language interacting with it (almost always javascript in web applications).
