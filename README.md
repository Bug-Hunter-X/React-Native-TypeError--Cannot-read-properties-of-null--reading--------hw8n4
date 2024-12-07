# React Native TypeError: Cannot read properties of null (reading '...')

This repository demonstrates a common error in React Native: `TypeError: Cannot read properties of null (reading '...')`. This error arises when trying to access properties of an object that's unexpectedly `null` or `undefined`.  The example showcases the problem and its solution using optional chaining and nullish coalescing.

## Problem
The core issue is accessing properties before confirming the object's existence and validity. This frequently happens when dealing with asynchronous data fetching or component lifecycle events where data might be unavailable initially.

## Solution
The solution involves employing optional chaining (`?.`) and the nullish coalescing operator (`??`). These operators provide safer ways to handle potentially null or undefined values.

## How to reproduce
1. Clone the repository.
2. Run `npm install` to install the necessary dependencies.
3. Run the project using your preferred React Native environment (e.g., `npx react-native run-android` or `npx react-native run-ios`).
4. Observe the error and then the solution in action.