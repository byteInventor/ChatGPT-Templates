# Debugging Template

Use this template when you need help debugging issues in your code or projects.

## Template

```
**Context:** [project type, framework, version]

**Problem:** [error/logs/symptom]

**My hypothesis:** [what I think is wrong]

**Goal:** [what I need fixed/explained]
```

## Example Usage

```
**Context:** React 18.2.0 with TypeScript, using Vite as build tool

**Problem:** Getting "Cannot read property 'map' of undefined" error when trying to render a list of items. The error occurs intermittently on page load.

**My hypothesis:** The API data might not be loaded yet when the component tries to render, causing the array to be undefined initially.

**Goal:** I need to understand why this is happening and implement a proper solution to handle the loading state safely.
```

## Tips for Better Results

- **Be specific about your context**: Include exact versions, frameworks, and relevant tools
- **Include actual error messages**: Copy the exact error text, stack traces, or logs
- **Share relevant code snippets**: Include the problematic code section
- **Explain what you've tried**: Mention any debugging steps you've already taken
- **State your end goal clearly**: Specify whether you want an explanation, a fix, or both