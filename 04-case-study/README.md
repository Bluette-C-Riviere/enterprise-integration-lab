# 04 — Final Enterprise Integration Case Study

## Scenario

A European enterprise software provider needs to connect identity, CRM, ERP, provisioning and analytics systems.

## Target flow

1. A new enterprise customer is created in CRM.
2. Integration middleware validates and maps customer data.
3. ERP and provisioning systems are updated.
4. Users authenticate through enterprise SSO.
5. SCIM manages user lifecycle.
6. Transactional data moves to an analytical environment.
7. Failures are monitored and retried.

## Deliverables

- Context diagram
- Integration architecture
- Identity flow
- Data flow
- API / connector choices
- Error-handling strategy
- Security considerations
- Architecture trade-offs

## Final question

**Where should each responsibility live: identity provider, application, iPaaS, ETL pipeline, or target system?**
