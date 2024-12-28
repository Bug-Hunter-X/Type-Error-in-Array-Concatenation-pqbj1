# Type Error in TypeScript Array Concatenation
This repository demonstrates a common TypeScript error: a type error that occurs when attempting to concatenate arrays of mismatched types.

## Bug Description
The `combine` function is designed to concatenate two arrays of numbers. However, an error arises when attempting to combine an array containing a string element.

## Reproduction
1. Clone this repository.
2. Compile the `bug.ts` file using a TypeScript compiler (tsc).
3. Observe the compiler error indicating type mismatch.

## Solution
The solution involves ensuring type consistency in the array inputs.  The corrected code is shown in `bugSolution.ts`.