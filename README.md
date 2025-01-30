# Uncommon Dart Asynchronous Error: Missing Exception Details

This repository demonstrates a subtle error in asynchronous Dart code and how to improve its error handling. The original code handles exceptions during the API call, but doesn't provide enough context for debugging. The improved version provides more specific information about the error, making debugging significantly easier.

## Problem

The `fetchData` function in `bug.dart` handles exceptions. However, if an exception occurs, the error message printed is generic and doesn't provide the specific exception type or stack trace. This lack of detailed information makes debugging difficult.