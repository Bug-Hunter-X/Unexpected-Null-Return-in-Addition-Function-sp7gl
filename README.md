# Unexpected Null Return in Addition Function

This repository demonstrates a common error in JavaScript function handling of null values. The `foo` function adds two numbers; however, it returns `null` if either input is `null`.  This behavior might be unexpected.

The `bug.js` file contains the erroneous code. The `bugSolution.js` offers a corrected version.

## Bug
The original function immediately returns `null` if either `a` or `b` is `null`, preventing any addition.

## Solution
The solution handles `null` values by treating them as 0, ensuring that the addition proceeds correctly even if one of the inputs is `null`.

This illustrates the importance of carefully handling null values in JavaScript to avoid unexpected behavior.