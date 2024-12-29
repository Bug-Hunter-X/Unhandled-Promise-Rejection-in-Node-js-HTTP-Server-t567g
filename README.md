# Unhandled Promise Rejection in Node.js HTTP Server

This repository demonstrates a common error in Node.js where an unhandled promise rejection in an HTTP server leads to unresponsive behavior.  The `bug.js` file shows the problematic code. The server lacks proper error handling within the asynchronous operation, resulting in the server not sending a response to the client when errors occur.

The `bugSolution.js` file provides the corrected code with proper error handling using a catch block. This improved version ensures that the client receives a response even if an error occurs.