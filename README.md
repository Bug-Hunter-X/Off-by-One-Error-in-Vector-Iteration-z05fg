# Off-by-One Error in C++ Vector Iteration

This repository demonstrates a common off-by-one error that occurs when iterating over a `std::vector` in C++.  The error arises from using an incorrect loop condition, causing an out-of-bounds access and undefined behavior.

The `bug.cpp` file contains the erroneous code. The `bugSolution.cpp` file demonstrates the corrected code with a proper loop condition.

This example highlights the importance of careful loop condition checking when working with containers in C++ to avoid potential runtime errors and crashes.