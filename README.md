# Tcl Bug: Potential Division-by-Zero Error
This repository demonstrates a potential division-by-zero error in a simple Tcl procedure. The bug is explained in detail and a solution is provided. 

## Bug Description
The `badproc` procedure in `bug.tcl` fails to handle the case where the first argument (`a`) is 0, resulting in a division-by-zero error when called with `a` equal to 0.

## Solution
The solution in `bugSolution.tcl` demonstrates how to properly handle this case using an `if` statement to check if `a` is 0 before performing the division. If `a` is 0, the procedure returns an appropriate error message or value instead of causing an error.