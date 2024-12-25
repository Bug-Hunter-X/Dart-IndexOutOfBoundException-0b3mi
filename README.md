# Dart IndexOutOfBoundsException Bug

This repository demonstrates a common error in Dart: the `IndexOutOfBoundsException`.  The `bug.dart` file contains code that attempts to access an element of a list using an index that is out of range. This results in a runtime exception. The `bugSolution.dart` file provides a corrected version that prevents this error.

## How to reproduce the bug

1. Clone this repository.
2. Run `bug.dart`. You will see an exception indicating the index is out of bounds.

## Solution

The solution involves checking the index before accessing the list element to ensure it is within the valid range (0 to list.length - 1). The `bugSolution.dart` file demonstrates the correct approach. 

This example highlights the importance of careful index management in Dart when working with lists and arrays.