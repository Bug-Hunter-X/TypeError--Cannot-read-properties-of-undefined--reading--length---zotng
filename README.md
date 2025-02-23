# Uncommon JavaScript Error: TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common yet easily overlooked JavaScript error: the `TypeError: Cannot read properties of undefined (reading 'length')`.  This occurs when attempting to access the `.length` property of a variable that is `undefined`.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides the corrected version.

## How to Reproduce the Bug
1. Clone this repository.
2. Run `bug.js` with an undefined value.

## Solution
The solution involves explicitly checking for `undefined` before accessing the `.length` property.  This is a crucial aspect of robust error handling in JavaScript.