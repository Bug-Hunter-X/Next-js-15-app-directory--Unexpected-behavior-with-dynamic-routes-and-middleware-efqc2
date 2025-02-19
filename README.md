# Next.js 15 App Directory Bug: Dynamic Routes and Middleware

This repository demonstrates an unexpected behavior encountered when using dynamic routes and middleware in Next.js 15's App directory.  The issue involves inconsistent behavior between client-side navigation and initial server-side rendering. 

## Bug Description
The bug is observed when using dynamic routes and middleware. Under some specific conditions, the middleware does not execute correctly on client-side navigation, leading to unexpected behavior or incorrect data being displayed.

## Steps to Reproduce
1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to a dynamic route. 
5. Observe inconsistent behavior between initial load and client side navigation.

## Solution
The solution is detailed in `bugSolution.js`