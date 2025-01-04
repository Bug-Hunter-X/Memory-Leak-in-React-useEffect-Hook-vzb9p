# React useEffect Hook Memory Leak

This example demonstrates a common mistake in React's `useEffect` hook that can lead to memory leaks.  The `setInterval` function within the `useEffect` is not properly cleaned up, resulting in the interval continuing indefinitely, even after the component unmounts. This will cause memory leaks and performance issues in your React app.

The solution shows the correct way to implement the `useEffect` hook with cleanup to prevent this error.