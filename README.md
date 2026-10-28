# Test21

## Project overview

This repository contains a small Angular 21 application used to compare two development setups:

- **`no-mcp` branch**: generated from an AI-assisted run **without** Angular MCP configured.
- **`master` branch**: generated from an AI-assisted run **with** Angular MCP configured.

The app currently uses modern Angular patterns (standalone components, signal-based inputs) and includes Angular image optimization through `NgOptimizedImage` in the header component ([header.ts](./src/app/header/header.ts)).

## Angular and `NgOptimizedImage`

- This project uses Angular **21** (`@angular/*` dependencies are on `^21.2.17`).
- `NgOptimizedImage` (from `@angular/common`) was introduced in **Angular 14.2** (developer preview) and became stable in Angular 15.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

