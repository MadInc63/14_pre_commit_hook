# Quadratic Equations Solver

Programm finds roots of quadratic equation

# How to use

```Python
from quadratic_equation import get_roots
get_roots(1, 2, 3) # Finds roots of quadratic equation
```

For automatic tests before commits, you need to move `pre-commit` file into `.git/hooks` folder.

# Quickstart

When you try commit, test runs automatically

```Bash
$ git add quadratic_equation.py

$ git commit -m "test"
.E..
======================================================================
ERROR: test_returns_none_for_complex_solution (__main__.QuadraticEquationTestCase)
----------------------------------------------------------------------
Traceback (most recent call last):
  File "tests.py", line 22, in test_returns_none_for_complex_solution
    root1, root2 = get_roots(1, 2, 3)
  File "C:\devman\14_pre_commit_hook\quadratic_equation.py", line 6, in get_roots
    root1 = (-b - sqrt(discriminant)) / (2 * a)
ValueError: math domain error

----------------------------------------------------------------------
Ran 4 tests in 0.001s

FAILED (errors=1)
```
# Project Goals 

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
