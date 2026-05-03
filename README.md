# UKG

UKG (Ultimate Kronos Group) is an enterprise human capital management (HCM) and workforce management platform serving over 80,000 organizations worldwide. The UKG Pro suite includes HCM APIs for employee data, payroll, benefits, and personnel actions, plus WFM APIs for time and labor management, scheduling, accruals, and attendance.

**Run: [Capabilities Using Naftiko](https://naftiko.com)**

**URL:** [https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/apis.yml)

## APIs

### UKG Pro HCM API

The UKG Pro HCM API provides programmatic access to human capital management data including employees, personnel actions, benefits, payroll, performance, and organizational structure. Uses Basic Authentication with service account credentials and tenant-specific API keys.

**Human URL:** [https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api](https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api)

**Base URL:** https://service.ultipro.com

**Tags:** HCM, Employees, Payroll, Benefits, Personnel Actions

**Properties:**

| Type | URL |
|------|-----|
| Documentation | [https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api](https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api) |
| OpenAPI | [openapi/ukg-pro-hcm-openapi.yml](openapi/ukg-pro-hcm-openapi.yml) |

### UKG Pro Workforce Management API

The UKG Pro WFM API provides programmatic access to time and labor management data including punches, shifts, schedules, accruals, and attendance. Supports timekeeping, scheduling, and compliance workflows for hourly and salaried employees. Uses OAuth 2.0 with tenant API keys.

**Human URL:** [https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api](https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api)

**Base URL:** https://api.ultipro.com/workforce/v1

**Tags:** Workforce Management, Time and Attendance, Scheduling, Accruals, Timekeeping

**Properties:**

| Type | URL |
|------|-----|
| Documentation | [https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api](https://developer.ukg.com/wfm/reference/welcome-to-the-ukg-pro-workforce-management-api) |
| OpenAPI | [openapi/ukg-pro-wfm-openapi.yml](openapi/ukg-pro-wfm-openapi.yml) |

### UKG HR Service Delivery API

The UKG HR Service Delivery API (formerly People Doc) provides access to employee request management, knowledge portal content, process automation, document storage, and compliance workflows. Enables HR case management integrations and employee self-service applications.

**Human URL:** [https://doc.people-doc.com/api/?urls.primaryName=Client](https://doc.people-doc.com/api/?urls.primaryName=Client)

**Base URL:** https://api.people-doc.com

**Tags:** HR Service Delivery, Case Management, Document Management, Employee Requests

**Properties:**

| Type | URL |
|------|-----|
| Documentation | [https://doc.people-doc.com/api/?urls.primaryName=Client](https://doc.people-doc.com/api/?urls.primaryName=Client) |
| API Reference | [https://doc.people-doc.com/client/api/index-v2.html](https://doc.people-doc.com/client/api/index-v2.html) |

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://www.ukg.com](https://www.ukg.com) |
| Documentation | [https://developer.ukg.com](https://developer.ukg.com) |
| Portal | [https://developer.ukg.com](https://developer.ukg.com) |
| Blog | [https://www.ukg.com/blog](https://www.ukg.com/blog) |
| Pricing | [https://www.ukg.com/pricing](https://www.ukg.com/pricing) |
| Terms of Service | [https://www.ukg.com/legal/terms](https://www.ukg.com/legal/terms) |
| Privacy Policy | [https://www.ukg.com/legal/privacy-policy](https://www.ukg.com/legal/privacy-policy) |
| Support | [https://support.ukg.com](https://support.ukg.com) |
| Getting Started | [https://developer.ukg.com/general/docs/getting-started](https://developer.ukg.com/general/docs/getting-started) |
| Authentication | [https://developer.ukg.com/hcm/docs/authentication](https://developer.ukg.com/hcm/docs/authentication) |
| Signup | [https://www.ukg.com/contact-us](https://www.ukg.com/contact-us) |

## Features

| Name | Description |
|------|-------------|
| Human Capital Management | Comprehensive HCM covering employee records, org management, talent, and compliance for enterprise organizations. |
| Payroll Processing | Full-service payroll with tax compliance, direct deposit, pay statements, and multi-state support. |
| Benefits Administration | Benefits enrollment, plan management, life event processing, and ACA compliance tracking. |
| Time and Attendance | Automated timekeeping with punch clocks, mobile entry, approval workflows, and FLSA compliance. |
| Workforce Scheduling | AI-powered scheduling with demand forecasting, shift management, and coverage optimization. |
| Accrual Management | Configurable vacation, sick, and PTO accrual policies with automated balance tracking. |
| HR Service Delivery | Employee case management, knowledge portal, HR document management, and process automation. |
| People Fabric | Unified data platform connecting HCM and WFM data across all UKG products via modern APIs. |

## Use Cases

| Name | Description |
|------|-------------|
| Payroll Integration | Sync employee pay data, deductions, and tax information with third-party payroll processors and ERP systems. |
| Benefits Connector | Exchange enrollment data and eligibility with benefits carriers, insurance providers, and benefits administration systems. |
| Time and Labor Integration | Import punch data, approved timecards, and schedule information into payroll and workforce analytics platforms. |
| HRIS Data Sync | Keep employee demographic, job, and organizational data synchronized between UKG and downstream business systems. |
| Analytics and Reporting | Export workforce data to business intelligence tools and data warehouses for advanced analytics and reporting. |
| Onboarding Automation | Automate new hire provisioning by triggering downstream system access and equipment setup from UKG hire events. |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Sync employee data between UKG and Salesforce for HR-CRM alignment. |
| SAP | Integrate with SAP ERP for GL posting, cost center management, and financial reconciliation. |
| Microsoft Azure AD | Single sign-on and user provisioning integration with Microsoft Entra ID. |
| Workday | Employee data exchange for organizations using both platforms during migration or hybrid scenarios. |
| ADP | Payroll data exchange with ADP for organizations using both HCM and payroll platforms. |
| Greenhouse | Applicant tracking system integration for recruiting and onboarding handoff. |

## Solutions

| Name | Description |
|------|-------------|
| UKG Pro | Enterprise HCM platform for mid-market and enterprise organizations with full HR, payroll, and talent capabilities. |
| UKG Pro WFM | Workforce management platform for hourly and complex workforce scheduling, timekeeping, and compliance. |
| UKG Ready | Simplified HCM solution for small and medium businesses with combined HR, payroll, and time management. |
| UKG HR Service Delivery | Employee experience platform for HR case management, knowledge delivery, and document compliance. |

## Artifacts

### OpenAPI Specs

| Name | URL |
|------|-----|
| UKG Pro HCM API | [openapi/ukg-pro-hcm-openapi.yml](openapi/ukg-pro-hcm-openapi.yml) |
| UKG Pro WFM API | [openapi/ukg-pro-wfm-openapi.yml](openapi/ukg-pro-wfm-openapi.yml) |

### JSON Schema

| Name | URL |
|------|-----|
| Employee | [json-schema/pro-hcm-employee-schema.json](json-schema/pro-hcm-employee-schema.json) |
| Employee List | [json-schema/pro-hcm-employee-list-schema.json](json-schema/pro-hcm-employee-list-schema.json) |
| Employee Job | [json-schema/pro-hcm-employee-job-schema.json](json-schema/pro-hcm-employee-job-schema.json) |
| Pay Rate | [json-schema/pro-hcm-pay-rate-schema.json](json-schema/pro-hcm-pay-rate-schema.json) |
| Benefits Election | [json-schema/pro-hcm-benefits-election-schema.json](json-schema/pro-hcm-benefits-election-schema.json) |
| Department | [json-schema/pro-hcm-department-schema.json](json-schema/pro-hcm-department-schema.json) |
| Location | [json-schema/pro-hcm-location-schema.json](json-schema/pro-hcm-location-schema.json) |
| Pay Statement | [json-schema/pro-hcm-pay-statement-schema.json](json-schema/pro-hcm-pay-statement-schema.json) |
| Direct Deposit | [json-schema/pro-hcm-direct-deposit-schema.json](json-schema/pro-hcm-direct-deposit-schema.json) |
| Personnel Change Request | [json-schema/pro-hcm-personnel-change-request-schema.json](json-schema/pro-hcm-personnel-change-request-schema.json) |
| WFM Employee | [json-schema/pro-wfm-wfm-employee-schema.json](json-schema/pro-wfm-wfm-employee-schema.json) |
| Timecard | [json-schema/pro-wfm-timecard-schema.json](json-schema/pro-wfm-timecard-schema.json) |
| Punch | [json-schema/pro-wfm-punch-schema.json](json-schema/pro-wfm-punch-schema.json) |
| Accrual Balance | [json-schema/pro-wfm-accrual-balance-schema.json](json-schema/pro-wfm-accrual-balance-schema.json) |
| Shift | [json-schema/pro-wfm-shift-schema.json](json-schema/pro-wfm-shift-schema.json) |

### JSON-LD Contexts

| Name | URL |
|------|-----|
| UKG Pro HCM Context | [json-ld/ukg-pro-hcm-context.jsonld](json-ld/ukg-pro-hcm-context.jsonld) |
| UKG Pro WFM Context | [json-ld/ukg-pro-wfm-context.jsonld](json-ld/ukg-pro-wfm-context.jsonld) |

## Capabilities

### Shared Definitions

| Name | URL |
|------|-----|
| UKG Pro HCM | [capabilities/shared/pro-hcm.yaml](capabilities/shared/pro-hcm.yaml) |
| UKG Pro WFM | [capabilities/shared/pro-wfm.yaml](capabilities/shared/pro-wfm.yaml) |

### Workflow Compositions

| Name | Description | URL |
|------|-------------|-----|
| Workforce Management | Timekeeping, scheduling, and accrual management workflow | [capabilities/workforce-management.yaml](capabilities/workforce-management.yaml) |
| HR Administration | Employee records, benefits, and payroll management workflow | [capabilities/hr-administration.yaml](capabilities/hr-administration.yaml) |

## Vocabulary

| Name | URL |
|------|-----|
| UKG API Vocabulary | [vocabulary/ukg-vocabulary.yaml](vocabulary/ukg-vocabulary.yaml) |

## Rules

| Name | URL |
|------|-----|
| UKG Spectral Rules | [rules/ukg-spectral-rules.yml](rules/ukg-spectral-rules.yml) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
