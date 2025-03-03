# npm-workspaces

This is a simple project that introduces Npm Workspaces that convert date and time whithout an existing node lib, creating by my own

## date-util

Provides utility functions for formatting dates and converting date strings between different formats.

```
DateUtil.formatString('03/03/2025', 'dd/mm/yyyy', 'yyyy-mm-dd')
// Output: '2025-03-03'
```

## string-util

Removes all whitespace (\s) characters (spaces, tabs, newlines) from the given string.

## What is NPM Workspaces?

NPM Workspaces is a feature introduced in npm 7+ that allows you to manage multiple packages (or projects) within a single repository (monorepo). It simplifies dependency management and linking between packages, making it easier to work with multiple interdependent modules.

Why Use NPM Workspaces?

📦 Centralized dependency management – Install dependencies once at the root instead of per package.

🔗 Automatic linking – Packages within the workspace are linked automatically.

🚀 Efficient monorepo development – Helps in managing multiple related packages in a single repo.
