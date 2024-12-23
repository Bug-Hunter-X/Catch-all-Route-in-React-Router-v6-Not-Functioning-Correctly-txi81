# React Router v6 Catch-all Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`/*`) in React Router v6. The catch-all route, intended to handle any unmatched paths, fails to function as expected, potentially leading to unexpected behavior or rendering issues. The problem arises due to how the router handles routes and their order of precedence. 

## Problem

The `/*` route should ideally be placed at the end of the routes list to handle unmatched paths, but in some situations this doesn't work as expected. This example reproduces the issue and offers a simple solution.

## Solution

The solution involves understanding and correctly defining routes, and handling navigation.