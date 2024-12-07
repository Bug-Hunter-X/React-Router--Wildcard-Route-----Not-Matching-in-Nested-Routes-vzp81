# React Router Wildcard Route Issue

This repository demonstrates a subtle bug in React Router v6 where a wildcard route (`/*`) does not match when nested within other routes. The root cause is that the wildcard route only works at the top level if other routes are not present which match before it. 