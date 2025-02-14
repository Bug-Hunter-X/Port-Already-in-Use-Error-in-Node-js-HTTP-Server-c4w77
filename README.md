# Node.js Port Already in Use Error

This repository demonstrates a common error in Node.js when creating an HTTP server: the 'port already in use' error.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a robust solution.

## Problem

Attempting to start a Node.js HTTP server on a port that is already occupied by another process results in an error.  The server fails to start, and the application terminates.

## Solution

The solution involves checking if the port is available before attempting to start the server.  Error handling is implemented to gracefully manage the situation, providing informative messages to the user.