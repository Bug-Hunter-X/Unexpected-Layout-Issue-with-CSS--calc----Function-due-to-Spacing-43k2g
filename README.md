# Unexpected Layout Issue with CSS `calc()` Function due to Spacing

This repository demonstrates an uncommon error that can occur when using the CSS `calc()` function. Specifically, the issue arises from incorrect spacing within the `calc()` function's expression, leading to unexpected layout results.

## Problem
The `calc()` function is a powerful tool for performing calculations within CSS. However, it's susceptible to errors when spaces are incorrectly placed.  In this case, an extra space after the `-` sign in `calc(50% - 10px)` prevents the subtraction operation from working correctly.

## Solution
The solution involves removing extra spaces within the `calc()` function's expression. Make sure to have no spaces between operators and operands to ensure correct calculation.

## How to reproduce
1. Clone this repository.
2. Open `bug.css` to observe the incorrect CSS.
3. Open `bugSolution.css` to see the corrected CSS.
4. Compare the layout results in your browser.