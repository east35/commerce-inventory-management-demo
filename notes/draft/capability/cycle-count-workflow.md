---
title: "Cycle Count Workflow"
slug: "cycle-count-workflow"
status: draft
category: capability
priority: high
owner: "@jamie.park"
ai_visible: true
phase: null
dependencies: ["warehouse-event-ingestion"]
tags: ["warehouse", "operations", "counting"]
updated_at: "2026-02-15T14:15:53.341Z"
created_at: "2026-02-15T14:15:53.341Z"
---
## Intent

Design daily cycle-count workflows for high-velocity SKUs.

## User Flow

1. Supervisor creates count batch
2. Picker scans assigned bins
3. Variance routed to approver

## Open Questions

- How many recount attempts before escalation?
- Should mobile mode support offline bin scans?