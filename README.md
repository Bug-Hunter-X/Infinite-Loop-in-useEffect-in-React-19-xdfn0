# React 19 useEffect Infinite Loop Bug

This repository demonstrates a bug in React 19 where a `useEffect` hook runs after every render, even without dependencies, leading to an infinite loop.  The issue is related to how state updates trigger unnecessary re-renders. The solution involves adding the correct dependencies to the useEffect hook.