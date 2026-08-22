# UKG (ukg)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
