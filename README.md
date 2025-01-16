# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow due to unbounded recursion. The `foo` function calculates the factorial of a number, but it doesn't handle negative input, leading to infinite recursion and a stack overflow.

The solution demonstrates how to add input validation to prevent this issue.

## Bug

The `bug.hack` file contains the erroneous code.

## Solution

The `bugSolution.hack` file provides a corrected version with input validation.