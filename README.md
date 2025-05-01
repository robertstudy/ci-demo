# CI Example

Simple Node.js repo with test + lint GitHub Actions.

## Recent Changes

1. **Workflow Updates**:
   - The GitHub Actions workflow now runs on pushes any branch, not just `main`.
   - Updated the Node.js version from `20` to `22`.
   - Added caching for the `node_modules` directory using `actions/cache@v2`.

2. **Bug Fix**:
   - Fixed a logic bug in the `add.js` file to ensure the `add` function correctly adds two numbers.