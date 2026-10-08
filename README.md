# Enterprise Integration Lab

A practical learning and portfolio project covering **SSO, ETL/ELT, and iPaaS** through hands-on exercises and enterprise architecture examples.

## Objectives

- **SSO:** SAML, OAuth 2.0, OIDC, JWT, and SCIM
- **ETL / ELT:** extraction, transformation, loading, orchestration, data quality, and incremental pipelines
- **iPaaS:** application integration, APIs, connectors, workflows, mapping, monitoring, and error handling
- **MuleSoft:** API-led connectivity and System / Process / Experience APIs
- **Workato:** recipe-based automation and business-process integration

## Learning approach

For each topic: what it is → why enterprises use it → how it works → practical exercise → architecture → trade-offs → when I would recommend it.

The emphasis is on **architecture and practical understanding**, not becoming a specialist developer in two days.

## Roadmap

- [ ] SSO fundamentals and practical OIDC/SAML lab
- [ ] ETL / ELT fundamentals and PostgreSQL pipeline
- [ ] iPaaS fundamentals
- [ ] MuleSoft: Anypoint, DataWeave, API-led connectivity
- [ ] Workato: recipes, connectors, automation
- [ ] Workato Automation Pro certification
- [ ] Final end-to-end enterprise integration case study

## Planned architecture

```text
Identity Provider
      │ SSO / SCIM
      ▼
SaaS / Business Apps
      │ APIs / Events
      ▼
   ┌─────────┐
   │  iPaaS  │
   └────┬────┘
        ├── CRM
        ├── ERP
        └── Provisioning
              │
              ▼
        Data Pipeline
              │
              ▼
        Data Warehouse
```

## Practical principle

> Understand the architecture first. Use the code to prove the architecture.

## Learning log

See [docs/learning-log.md](docs/learning-log.md) for progress, key concepts, practical work, and questions to revisit.
