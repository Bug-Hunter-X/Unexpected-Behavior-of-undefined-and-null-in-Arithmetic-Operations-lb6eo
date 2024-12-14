# Unexpected Behavior of undefined and null in Arithmetic Operations

This code demonstrates the unexpected behavior of adding `undefined` and `null` to numbers in JavaScript.  Adding `undefined` results in `NaN`, while adding `null` results in the number itself. This can lead to subtle bugs if not accounted for.

## Bug

The `foo` function adds two numbers. However, if one of the arguments is `undefined` or `null`, the result is unexpected.

## Solution

The solution involves explicitly checking for `undefined` and `null` values and handling them appropriately, perhaps by assigning a default value or throwing an error.