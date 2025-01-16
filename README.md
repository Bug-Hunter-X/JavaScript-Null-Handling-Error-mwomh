# JavaScript Null Handling Bug

This repository demonstrates a common error in JavaScript involving the improper handling of null values. The `foo` function attempts to add two numbers; however, it fails to gracefully handle cases where one or both input parameters are null. This can lead to unexpected results or errors.

The `bug.js` file showcases the problematic code. The `bugSolution.js` file provides a corrected version that explicitly checks for null values and handles them appropriately, returning null in such cases.

This example highlights the importance of robust null checks to avoid unexpected behavior and ensure the reliability of JavaScript applications.