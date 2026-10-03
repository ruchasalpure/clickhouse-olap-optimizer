---
name: clickhouse-query-tuning
description: Specialized capability for Profiles ClickHouse columnar analytical queries to optimize primary sorting keys, partition granularity, and sparse vector aggregations.
license: MIT
allowed-tools: ""
metadata:
  author: "Rucha Salpure"
  version: "1.0.0"
  category: data-analytics
---

# ClickHouse OLAP Optimizer Agent — Clickhouse Query Tuning Skill

## Purpose
The `clickhouse-query-tuning` capability provides high-assurance execution routines for `ClickHouse OLAP Optimizer Agent`.

## Execution Workflow
1. Validate input parameters against typed schemas and invariant constraints.
2. Ingest contextual metrics and establish a deterministic baseline.
3. Formulate candidate recommendations with explicit confidence intervals.
4. Submit draft plans to the independent checker agent for verification.

## Boundary Conditions
- **Input validation:** Reject non-conforming or malformed payloads before evaluation.
- **Fail-safe:** Escalate immediately if telemetry indicators exhibit critical anomalies.
