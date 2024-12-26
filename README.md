# TypeScript Type Error: Argument of type string[] is not assignable to parameter of type string
This example demonstrates a common TypeScript error: passing an array of strings to a function expecting a single string.  The error occurs because the function's parameter is explicitly typed as `string`, while the argument passed is an array (`string[]`).

The solution involves modifying either the function signature or the way the argument is handled to ensure type compatibility.