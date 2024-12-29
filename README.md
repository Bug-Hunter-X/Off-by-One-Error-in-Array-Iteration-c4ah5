# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The error occurs because the loop condition `i <= arr.length` should be `i < arr.length` to avoid accessing an index that is out of bounds.

The `bug.java` file contains the erroneous code, and `bugSolution.java` provides the corrected version.