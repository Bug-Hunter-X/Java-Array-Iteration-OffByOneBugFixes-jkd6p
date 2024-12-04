# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The error occurs in the `for` loop's condition, where the loop attempts to access an element beyond the array's bounds. This results in an `ArrayIndexOutOfBoundsException`.

The `Bug.java` file contains the erroneous code. The `BugSolution.java` file provides the corrected code.

## How to reproduce

1. Clone the repository.
2. Compile `Bug.java` using a Java compiler (e.g., `javac Bug.java`).
3. Run the compiled code (e.g., `java Bug`).

You'll observe an `ArrayIndexOutOfBoundsException`.  To see the correct implementation, run `BugSolution.java`.