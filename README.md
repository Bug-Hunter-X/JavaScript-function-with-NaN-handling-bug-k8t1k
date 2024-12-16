# JavaScript Function with NaN Handling Bug

This repository demonstrates a common JavaScript bug related to the improper handling of NaN (Not a Number) values.

## Bug Description

The `foo` function adds two numbers. It correctly handles null values by returning 0. However, it fails to address NaN values, resulting in NaN being returned when one or both inputs are NaN.

## Bug Solution

The solution involves checking for NaN explicitly using `isNaN()` before performing the addition.  This ensures that NaN is treated appropriately and a more meaningful result (such as 0) is returned.

## How to Run

1. Clone the repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run both files in a JavaScript environment (e.g., Node.js, browser's console).