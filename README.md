# XXXDONGXXX - Go Server Template

This is a server template project generated for XXXDONGXXX.

## Features

- Graceful shutdown (max 1 minute)
- chi router
- Structured logging with per-level files and basic rotation (daily + ~1GB split)
- Request-scoped transaction ID (X-Request-Id)
- Concurrency limiting middleware
- Per-request timeout middleware
- Worker pool with channel-based communication
- Simple scheduler with daily/monthly/yearly example jobs
- JSON config with hot reload (for selected fields)
- Health (`/healthz`), readiness (`/readyz`) and metrics (`/metrics`) endpoints
- Example handlers and tests
