# Unhandled Error: Invalid User ID in Express.js Route

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when dealing with user input.  Specifically, the code attempts to access a user based on an ID parameter, but doesn't account for the possibility of an invalid or non-numeric ID.  This can lead to unexpected crashes or incorrect behavior.

The `bug.js` file contains the faulty code.  The `bugSolution.js` file provides the corrected version with improved error handling.