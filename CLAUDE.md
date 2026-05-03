# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

`allergy-track` is an application for tracking allergies.

## Tech Stack

- **Framework**: TanStack Start (full-stack React, SSR, file-based routing)
- **Language**: TypeScript
- **Routing**: TanStack Router (`src/routes/`, file-based)
- **Styling**: Tailwind CSS v4
- **Build**: Vite + Vinxi
- **Deploy adapter**: Nitro (agnostic)
- **Testing**: Vitest + Testing Library

## Project Structure

```
src/
  router.tsx          # Router entry point
  routes/
    __root.tsx        # Root layout
    index.tsx         # Home route (/)
  styles.css          # Global styles
public/               # Static assets
vite.config.ts
tsconfig.json
```

## Commands

```bash
npm run dev      # Start dev server
npm run build    # Production build
npm run test     # Run tests
```

## Notes

- The developer uses a JetBrains IDE (`.idea` is gitignored).
