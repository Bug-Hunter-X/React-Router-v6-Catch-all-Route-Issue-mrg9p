This repository demonstrates a common issue in React Router v6 involving catch-all routes (`/*`).  The problem occurs when a catch-all route is defined after more specific routes. Even with exact matches, the catch-all route takes precedence.  The solution shows how to correctly order routes or use the `useLocation` hook for more controlled error handling. 