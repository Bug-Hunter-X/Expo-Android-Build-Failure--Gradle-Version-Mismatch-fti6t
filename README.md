# Expo Android Build Failure: Gradle Version Mismatch

This repository demonstrates a common error encountered when building Android apps with Expo CLI. The error arises from a mismatch between the Android Gradle Plugin version and the Gradle version specified in the project's `gradle/wrapper/gradle-wrapper.properties` file.

## Problem
The build process fails, producing error messages related to Gradle version incompatibility. This can manifest in various ways, usually indicating that the plugin version is incompatible with the project's current Gradle version.

## Solution
The solution involves updating the Gradle version and possibly the Android Gradle Plugin version in the project's configuration to ensure compatibility.  Consult the official Android Gradle Plugin release notes to find compatible versions.

## Steps to Reproduce
1. Follow the instructions in `buildError.js` to set up a project that reproduces the bug.
2. Attempt to build the Android app using the Expo CLI.
3. Observe the resulting error messages.

## How to Fix
Follow the instructions in `buildSolution.js` to modify the project's Gradle versions and resolve the build issue.