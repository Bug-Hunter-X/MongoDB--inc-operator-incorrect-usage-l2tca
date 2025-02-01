# MongoDB $inc Operator Incorrect Usage
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a given value. However, if the value is not an integer, the update may not behave as expected.

## Bug
The bug lies in the incorrect usage of the `$inc` operator. Instead of specifying an integer value to increment the field by, a string is used. This leads to unexpected results. 

## Solution
The solution involves ensuring that the value provided to the `$inc` operator is an integer. This will ensure that the field is correctly incremented.