# MongoDB $inc Operator Error

This repository demonstrates an error that can occur when using MongoDB's `$inc` operator with an invalid data type. The `$inc` operator is designed to increment a numerical value in a document. Attempting to increment with a non-numeric value (like a string) will result in an error or unexpected behavior.

## Bug Description
The bug showcases the incorrect usage of the `$inc` operator by attempting to increment a field with a string value. This will result in an error in MongoDB.

## Bug Solution
The solution corrects the invalid data type provided to `$inc`. The value used for incrementing is changed from a string to an integer, ensuring a successful update operation.