# Tonka Portfolio - Turborepo

This is a [Turborepo](https://turbo.build/repo) monorepo containing the portfolio application and shared components.

## What's inside?

This Turborepo includes the following apps and packages:

### Apps

- `apps/portfolio`: The main portfolio Next.js application
- `apps/components`: Shared component library (empty for now)

### Utilities

This Turborepo uses npm workspaces for package management.

## Getting Started

### Install dependencies

```bash
npm install
```

### Build all apps and packages

```bash
npm run build
```

### Run development servers

```bash
npm run dev
```

This will start all apps in development mode. To run a specific app:

```bash
npm run dev --filter=@tonka-portfolio/portfolio
```

### Lint

```bash
npm run lint
```

## Project Structure

```
.
├── apps
│   ├── portfolio          # Main portfolio Next.js app
│   └── components         # Shared component library
├── turbo.json             # Turborepo configuration
└── package.json           # Root package.json with workspaces
```

## Learn More

To learn more about Turborepo, take a look at the following resources:

- [Turborepo Documentation](https://turbo.build/repo/docs)
- [Turborepo GitHub](https://github.com/vercel/turbo)
