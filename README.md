# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The error occurs when attempting to increment a numeric field with a non-numeric value.

## Bug
The `bug.js` file contains code that attempts to increment the `age` field by the string value '1'. This will result in an error because the `$inc` operator expects a numeric value.

## Solution
The `bugSolution.js` file provides the corrected code.  The string value '1' is converted to a number before using it with `$inc`, resolving the error and correctly incrementing the `age` field.
