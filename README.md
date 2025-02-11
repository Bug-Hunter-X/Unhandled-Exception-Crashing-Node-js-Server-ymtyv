# Unhandled Exception in Node.js Server

This repository demonstrates a common error in Node.js applications: unhandled exceptions causing server crashes.  The `bug.js` file shows a server that throws an error without catching it.  The `bugSolution.js` file provides a solution using error handling to prevent crashes.

## How to Reproduce the Bug

1. Clone this repository.
2. Run `node bug.js`.
3. Access the URL `http://localhost:3000/error` in your browser.
4. Observe that the server crashes.

## Solution

The `bugSolution.js` demonstrates how to handle exceptions gracefully using a `try...catch` block to prevent the server from crashing.