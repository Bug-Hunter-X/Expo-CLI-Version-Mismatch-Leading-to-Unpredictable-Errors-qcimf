# Expo CLI Version Mismatch

This repository demonstrates a common yet elusive bug in Expo CLI: version mismatches between the CLI and project dependencies.  This can lead to a variety of cryptic errors during development and build processes.

## Problem
The core issue is that an outdated or incompatible Expo CLI version can cause unexpected behavior, often resulting in seemingly unrelated errors during the app's build or runtime. This makes debugging significantly more challenging, as error messages often aren't directly related to the underlying version conflict.

## Solution
The solution involves ensuring that your Expo CLI version aligns with your project's dependencies.  This typically requires updating both the CLI itself and resolving any discrepancies in the `package.json` file.  Careful attention to the Expo SDK version and its compatibility with the CLI is crucial.

## Reproduction
Refer to `bug.js` for an example project setup that might trigger this issue (though the exact manifestation may vary).  The `bugSolution.js` shows the steps to resolve the problem.