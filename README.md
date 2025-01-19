# CSS calc() unexpected behavior with percentages and pixels
This repository demonstrates an uncommon issue with the `calc()` function in CSS when combining percentages and fixed units like pixels.  The `bug.css` file shows the problematic code, and `bugSolution.css` provides a potential workaround.

## Issue:
The `calc()` function in CSS doesn't always produce expected results when combining percentage and pixel values.  Under certain circumstances, this might lead to layout inconsistencies or unexpected rendering.

## Solution:
The solution might involve alternative layout strategies, using a different unit system, or adding a more robust fallback to account for inconsistent browser implementations.