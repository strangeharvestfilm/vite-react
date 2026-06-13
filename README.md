# Vite React Lab

A small React + TypeScript workspace for fast front-end sketches, interface tests, and strange little web experiments.

This repository is intentionally lightweight: Vite for speed, React for components, TypeScript for guardrails, and ESLint for keeping the edges clean. It is a place to prototype ideas before they become part of a larger site or production build.

## Current Shape

- React 18 with TypeScript
- Vite development server and production build
- ESLint configured for React hooks and refresh
- Minimal starter UI kept in place until the next experiment lands

## Getting Started

Install dependencies:

```shell
npm install
```

Run the development server:

```shell
npm run dev
```

Check linting:

```shell
npm run lint
```

Create a production build:

```shell
npm run build
```

Preview the production build locally:

```shell
npm run preview
```

## Project Structure

```text
src/
  App.tsx        Main application component
  App.css        Component-level styles
  index.css      Global styles
  main.tsx       React entry point
public/          Static assets served by Vite
```

## Working Style

This repo is for small, clean iterations. Keep changes easy to read, name experiments clearly, and document anything that would be confusing to revisit later.

The vibe: polished enough to share, loose enough to keep moving.

## Roadmap

- Replace the starter screen with the first real interface concept.
- Add screenshots or preview links once the project has a visual direction.
- Split reusable components into `src/components/` when repetition appears.
- Add lightweight tests when behavior becomes more than visual exploration.

## Notes

This project is part of the `strangeharvestfilm` GitHub workspace.
