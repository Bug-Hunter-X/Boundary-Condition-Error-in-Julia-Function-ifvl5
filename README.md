# Julia Bug: Boundary Condition Handling

This repository demonstrates a common error in Julia: incorrect handling of boundary conditions in conditional statements. The `my_function` function is designed to return x^2 if x is greater than or equal to 10 and x+1 otherwise. However, the original implementation has a bug where 10 is not handled correctly.

The `bug.jl` file contains the buggy code, and the `bugSolution.jl` file provides a corrected version.
