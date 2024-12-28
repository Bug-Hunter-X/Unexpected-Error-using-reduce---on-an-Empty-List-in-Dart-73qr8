# Dart Reduce Method Error on Empty List

This repository demonstrates an uncommon error that can occur when using the `reduce()` method in Dart with an empty list.  The `reduce()` method requires at least one element in the list; otherwise, it throws a `StateError`. 

The `bug.dart` file contains the code that produces the error. The `bugSolution.dart` file shows how to handle this error gracefully.

## How to reproduce the error

1. Clone this repository.
2. Run `bug.dart` using the Dart VM.
3. Observe the error message.

## Solution

The solution involves checking if the list is empty before calling `reduce()`.  This prevents the error and allows for more robust code. See `bugSolution.dart` for an example.
