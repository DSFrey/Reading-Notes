# Javascript 2: The Scriptening

## Control Flow

The computer runs code in order from the first line to the last line unless otherwise told by structures that change this flow. These structures can include conditionals (`if` and `else`), loops, and functions.

## Functions

A function is a block of code that executes its designed task when it is called. This can happen automatically, when it is called by other code, or when an event occurs (such as clicking a button). Functions are created by the following:

    function name(inputparameter) {
        code to be executed
    }

Variables defined within a function can only be used by the function and are deleted when the function has functioned completely.

When JavaScript reaches a return statement, the function will stop executing and return to where the code was executing before. If an argument is added to the return line, it can give that value as an output to whatever called the function.

## Operators

### Arithmetic Operators

|Operator|Description|
|---|---|
|+|Addition|
|-|Subtraction|
|*|Multiplication|
|**|Exponentiation|
|/|Division|
|%|Modulus|
|++|Increment|
|--|Decrement|

You can operate and assign a new value to the variable by adding an equals to the operator, e.g. `a += b` is adding a and b and then assigning the new value to a. The operator `+` can be also used to join strings together; when a number and a string are added, the output is also a string.

### Comparison Operators

|Operator|Description|
|---|---|
|==|equal to|
|===|equal value and equal type|
|!=|not equal|
|!==|not equal value or not equal type|
|>|greater than|
|<|less than|
|>=|greater than or equal to|
|<=|less than or equal to|
|?|ternary operator|

### Type Operators

|Operator|Description|
|---|---|
|typeof|Returns the type of a variable|
|instanceof|Returns true if an object is an instance of an object type|

### Logical Operators

|Operator|Description|
|---|---|
|&&|logical and|
|\|\||logical or|
|!|logical not|

### Bitwise Operators

|Operator|Description|
|---|---|
|&|AND|
|\||OR|
|~|NOT|
|^|XOR|
|<<|left shift|
|>>|right shift|
|>>>|unsigned right shift|
