# Node.js Server Crashing Under Load

This repository demonstrates a common issue in Node.js applications where the server crashes under heavy load due to unhandled exceptions or memory leaks.  The original `server.js` file contains the buggy code. The solution, provided in `serverSolution.js`, addresses the issue.

## Setup

1. Clone the repository.
2. Run `npm install`
3. Run `node server.js`
4. Simulate load using tools such as `wrk` or `ab`.