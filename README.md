# MongoDB $inc Operator with String Value
This example demonstrates an incorrect usage of the $inc operator in MongoDB. The $inc operator is used to increment a numerical field by a specified value, but in this case, it is incorrectly used with a string value. This will lead to unexpected behavior or errors.

## Bug
The bug lies in the `updateOne` operation, where the `$inc` operator is used to increment the `field` by the string value 'abc'. This is incorrect and will result in an error or unexpected data modification.

## Solution
The solution is to use the correct numerical value when using the $inc operator to increment a numerical field.