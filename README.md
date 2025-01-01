# Unnecessary Re-renders in React useEffect Hook

This repository demonstrates a common issue in React applications involving the `useEffect` hook. The provided code shows an effect that runs on every render, leading to unnecessary re-renders and potential performance issues.  The solution demonstrates how to correctly use the dependency array to optimize the effect's execution.

## Bug Description

The original `MyComponent` uses `useEffect` without properly specifying the dependency array. This causes the effect to run on every render, even when the `count` value hasn't changed.  This is inefficient and can cause performance degradation in more complex applications.

## Solution

The corrected version demonstrates how to correctly specify dependencies to optimize `useEffect` behavior.