# j

A React + Vite web application.

## Architecture

- **Frontend**: React 18 + TypeScript, built with Vite
- **Dev server**: Runs on port 5000 (`npm run dev`)
- **Build output**: `dist/` directory (static site)

## Project Structure

```
├── src/
│   ├── App.tsx        # Main app component
│   ├── main.tsx       # Entry point
│   └── index.css      # Global styles
├── index.html         # HTML entry point
├── vite.config.ts     # Vite configuration
├── tsconfig.json      # TypeScript config
└── package.json       # Dependencies and scripts
```

## Development

- `npm run dev` — start dev server on port 5000
- `npm run build` — build for production (outputs to `dist/`)

## Deployment

Configured as a static site deployment. Build command: `npm run build`. Public directory: `dist`.
