# ActionScript ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common error in ActionScript: the `ArrayIndexOutOfBoundsException`.  This exception occurs when you try to access an element in an array using an index that is out of the array's valid range (0 to length-1). The provided code attempts to access the element at the index equal to the array's length, which is always one position beyond the last valid element. The solution demonstrates how to avoid this error by checking the array's length before accessing elements.

## How to reproduce

1.  Clone this repository.
2.  Compile and run the `bug.as` file.  You will get an `ArrayIndexOutOfBoundsException`.
3.  Examine the `bugSolution.as` file for a corrected version of the code.