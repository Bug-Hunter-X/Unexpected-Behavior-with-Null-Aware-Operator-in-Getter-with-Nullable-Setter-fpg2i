# Unexpected Behavior with Null-Aware Operator in Getter with Nullable Setter

This repository demonstrates an uncommon error in Dart related to the use of the null-aware operator (??) in a getter when the corresponding setter allows null values.  The issue arises when attempting to set the private variable to null after initially using the null-aware operator. This leads to an unexpected runtime error.

The `bug.dart` file contains the problematic code.  The `bugSolution.dart` file provides a solution to avoid this error.

## How to reproduce

1. Clone this repository.
2. Open the `bug.dart` file.
3. Run the code using a Dart compiler.
4. Observe the runtime error when attempting to set the `myVariable` to null.

## Solution

Refer to the `bugSolution.dart` file for a solution that addresses this issue by using different logic in getter and handling null values explicitly.