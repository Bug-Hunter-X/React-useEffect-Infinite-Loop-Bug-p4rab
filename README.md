# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook causing an infinite loop.  The example shows how improper dependency arrays can lead to unnecessary re-renders and performance issues.

## Bug Description
The provided code showcases an example where the `useEffect` hook is not properly optimized.  Incorrect usage of the dependency array can create an infinite loop.

## Solution
The solution demonstrates the correct usage of dependency arrays to avoid an infinite loop.  By correctly specifying the dependencies, we ensure that `useEffect` only executes when necessary.

## How to Reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.