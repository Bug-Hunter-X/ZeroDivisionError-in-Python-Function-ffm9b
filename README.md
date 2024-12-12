# ZeroDivisionError in Python Function

This repository demonstrates a common error in Python: the `ZeroDivisionError`. The error arises when attempting to divide by zero, which results in an exception.

## Bug Description
The `my_function` function attempts to handle the case where `x` is 0. However, the current implementation attempts a division by zero, triggering the exception.

## Bug Solution
The solution is to avoid the division by zero by explicitly checking for this condition before the division occurs.