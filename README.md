# MongoDB $inc Operator Error
This example demonstrates an error that can occur when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is used to increment or decrement a numerical value in a document. However, if the value provided to the `$inc` operator is a string instead of a number, it will lead to an error.

## Bug Description
The `$inc` operator in the following code is given a string value ("1") instead of a number (1). This will cause the update to fail with an error.

## Bug Solution
The solution is to provide a numerical value to the `$inc` operator.  The updated code uses the number 1 instead of the string "1".