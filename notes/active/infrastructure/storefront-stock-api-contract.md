---
title: "Storefront Stock API Contract"
slug: "storefront-stock-api-contract"
status: active
category: infrastructure
priority: high
owner: "@liam.ng"
ai_visible: true
phase: null
dependencies: ["warehouse-event-ingestion"]
tags: ["api", "storefront", "integration"]
updated_at: "2026-02-15T14:15:53.341Z"
created_at: "2026-02-15T14:15:53.341Z"
---
## Contract

Expose available-to-sell, reserved, and backorderable units per SKU-location.

## SLA

- p95 latency < 180ms
- freshness < 5 minutes
- 99.9% availability

## Integration Notes

Payments project consumes this for pre-auth risk checks on low-stock items.