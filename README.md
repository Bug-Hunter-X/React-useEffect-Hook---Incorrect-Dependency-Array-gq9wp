# React useEffect Hook - Incorrect Dependency Array

This repository demonstrates a common error in React's `useEffect` hook: an incorrect dependency array. The problem arises when a function declared within `useEffect` does not have the correct dependency array to track changes, or when it has unnecessary dependencies.

The example provided in `bug.js` illustrates an interval timer within `useEffect` that is not properly cleaned up when the component is unmounted. This can lead to memory leaks and unexpected behavior in your application.

The corrected version in `bugSolution.js` demonstrates the appropriate use of the dependency array to address this issue. Refer to the comments for a detailed explanation of the fix.

## How to Reproduce
1. Clone the repository.
2. Navigate to the directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Observe the behavior and compare the original and corrected code examples.
