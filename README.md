# Uncommon HTML Error: Incorrect innerHTML Usage

This repository demonstrates an uncommon error related to the `innerHTML` property in HTML.  The error stems from attempting to assign a non-string value (in this case, a number) to `innerHTML`.  This can result in unexpected behavior or errors in the browser's console.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file provides a corrected version. This demonstrates the importance of using strings when setting the `innerHTML` property. This is a subtle error that may not be caught by simple linting tools.