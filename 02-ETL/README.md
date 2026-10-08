# 02 — ETL / ELT

## Scope

Study how enterprise data is extracted from source systems, transformed or validated, and loaded into analytical or operational targets.

## Topics

- ETL vs ELT
- Batch vs real-time
- APIs, CSV and databases as sources
- Transformation and validation
- Incremental loads
- Idempotency
- Orchestration
- Monitoring and error handling

## Practical goal

Trace: **Source → Extract → Transform / Validate → Load → Target**.

Then identify orchestration, monitoring and failure recovery.

## Exercise

Planned: API / CSV → transformation → PostgreSQL pipeline, with orchestration.

## Questions

1. When is ETL preferable to ELT?
2. What makes a pipeline idempotent?
3. How should failed records be handled?
4. What is the role of a staging layer?
5. Where should data quality validation occur?
