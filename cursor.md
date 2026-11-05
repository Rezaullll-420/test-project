# Cursor project guide

## Project overview

A Node.js web app built with TypeScript and Next.js. The UI is React, and dependencies are installed with npm.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js
- **UI:** React
- **Package manager:** npm

## Project structure

```
app/            routes, layouts, and pages
components/     shared React components
lib/            helpers and shared logic
public/         static assets
types/          shared TypeScript types
```

## Coding convention

- Write new code in TypeScript.
- Use functional React components.
- Keep route files in `app/` and reusable UI in `components/`.
- Name component files in PascalCase and other files in kebab-case.
- Prefer small, focused modules over large files.
