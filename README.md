# Unexpected Behavior in CSS calc() Due to Spacing

This repository demonstrates a subtle but important bug in CSS related to the use of spaces within `calc()` expressions.  Incorrect spacing can lead to unexpected rendering.

## Bug Description

The `calc()` function in CSS is powerful for dynamic calculations. However, adding spaces around the operators (+, -, *, /) can cause the calculation to fail or produce unintended results.  This is not always immediately obvious and can be difficult to debug.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and `bugSolution.css`. 
3. Observe the difference in rendering behavior.

## Solution

Ensure there are NO spaces around the operators within the `calc()` expression.   Maintain a clean expression structure.  See `bugSolution.css` for the corrected code.
