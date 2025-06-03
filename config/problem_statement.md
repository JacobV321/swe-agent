 Problem Statement

 Context

The file `tests/missing_colon.py` contains a function definition and a call to `division(23, 0)`.

 Problem

When running the script, the following error appears:

  File "tests/missing_colon.py", line 4
    def division(a: float, b: float) -> float
                                             ^
SyntaxError: invalid syntax


This indicates a syntax error in the function definition, most likely due to a missing colon (`:`) at the end of the line.

 Objective

Fix the syntax error in the `tests/missing_colon.py` file so that the script runs correctly and the function `division` is defined properly.

 Suggested Fix

Add the missing colon at the end of the function definition line in `tests/missing_colon.py`.
