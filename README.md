# Node.js Server Unresponsiveness

This repository demonstrates a common Node.js issue: server unresponsiveness caused by a long-running synchronous operation within the request handler.  The `server.js` file contains the problematic code. The `serverSolution.js` file provides a solution using asynchronous operations and demonstrates the effect of blocking the event loop.