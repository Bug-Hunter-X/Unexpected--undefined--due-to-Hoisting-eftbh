# Unexpected 'undefined' due to Hoisting in JavaScript

This repository demonstrates a common JavaScript error related to hoisting.  The code in `bug.js` shows a function where a variable is used before it's declared, resulting in an unexpected `undefined` value being logged to the console.

The solution in `bugSolution.js` addresses this by ensuring that variables are declared and assigned before being used, eliminating the unexpected behavior.