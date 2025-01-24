# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a base case for invalid input, leading to infinite recursion and a `RecursionError`. The `bug.py` file contains the erroneous code, while `bugSolution.py` provides a corrected version.

The issue arises when the factorial function is called with a negative integer. The recursive calls never reach a base case (n == 0), resulting in a stack overflow error. The solution adds input validation to prevent this error.