# Expo Go Connection Error

This repository demonstrates a common, yet frustrating, issue in Expo Go where changes to your project result in connection errors or timeouts without clear error messages. The error is often caused by a mismatch between the Expo Go app's state and the current project code, and it's usually resolved by restarting Expo Go or rebuilding the project. This example provides a simple setup to reproduce the problem and the solution.

## Reproduction Steps

1. Clone the repository.
2. Run `npm install`.
3. Start the development server using `expo start`.
4. Open the project in Expo Go. 
5. Modify a component (e.g. change some text). Save the change. 
6. Observe that Expo Go may not reflect the change immediately. You may see error messages related to connection problems or timeouts. 

## Solution

The most reliable way to address this is to completely restart the Expo Go app.  Alternatively, rebuild the project, but this is a slower process.

This demonstrates a frequent, vague error found in Expo Go which isn't easily debugged by reading the error messages. The resolution is usually a quick restart.