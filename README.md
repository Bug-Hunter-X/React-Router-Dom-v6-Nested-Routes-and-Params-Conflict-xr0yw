# React Router Dom v6 Nested Routes and Params Conflict

This repository demonstrates a bug in React Router Dom v6 related to nested routes and parameters in the path.  The issue occurs when a route with parameters is nested within other routes, causing a conflict and preventing the application from rendering correctly.  The provided solution outlines a way to resolve this conflict.

## Bug Description

The bug manifests when using the `useParams` hook in a nested route. The parameters are not correctly extracted, leading to unexpected behavior or errors. The specific scenario here is using a route such as `/users/:userId` causing a conflict and breaking the application.

## Solution

The solution uses a combination of route configurations and potentially updating the React Router Dom library to its latest version.  The code provides examples for both solutions.