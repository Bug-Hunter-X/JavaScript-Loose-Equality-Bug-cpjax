# JavaScript Loose Equality Bug

This repository demonstrates a common error in JavaScript related to loose equality (==) comparisons. Loose equality can lead to unexpected behavior when comparing values of different types.

## Bug Description
The `bug.js` file contains a function that uses loose equality. This can result in unexpected results, especially when handling null or undefined values.

## Solution
The `bugSolution.js` file demonstrates the correct approach using strict equality (===), which prevents the unexpected behavior.

## How to Reproduce
1. Clone the repository
2. Open `bug.js` and `bugSolution.js` in your preferred text editor or IDE
3. Run both files and compare their outputs.

## Lesson Learned
Always use strict equality (===) when comparing values in JavaScript to ensure type safety and avoid unexpected results. Loose equality (==) can lead to subtle and difficult-to-debug errors. 