# MongoDB $inc operator with string value
This repository demonstrates an uncommon error when using the MongoDB `$inc` operator with an incorrect data type.
The `$inc` operator is used to increment a numeric field by a specified value.  However, if a string is provided, MongoDB will not correctly perform the increment.
The `bug.js` file shows the erroneous code, while `bugSolution.js` contains the corrected implementation. 