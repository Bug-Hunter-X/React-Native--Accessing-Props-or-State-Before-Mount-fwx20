# React Native: Accessing Props or State Before Mount

This repository demonstrates a common error in React Native: attempting to access component props or state before the component has fully mounted.  This can lead to undefined values and unexpected behavior.

The `bug.js` file shows the erroneous code.  `bugSolution.js` provides the corrected version.

## How to reproduce the bug:

1. Clone this repository.
2. Run `npm install`.
3. Run the app.
4. Observe the console log in the initial render.