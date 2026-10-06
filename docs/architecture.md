# Architecture

This document describes Awqat's current implementation boundaries and the
data flow between them.

## Current modules

- `src/core`: prayer-time, date, storage, search, and domain logic
- `src/tui`: terminal user interface and interaction handling
- `src/tray`: desktop notification or tray integration

## Documentation rule

Document user-visible behavior in `docs/requirements/`. Document significant
technical choices in `docs/decisions/`.
