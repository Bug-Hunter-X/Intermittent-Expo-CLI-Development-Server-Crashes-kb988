# Intermittent Expo CLI Development Server Crashes

This repository demonstrates a problem where the Expo CLI development server crashes randomly without providing any specific error messages.  The associated application also stops functioning and requires a restart of both the server and the simulator/device.

## Problem Description

The issue occurs intermittently and is not consistently reproducible. No particular code changes seem to consistently trigger this behavior.  Debugging is difficult due to the absence of error messages.

## Reproduction Steps

The exact steps to reproduce this problem are currently unknown. It appears to be related to a state within Expo's development server, and may involve factors such as memory management or asynchronous operations that are difficult to track down. 

## Potential Solutions (Investigative)

The `expoBugSolution.js` file contains potential solutions or areas to investigate.  Further investigation is required to identify the root cause and implement a robust fix.