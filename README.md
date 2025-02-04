# Unexpected NaN Handling in JavaScript Comparison

This repository demonstrates a common JavaScript bug stemming from the loose comparison operator (==) and its interaction with NaN (Not a Number).

## The Bug
The `foo` function aims to categorize input numbers (null, negative, or positive).  However, its use of loose comparison causes unexpected behavior when NaN is passed in.  NaN is not equal to itself using loose or strict equality, leading to incorrect classification.

## The Solution
The solution employs strict equality (===) to correctly handle NaN and provides a more robust categorization of inputs.

## How to Run
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in a browser's developer console or a JavaScript environment (Node.js).
3. Execute the functions and observe the difference in output for various inputs, including NaN.
