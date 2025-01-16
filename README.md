# Haskell Runtime Error: Uninitialized Variable

This repository demonstrates a common runtime error in Haskell caused by using the undefined value.  The `bug.hs` file contains the erroneous code, and `bugSolution.hs` shows the corrected version.

The error arises when the program attempts to use a variable that has not been properly initialized, leading to a runtime exception.

## Bug:

The `bug.hs` file defines a main function that attempts to print the value of a variable `x`, which is explicitly assigned `undefined`. This results in a runtime error.

## Solution:

The `bugSolution.hs` demonstrates how to correct this error by initializing `x` with a concrete value or handling potential undefined values more gracefully (e.g. using `maybe`).