# Floating-Point Comparison Inaccuracies in Julia

This repository demonstrates a common yet subtle issue in Julia: inaccuracies in floating-point comparisons.  The example highlights how seemingly straightforward conditional logic involving floating-point numbers can produce unexpected behavior due to small rounding errors.

The `bug.jl` file shows the original code with the problematic comparison.  The `bugSolution.jl` file provides a corrected version using a tolerance-based approach to handle potential inaccuracies.

This issue is relevant to anyone working with numerical computations in Julia, and it emphasizes the importance of careful consideration of floating-point precision.