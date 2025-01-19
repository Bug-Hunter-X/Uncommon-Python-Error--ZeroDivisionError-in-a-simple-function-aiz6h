# Uncommon Python Error: ZeroDivisionError
This repository demonstrates a less frequently encountered error in Python: the ZeroDivisionError.  While type errors and similar issues are often addressed explicitly in code, the ZeroDivisionError can still slip through, particularly in functions with numerical inputs.  The example showcases a simple function where a division by zero occurs only under a specific condition (a == 0).  The solution provides a practical way to handle this type of error gracefully, preventing abrupt program crashes. 

## Bug Description
The `bug.py` file contains a Python function that can potentially raise a ZeroDivisionError if the input 'a' is equal to zero.  This occurs because the code attempts to divide 'b' by 'a' without first checking whether 'a' is zero. 

## Solution
The `bugSolution.py` file shows the improved version of the function.  It explicitly checks if 'a' is zero before performing the division.  If 'a' is zero, a more informative message is returned, preventing the exception from being thrown, thus enhancing the robustness and user-friendliness of the application.