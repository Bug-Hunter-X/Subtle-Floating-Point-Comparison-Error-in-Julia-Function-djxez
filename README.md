# Subtle Floating-Point Comparison Error in Julia

This repository demonstrates a common, yet subtle, error in Julia code related to floating-point comparisons. The `bug.jl` file contains a function with a flawed conditional statement that can lead to unexpected behavior due to the limitations of floating-point precision.

The `bugSolution.jl` file provides a corrected version of the function, addressing the issue and improving the reliability of the code.

The issue highlights the importance of carefully considering how floating-point numbers are compared in Julia, particularly when checking for equality.