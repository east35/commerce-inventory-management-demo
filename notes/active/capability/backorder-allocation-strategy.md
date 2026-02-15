---
title: "Backorder Allocation Strategy"
slug: "backorder-allocation-strategy"
status: active
category: capability
priority: medium
owner: "@alex.chen"
ai_visible: true
phase: null
dependencies: ["inventory-north-star"]
tags: ["allocation", "orders", "fulfillment"]
updated_at: "2026-02-15T14:19:26.829Z"
created_at: "2026-02-15T14:19:26.829Z"
---
## Objective

Allocate scarce inventory by service tier and promised ship date.

## Strategy

- Priority by service tier first
- Tie-break by promised date
- Reserve pool for replacement orders

## Validation

- [x] Simulation completed on 60-day dataset
- [ ] Ops sign-off for reserve pool percentages