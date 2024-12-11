# MongoDB $inc Operator Error

This repository demonstrates an incorrect usage of the `$inc` operator in MongoDB and provides a solution.

The bug arises from attempting to increment a field with a non-numeric value. The `$inc` operator requires a numeric value, not a string. This example showcases this error and its resolution.

## Bug
The file `bug.js` contains the incorrect MongoDB update operation.  It attempts to increment the `field` with the string 'abc'.

## Solution
The file `bugSolution.js` provides the correct update operation. It increments the `field` with a numeric value (1).