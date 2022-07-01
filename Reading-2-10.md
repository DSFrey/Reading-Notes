# Debugging

## What Went Wrong? Troubleshooting JavaScript

1. Syntax errors occur when there is a spelling or argument error that causes the code to stop working, either immediately or partway through execution. Logic errors occur when there are no issues with the syntax, but the code does not perform as you intended it to.

2. Syntax errors tend to be easy to fix, as there is an error message giving you a clue as to what might be wrong. For example, a few times I have accidentally declared a variable more than once. Logic errors can be more difficult. In the lab today, the sales data table was not updating when I tried to update an already existing record. I used console logs to track the flow of the code, which showed that it was executing in the path I was expecting. I also tried checking the value of variables throughout the process. This lead me to discover that the arrays were much longer than they should have been, indicating that the updated numbers were being added the end of the array instead of replacing it.

3. Troubleshooting is a constant daily activity when writing code, so having a robust toolbox of troubleshooting strategies will be a great benefit for my entire career.

## The JavaScript Debugger

1. The Javascript debugger allows you to check your code piece by piece to more easily locate problems.

2. Breakpoints are placed in set places to pause the execution of the code, giving a snapshot at that specific time.

3. The call stack shows the code that executed just before the breakpoint.
