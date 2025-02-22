# Incorrect Usage of $inc Operator in MongoDB
This example demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, providing a string value instead of a number will lead to unexpected behavior. The field will be replaced with the string value instead of being incremented. 

## Bug
The bug lies in the incorrect usage of the `$inc` operator. Instead of using the correct numeric value for incrementing, a string is used causing the field to be overwritten with the string.

## Solution
The solution is to provide the numerical value to the `$inc` operator so it increments the field properly.