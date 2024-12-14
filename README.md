# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  lack of proper error handling for invalid input.  The `bug.js` file shows code that attempts to parse a user ID from a route parameter without sufficient error handling. This can cause crashes or unexpected behavior if the user ID is not a number.

The `bugSolution.js` file provides a corrected version with improved error handling, illustrating best practices for handling potential errors in Express.js applications.