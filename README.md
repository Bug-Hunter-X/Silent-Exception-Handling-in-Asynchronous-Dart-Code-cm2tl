# Silent Exception Handling in Asynchronous Dart Code

This repository demonstrates a common error in Dart asynchronous programming: silently catching exceptions without proper handling or re-throwing.

The `bug.dart` file showcases the problematic code where an exception during an HTTP request is caught but not handled or re-thrown, making it harder to debug potential issues.

The solution in `bugSolution.dart` addresses this by properly handling or re-throwing exceptions. This improves error handling, allowing for better debugging and application stability.
