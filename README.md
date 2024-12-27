# Unexpected Type Coercion in JavaScript Addition
This example demonstrates a common error in JavaScript related to type coercion during addition. When adding a number and a string, the + operator performs string concatenation instead of numerical addition.

## Bug Description
The function `myFunction` attempts to add a number and a string.  Instead of performing numerical addition, JavaScript converts the number to a string and concatenates the two values, leading to an unexpected result.

## Solution
To fix this, explicitly convert the string to a number using `parseInt()` or `parseFloat()` before performing the addition.