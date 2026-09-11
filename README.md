# zqmlabs-shared

Shared types, utilities, and configuration constants for the ZQM modular architecture.

## Purpose

This module provides shared code across all ZQM services:
- **TypeScript types** — Shared interfaces used by frontend and backend
- **Python utilities** — Common helper functions
- **Configuration** — Shared constants and environment variables

## Architecture

This is the **shared layer** of the ZQM modular architecture.

## Repo Map

```
zqmlabs-frontend ←→ zqmlabs-shared (TypeScript types)
zqmlabs-backend ←→ zqmlabs-shared (Python utilities)
zqmlabs-gamification ←→ zqmlabs-shared (shared types)
```
