# Expressions and Operators and Loops, Oh My

## Operators

Javascript contains several categories of operator, including Assignment, Comparison, Arithmetic, Bitwise, Logical, String, Conditional (ternary), Comma, Unary, and Relational. Most operators are binary, requiring two operands.

Assignment operators take a variable, do math to it, and make the resulting value the new value of the variable. Chains of assignment operators on a single line should be avoided.

Comparison operators take to variables, determine a certain relationship between them, then return a boolean output.

## Loops

### For Loops

A `for` loop is structured as follows:

    for ([initialExpression]; [conditionExpression]; [incrementExpression]) 
        statement;

It executes in the following order:

1. Execute the `initialExpression`.
2. Check the `conditionExpression`. If false, leave the loop.
3. Execute the `statement`. If there are multiple statements, use a `{block statement}` to execute them all.
4. Execute `incrementExpression`.
5. Repeat back to step 2.

### While Loops

A `while` loop is structured as follows:

    while (conditionExpression) 
        statement;

It executes in the following order:

1. Check the `conditionExpression`. If false, leave the loop.
2. Execute the `statement`. If there are multiple statements, use a `{block statement}` to execute them all.
3. Repeat back to step 1.
