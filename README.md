> [!WARNING]
> This project is now part of the [choco-theme repository](https://github.com/chocolatey/choco-theme/tree/main/packages/playwright). Please visit that location for the latest updates and code.

# Chocolatey choco-playwright

**NOTE: This project is used on Chocolatey websites and is being released for the benefit of the community. While we endeavour to help and fix issues, it will be limited to GitHub issues, discussions and pull requests when we are able to.**

This repository holds all common Playwright specific code that is used across many Chocolatey projects.

## Commands

| Command                                       | Description                                        |
| --------------------------------------------- | -------------------------------------------------- |
| `yarn`                                        | Installs dependencies. |
| `yarn choco-theme`                            | Copies and prepares ESLint for usage. Required for ESLint commands. |
| `yarn audit`                                  | Audits all dependencies recursively and ignores [sweetalert2 vulnerability](https://github.com/advisories/GHSA-mrr8-v49w-3333). |
| `yarn eslint`                                 | Runs ESLint to reports errors and warnings. |
| `yarn eslint --fix`                           | Runs ESLint and attempts to fix errors and warnings automatically. |
