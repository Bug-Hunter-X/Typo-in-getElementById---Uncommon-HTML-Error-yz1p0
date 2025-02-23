# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle error that can occur in HTML when using `document.getElementById`. A simple typo in the function name can lead to unexpected behavior and errors.

## Bug Description
The `bug.html` file contains a typo in the `document.getElementById` function, causing a runtime error because the function doesn't exist.  The error occurs when the program tries to access the `innerHTML` of an element that doesn't exist.  The correct way to access the element is to use `document.getElementById()`.  This demonstrates how minor errors in function names can create significant problems in your code.