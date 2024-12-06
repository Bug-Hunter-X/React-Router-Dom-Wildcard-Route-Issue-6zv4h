# React Router Dom Wildcard Route Issue

This repository demonstrates an unexpected behavior with nested routes and wildcard routes in React Router Dom v6.

The issue occurs when a wildcard route ('*') is nested within other routes.  The wildcard route should catch any unmatched paths, but it doesn't behave as expected in this scenario. 

## Steps to Reproduce

1. Clone this repository.
2. Install dependencies using `npm install`.
3. Run the application using `npm start`.
4. Navigate to a path that should be caught by the wildcard route.  You'll see that it doesn't work as expected.

## Solution

The solution involves restructuring the routes to ensure the wildcard route is at the top level of the routes structure and not nested inside other routes. 

Check out `AppSolution.js` for a working example.