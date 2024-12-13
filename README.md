# Unhandled Modulo Operator in Calculator Function

This repository demonstrates a common yet easily overlooked error in JavaScript: the improper handling of modulo operators within a switch statement. 

The `operate` function is designed to perform basic arithmetic operations (+, -, *, /). However, it lacks the case for the modulo operator (`%`). This omission leads to an 'Invalid operator' error when attempting to perform modulo operations.

The solution provides a corrected version of the `operate` function that includes a case to handle modulo operations properly.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory in your terminal.
3. Run `node bug.js`. Observe the error.
4. Run `node bugSolution.js`. Observe the correct output.