# Unexpected setTimeout Behavior in Loop

This repository demonstrates a common JavaScript closure issue related to the use of `setTimeout` within a loop.  The expected behavior is to print numbers 0-9 sequentially after each second. However, due to the nature of closures and how `setTimeout` handles its callback function, the code produces unexpected results.  The solution provides a fix using an immediately invoked function expression (IIFE) to maintain the correct value of `i` for each iteration.

## How to run

1. Clone the repository
2. Open `bug.js` to see the erroneous code.
3. Open `bugSolution.js` to see the corrected code.
4. Run the files in a JavaScript environment (e.g., Node.js, browser's console).