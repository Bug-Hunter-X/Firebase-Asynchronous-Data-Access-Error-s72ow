# Firebase Asynchronous Data Access Error

This repository demonstrates a common error when working with Firebase's asynchronous data retrieval methods. The issue arises when attempting to access properties of a document snapshot before the data has fully loaded. This often manifests as `undefined` values or unexpected behavior.

The `bug.js` file shows the erroneous code that leads to this issue.  `bugSolution.js` provides the corrected code, demonstrating how to properly handle asynchronous operations using promises or async/await.

## How to Reproduce

1. Clone this repository.
2. Set up a Firebase project and configure your credentials.
3. Install the required packages: `npm install firebase`
4. Run `bug.js` and observe the console output (likely an error or undefined values).
5. Run `bugSolution.js` and observe that the output correctly handles asynchronous loading.