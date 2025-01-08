# Unexpected Results from CSS `calc()` function
This repository demonstrates a scenario where the CSS `calc()` function produces unexpected results due to inconsistent units or incorrect order of operations. The `bug.css` file contains the problematic code, while `bugSolution.css` provides a corrected version.

## Bug Description
The `calc()` function in CSS allows for dynamic calculations. However, if the units are inconsistent or the order of operations is incorrect, the calculations might not produce the expected output.  This can lead to unexpected layout issues or visual discrepancies.

## Solution
The solution involves carefully checking the units used within the `calc()` function to ensure they are consistent. Also, parentheses should be used to correctly enforce the order of operations if necessary.  This ensures accurate calculations and predictable results.

## How to reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser. 
3. Observe the unexpected layout/rendering.
4. Open `bugSolution.html` (if provided) and observe the corrected layout/rendering.