## Expo CLI Android Build Failure: AGP Version Mismatch

This repository demonstrates a common issue encountered when building Android APKs using the Expo CLI.  The problem stems from an incompatibility between the AGP version expected by Expo and the one installed in your Android Studio environment.

The `bug.js` file contains example code that, when built with Expo CLI, triggers this error.  The `bugSolution.js` file provides a solution to resolve this conflict and successfully build the APK.  This issue is often solved by updating the AGP version or resolving conflicting dependencies, as detailed in the solution file.

This issue usually results in a build error that points to problems in the `gradle.properties` file or a related error message about conflicting AGP versions.

**Steps to Reproduce:**

1. Clone the repository.
2. Install the necessary dependencies: `npm install`
3. Run `expo build:android` to reproduce the error.
4. Follow the solution in `bugSolution.js` to resolve the error and build the APK successfully.