# Architecture

## Current state

The repository contains no runtime modules or dependency graph.

## Intended boundaries

```text
admin UI/API
      ↓
authorization and application services
      ↓
domain models and audit events
      ↓
infrastructure adapters
```

Authentication should establish identity, authorization should enforce
permissions, and audit logging should record administrative actions without
owning business policy. Infrastructure details must remain behind adapters so
domain logic is testable without production services.
