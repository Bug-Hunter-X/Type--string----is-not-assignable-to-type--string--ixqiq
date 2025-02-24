# Type 'string[]' is not assignable to type 'string'
This repository demonstrates a common TypeScript error: attempting to pass an array of strings to a function that expects a single string.

## The Bug
The `greeter` function is defined to accept a single string argument. However, the `user` variable is an array of strings.  Attempting to pass `user` to `greeter` results in a type error.

## The Solution
The solution involves either modifying the `greeter` function to accept an array of strings or modifying the way the `user` variable is used.