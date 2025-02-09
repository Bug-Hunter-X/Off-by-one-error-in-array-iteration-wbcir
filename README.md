# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating through arrays.  The `BuggyArray.java` file contains the erroneous code, while `FixedArray.java` provides the corrected version. 

The error arises from an incorrect loop condition that leads to accessing an element beyond the array bounds, resulting in an `ArrayIndexOutOfBoundsException`.  The solution simply adjusts the loop condition to properly iterate within the array's valid index range. 

This is a classic example of a subtle but potentially critical bug.  Always carefully consider your loop conditions when working with arrays or other indexed data structures.