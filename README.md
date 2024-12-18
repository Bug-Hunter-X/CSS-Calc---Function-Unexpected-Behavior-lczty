# CSS Calc() Unexpected Behavior
This repository demonstrates a common issue with the CSS `calc()` function and presents a solution. The `calc()` function, while powerful, can be prone to errors if not used carefully.  This example highlights issues related to unit consistency and the order of operations.

## Bug
The original CSS uses `calc()` to dynamically calculate the width of an element. However, due to an oversight in the unit handling, the calculation yields unexpected results, and the resulting element's width is not as intended.

## Solution
The solution addresses the problem by ensuring proper unit conversion and using more straightforward calculations to avoid ambiguity.