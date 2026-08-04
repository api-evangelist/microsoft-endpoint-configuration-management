# Microsoft Endpoint Configuration Management (microsoft-endpoint-configuration-management)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Microsoft Endpoint Configuration Management (formerly System Center Configuration Manager) provides comprehensive management of devices and applications across an enterprise. It enables IT administrators to manage PCs, servers, and mobile devices, deploy software, manage compliance, and protect data.

**APIs.json:** [https://learn.microsoft.com/en-us/intune/configmgr/](https://learn.microsoft.com/en-us/intune/configmgr/)

## Tags

- Compliance
- Configuration Management
- Device Management
- Endpoint Management
- Mobile Device Management
- Patch Management
- Software Deployment

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Configuration Manager REST API

REST API for managing Configuration Manager resources including collections, deployments, applications, and device queries. The administration service is based on the OData v4 protocol and supports both WMI and versioned OData routes.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/overview](https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/overview)
- **Base URL:** `https://{siteserver}/AdminService`

#### Tags

- Admin Service
- Configuration Manager
- REST API

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/overview)
- [Getting Started](https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/set-up)
- [OpenAPI](openapi/microsoft-endpoint-configuration-management-configmgr-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/set-up#enable-secure-https-communication)
- [Reference](https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/usage)
- [Changelog](https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/release-notes)

### Configuration Manager PowerShell Cmdlets

PowerShell module for Configuration Manager automation and scripting, providing over 1100 cmdlets for all major management tasks including device collections, software deployment, and compliance settings.

- **Human URL:** [https://learn.microsoft.com/en-us/powershell/sccm/overview?view=sccm-ps](https://learn.microsoft.com/en-us/powershell/sccm/overview?view=sccm-ps)

#### Tags

- Automation
- Configuration Manager
- PowerShell
- Scripting

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/powershell/sccm/overview?view=sccm-ps)
- [Reference](https://learn.microsoft.com/en-us/powershell/module/configurationmanager/?view=sccm-ps)
- [Getting Started](https://learn.microsoft.com/en-us/intune/configmgr/core/servers/manage/admin-console)
- [Changelog](https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/changes/whats-new-incremental-versions)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Configuration Manager SDK

Software Development Kit for extending and integrating with Configuration Manager, including WMI providers, class schemas, and programming interfaces for custom solutions.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/configmgr/develop/](https://learn.microsoft.com/en-us/intune/configmgr/develop/)

#### Tags

- Configuration Manager
- Development
- SDK
- WMI

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/intune/configmgr/develop/)
- [Reference](https://learn.microsoft.com/en-us/intune/configmgr/develop/reference/configuration-manager-reference)
- [Getting Started](https://learn.microsoft.com/en-us/intune/configmgr/develop/core/understand/getting-started-with-configuration-manager-programming)
- [Changelog](https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/changes/whats-new-incremental-versions)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Intune Graph API

Microsoft Graph API endpoints for Intune device management, enabling programmatic access to manage devices, apps, compliance policies, and configuration profiles. Supports both v1.0 and beta endpoints.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/intune-graph-overview?view=graph-rest-1.0](https://learn.microsoft.com/en-us/graph/api/resources/intune-graph-overview?view=graph-rest-1.0)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Compliance
- Device Management
- Intune
- Microsoft Graph

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/intune-graph-overview?view=graph-rest-1.0)
- [Getting Started](https://learn.microsoft.com/en-us/graph/intune-concept-overview)
- [OpenAPI](openapi/microsoft-endpoint-configuration-management-intune-graph-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/microsoft-endpoint-configuration-management-device-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-endpoint-configuration-management-compliance-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-endpoint-configuration-management-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-endpoint-configuration-management-configuration-profile-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/microsoft-endpoint-configuration-management-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Reference](https://learn.microsoft.com/en-us/graph/intune-concept-overview)
- [Authentication](https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis)
- [Changelog](https://developer.microsoft.com/en-us/graph/changelog)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Postman Collection](https://www.postman.com/microsoftgraph/workspace/microsoft-graph/overview) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

### Intune Data Warehouse API

OData-based REST API that provides access to Intune reporting data in a machine-readable format. Enables building custom reports and analytics for enterprise mobile environment insights.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-nav-intune-data-warehouse](https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-nav-intune-data-warehouse)
- **Base URL:** `https://fef.{location}.manage.microsoft.com/ReportingService/DataWarehouseFEService`

#### Tags

- Data Warehouse
- Intune
- OData
- Reporting

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-nav-intune-data-warehouse)
- [OpenAPI](openapi/microsoft-endpoint-configuration-management-intune-data-warehouse-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-api-url)
- [Authentication](https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis)
- [Reference](https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-proc-data-rest)
- [Changelog](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)

### Intune App SDK

SDKs for iOS and Android that enable mobile apps to support Intune app protection policies. Allows developers to integrate mobile application management features into line-of-business and partner apps.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started)

#### Tags

- App Protection
- Intune
- Mobile Apps
- SDK

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk)
- [Getting Started](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started)
- [Reference](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-ios-phase1)
- [GitHub Organization](https://github.com/msintuneappsdk)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune Reporting Export API

Microsoft Graph API endpoints for exporting Intune reports programmatically. Supports exporting device, compliance, and app management reports in CSV or JSON format using asynchronous export jobs.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis)
- **Base URL:** `https://graph.microsoft.com/v1.0/deviceManagement/reports`

#### Tags

- Export
- Intune
- Microsoft Graph
- Reporting

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis)
- [OpenAPI](openapi/microsoft-endpoint-configuration-management-intune-reporting-export-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Reference](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-available-reports)
- [Authentication](https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis)

### Intune App Wrapping Tool

Command-line tools for iOS and Android that enable existing line-of-business apps to be managed by Intune app protection policies without requiring source code changes.

- **Human URL:** [https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management](https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management)

#### Tags

- Android
- App Protection
- Intune
- iOS
- Mobile Apps

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management)
- [Getting Started](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-wrapper-prepare-ios)
- [Reference](https://learn.microsoft.com/en-us/intune/intune-service/developer/app-wrapper-prepare-android)
- [GitHub Organization](https://github.com/microsoftconnect)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Intune PowerShell SDK

PowerShell module providing native cmdlet support for invoking the Microsoft Intune Graph API. Enables IT administrators to automate device management, app deployment, and compliance policy operations through scripting.

- **Human URL:** [https://github.com/microsoft/Intune-PowerShell-SDK](https://github.com/microsoft/Intune-PowerShell-SDK)

#### Tags

- Automation
- Intune
- PowerShell
- SDK

#### Properties

- [Documentation](https://github.com/microsoft/Intune-PowerShell-SDK)
- [Getting Started](https://github.com/microsoft/mggraph-intune-samples)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdk-installation)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-configmgr-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-data-warehouse-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-graph-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-endpoint-configuration-management-intune-reporting-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://endpoint.microsoft.com/)
- [Console](https://intune.microsoft.com/)
- [Documentation](https://learn.microsoft.com/en-us/intune/intune-service/)
- [Getting Started](https://learn.microsoft.com/en-us/intune/configmgr/core/understand/introduction)
- [Authentication](https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis)
- [Blog](https://techcommunity.microsoft.com/t5/microsoft-endpoint-manager-blog/bg-p/MicrosoftEndpointManagerBlog)
- [Support](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/contact-assisted-support)
- [Status Page](https://status.azure.com/)
- [Changelog](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new)
- [Pricing](https://www.microsoft.com/en-us/security/business/microsoft-intune-pricing)
- [Sign Up](https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/free-trial-sign-up)
- [Login](https://intune.microsoft.com/)
- [Privacy Policy](https://privacy.microsoft.com/)
- [Terms of Service](https://www.microsoft.com/licensing/terms/)
- [GitHub Organization](https://github.com/microsoftgraph)
- [Community](https://techcommunity.microsoft.com/category/microsoftintune/blog/microsoftintuneblog)
- [Website](https://learn.microsoft.com/en-us/intune/configmgr/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
