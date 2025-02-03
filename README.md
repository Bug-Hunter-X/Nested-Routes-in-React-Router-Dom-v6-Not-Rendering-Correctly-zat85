# React Router Dom v6 Nested Route Issue

This repository demonstrates a bug in React Router Dom v6 where nested routes do not render correctly. The catch-all route (`/*`) always seems to be rendering, overriding nested routes that should logically match first.

## Bug Description
Nested routes within a parent route are not rendering as expected in React Router Dom v6. The catch-all route (`/*`) is overriding the rendering of nested routes, always displaying the Not Found component even when the nested route should be shown.