# React Native Uninitialized State Variable Access

This repository demonstrates a common error in React Native: accessing a state variable before it's been initialized by `useState`.  This typically occurs within conditional statements or asynchronous operations where the state hasn't fully updated yet.

The `bug.js` file shows the problematic code, which causes a runtime error. The solution is provided in `bugSolution.js`, illustrating how to handle this using conditional rendering and/or the `useEffect` hook.