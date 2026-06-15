# UKG (ukg)

UKG (Ultimate Kronos Group) is an enterprise human capital management (HCM) and workforce management platform serving over 80,000 organizations worldwide. The UKG Pro suite includes HCM APIs for employee data, payroll, benefits, and personnel actions, plus WFM APIs for time and labor management, scheduling, accruals, and attendance. The UKG Developer Hub provides REST APIs, webhook subscriptions, and People Fabric APIs for building HR integrations, payroll connectors, and workforce analytics applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Human Capital Management
- HCM
- Workforce Management
- HR
- Payroll
- Time and Attendance
- Benefits
- Scheduling

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### UKG Pro HCM API

The UKG Pro HCM API provides programmatic access to human capital management data including employees, personnel actions, benefits, payroll, performance, and organizational structure. Uses Basic Authentication with service account credentials and tenant-specific API keys. Enables integrations with HR systems, payroll processors, benefits administrators, and workforce analytics platforms.

- **Human URL:** [https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api](https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api)
- **Base URL:** `https://service.ultipro.com`

#### Tags

- HCM
- Employees
- Payroll
- Benefits
- Personnel Actions

#### Properties

- [Documentation](https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api)
- [OpenAPI](openapi/ukg-pro-hcm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ukg-pro-hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro-hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/pro-hcm-employee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-employee-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-pay-rate-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-benefits-election-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-department-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-location-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-pay-statement-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-direct-deposit-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-personnel-change-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-personnel-change-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-employee-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-hcm-employee-id-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/pro-hcm-employee-structure.json)
- [JSON Structure](json-structure/pro-hcm-employee-job-structure.json)
- [JSON Structure](json-structure/pro-hcm-pay-rate-structure.json)
- [JSON Structure](json-structure/pro-hcm-benefits-election-structure.json)
- [JSON Structure](json-structure/pro-hcm-department-structure.json)
- [JSON Structure](json-structure/pro-hcm-location-structure.json)
- [JSON Structure](json-structure/pro-hcm-pay-statement-structure.json)
- [JSON Structure](json-structure/pro-hcm-direct-deposit-structure.json)
- [JSON Structure](json-structure/pro-hcm-personnel-change-request-structure.json)
- [JSON Structure](json-structure/pro-hcm-personnel-change-response-structure.json)
- [JSON Structure](json-structure/pro-hcm-employee-list-structure.json)
- [JSON Structure](json-structure/pro-hcm-employee-id-list-structure.json)
- [J S O N L D Context](json-ld/ukg-pro-hcm-context.jsonld)
- [Example](examples/pro-hcm-employee-example.json)
- [Example](examples/pro-hcm-employee-job-example.json)
- [Example](examples/pro-hcm-pay-rate-example.json)
- [Example](examples/pro-hcm-benefits-election-example.json)
- [Example](examples/pro-hcm-department-example.json)
- [Example](examples/pro-hcm-location-example.json)
- [Example](examples/pro-hcm-pay-statement-example.json)
- [Example](examples/pro-hcm-direct-deposit-example.json)
- [Example](examples/pro-hcm-personnel-change-request-example.json)
- [Example](examples/pro-hcm-personnel-change-response-example.json)
- [Example](examples/pro-hcm-employee-list-example.json)
- [Example](examples/pro-hcm-employee-id-list-example.json)

### UKG Pro Workforce Management API

The UKG Pro WFM API provides programmatic access to time and labor management data including punches, shifts, schedules, accruals, and attendance. Supports timekeeping, scheduling, and compliance workflows for hourly and salaried employees. Uses OAuth 2.0 with tenant API keys.

- **Human URL:** [https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api](https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api)
- **Base URL:** `https://api.ultipro.com/workforce/v1`

#### Tags

- Workforce Management
- Time and Attendance
- Scheduling
- Accruals
- Timekeeping

#### Properties

- [Documentation](https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api)
- [OpenAPI](openapi/ukg-pro-wfm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ukg-pro-wfm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro-wfm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/pro-wfm-wfm-employee-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-wfm-timecard-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-wfm-punch-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-wfm-punch-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-wfm-accrual-balance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pro-wfm-shift-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/pro-wfm-wfm-employee-structure.json)
- [JSON Structure](json-structure/pro-wfm-timecard-structure.json)
- [JSON Structure](json-structure/pro-wfm-punch-structure.json)
- [JSON Structure](json-structure/pro-wfm-punch-request-structure.json)
- [JSON Structure](json-structure/pro-wfm-accrual-balance-structure.json)
- [JSON Structure](json-structure/pro-wfm-shift-structure.json)
- [J S O N L D Context](json-ld/ukg-pro-wfm-context.jsonld)
- [Example](examples/pro-wfm-wfm-employee-example.json)
- [Example](examples/pro-wfm-timecard-example.json)
- [Example](examples/pro-wfm-punch-example.json)
- [Example](examples/pro-wfm-punch-request-example.json)
- [Example](examples/pro-wfm-accrual-balance-example.json)
- [Example](examples/pro-wfm-shift-example.json)

### UKG HR Service Delivery API

The UKG HR Service Delivery API (formerly People Doc) provides access to employee request management, knowledge portal content, process automation, document storage, and compliance workflows. Enables HR case management integrations and employee self-service applications.

- **Human URL:** [https://doc.people-doc.com/api/?urls.primaryName=Client](https://doc.people-doc.com/api/?urls.primaryName=Client)
- **Base URL:** `https://api.people-doc.com`

#### Tags

- HR Service Delivery
- Case Management
- Document Management
- Employee Requests

#### Properties

- [Documentation](https://doc.people-doc.com/api/?urls.primaryName=Client)
- [API Reference](https://doc.people-doc.com/client/api/index-v2.html)
- [Postman Collection](collections/ukg-pro-hcm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro-hcm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ukg-pro-wfm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro-wfm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [GitHub Organization](https://github.com/ultimatesoftware)
- [LinkedIn](https://www.linkedin.com/company/ukg)
- [Website](https://www.ukg.com)
- [Documentation](https://developer.ukg.com)
- [Portal](https://developer.ukg.com)
- [Blog](https://www.ukg.com/blog)
- [Pricing](https://www.ukg.com/pricing)
- [Terms of Service](https://www.ukg.com/legal/terms)
- [Privacy Policy](https://www.ukg.com/legal/privacy-policy)
- [Support](https://support.ukg.com)
- [Getting Started](https://developer.ukg.com/general/docs/getting-started)
- [Authentication](https://developer.ukg.com/hcm/docs/authentication)
- [Sign Up](https://www.ukg.com/contact-us)
- [Spectral Rules](rules/ukg-spectral-rules.yml)
- [Vocabulary](vocabulary/ukg-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
