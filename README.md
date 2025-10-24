# SGOs

A mono repository for SGOs (Smart Goal Objectives).

## Structure

This is a pnpm-based mono repository with the following structure:

```
SGOs/
├── packages/          # Individual packages/projects
│   └── pre-sgo/      # Pre-SGO package
├── package.json      # Root package.json with workspaces
└── pnpm-workspace.yaml
```

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- pnpm >= 8.0.0

### Installation

```bash
# Install pnpm if you haven't already
npm install -g pnpm

# Install dependencies
pnpm install
```

### Development

```bash
# Run dev mode for all packages
pnpm dev

# Build all packages
pnpm build

# Run tests
pnpm test

# Lint all packages
pnpm lint
```

## Packages

- **pre-sgo**: [Description coming soon]

## Contributing

[Contributing guidelines coming soon]

## License

[License information coming soon]
