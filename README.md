# JavaScript Type Coercion Bug

This repository demonstrates a common, yet subtle, bug in JavaScript related to type coercion and null checks.  The `foo` function is designed to add two numbers, but returns `null` if either input is `null`. However, due to JavaScript's loose typing, the strict equality (`===`) operator can lead to unexpected results. 

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a corrected version.