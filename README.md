# React useEffect Dependency Array Bug
This repository demonstrates a common error in React's `useEffect` hook, specifically related to the dependency array.  Incorrectly specifying dependencies in the `useEffect` hook's second argument can lead to unexpected behavior, including stale closures and performance issues. This example showcases the problem and its solution.

## Bug
The `bug.js` file contains a `useEffect` hook that is missing a necessary dependency. This omission results in the counter not updating correctly.