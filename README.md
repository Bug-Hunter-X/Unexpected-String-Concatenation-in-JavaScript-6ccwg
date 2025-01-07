# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript error caused by the language's loose typing system.  The `foo` function is intended to add two numbers, but due to the implicit type coercion, it performs string concatenation when a number and a string are passed as arguments.

The `bug.js` file contains the erroneous code.  The solution, which uses type checking or explicit type conversion, is provided in `bugSolution.js`.