---
title: "Warehouse Event Ingestion"
slug: "warehouse-event-ingestion"
status: active
category: infrastructure
priority: high
owner: "@mario.ramos"
phase: null
dependencies: ["inventory-north-star"]
tags: ["events", "etl", "warehouse"]
updated_at: "2026-02-15T03:01:53.949Z"
created_at: "2026-02-15T03:01:53.949Z"
---
## Scope

Ingest receives, picks, returns, and adjustments from WMS into canonical inventory events.

## Requirements

- Idempotent event keys
- Dead-letter queue visibility
- Replay by date range

## Acceptance Checklist

- [x] Event schema v1 finalized
- [x] DLQ alerts wired to on-call
- [ ] Replay API approved by platform review