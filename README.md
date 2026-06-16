# Autodesk Fusion (autodesk-fusion)

Autodesk Fusion is a cloud-based CAD/CAM/CAE/PCB platform that provides REST and GraphQL APIs for design data access, manufacturing automation, simulation, and shop-floor operations within the Autodesk Platform Services (APS) ecosystem. Developers can build scripts, add-ins, and integrations that automate workflows, sync production data, and connect Fusion with ERP, PLM, and BI systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/autodesk-fusion/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/autodesk-fusion/refs/heads/main/apis.yml)

## Tags

- CAD
- CAM
- CAE
- Manufacturing
- Design Automation
- GraphQL
- REST
- Autodesk Platform Services

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Autodesk Fusion API

The Autodesk Fusion API enables developers to create scripts, add-ins, and cloud-connected applications that extend and automate Fusion design and manufacturing workflows. Built on Autodesk Platform Services, it supports OAuth 2.0 authentication and covers the entire design-to-manufacturing process including parametric modeling, simulation, and toolpath generation.

- **Human URL:** [https://aps.autodesk.com/developer/overview/autodesk-fusion-api](https://aps.autodesk.com/developer/overview/autodesk-fusion-api)
- **Base URL:** `https://developer.api.autodesk.com`

#### Tags

- CAD
- Scripting
- Design
- Automation

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/autodesk-fusion-api)
- [Documentation](https://help.autodesk.com/view/fusion360/ENU/?guid=GUID-A92A4B10-3781-4925-94C6-47DA85A4F65A)
- [Authentication](https://aps.autodesk.com/en/docs/oauth/v2/developers_guide/basics)
- [OpenAPI](https://github.com/autodesk-platform-services/aps-sdk-openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Graph Q L](graphql/autodesk-fusion-graphql.md)

### Fusion Automation API (Design Automation)

The Fusion Automation API is a cloud-based Premium API that runs Fusion scripts and automation jobs at scale without requiring desktop software. It supports parametric design customization, advanced manufacturing algorithms (packing, toolpath generation), and end-to-end workflow integration. Priced at 3.0 Flex tokens per processing hour on a pay-per-use basis.

- **Human URL:** [https://aps.autodesk.com/blog/design-automation-api-fusion-now-generally-available](https://aps.autodesk.com/blog/design-automation-api-fusion-now-generally-available)
- **Base URL:** `https://developer.api.autodesk.com`

#### Tags

- Design Automation
- Cloud
- Manufacturing
- Flex Tokens

#### Properties

- [Documentation](https://aps.autodesk.com/en/docs/design-automation/v3/developers_guide/overview/)
- [Authentication](https://aps.autodesk.com/en/docs/oauth/v2/developers_guide/basics)
- [Pricing](https://aps.autodesk.com/pricing)

### Fusion Operations API

The Fusion Operations API provides REST endpoints to integrate Autodesk Fusion Operations (manufacturing execution system) production data with external enterprise systems. Supports bidirectional sync of production orders, inventory, machine status, downtime records, punch clock entries, workers, and operations with ERP, PLM, accounting, and BI platforms. Currently in Public Beta (V2).

- **Human URL:** [https://aps.autodesk.com/developer/overview/fusion-operations-api](https://aps.autodesk.com/developer/overview/fusion-operations-api)
- **Base URL:** `https://developer.api.autodesk.com`

#### Tags

- Manufacturing Execution
- ERP Integration
- Production Data
- Shop Floor

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/fusion-operations-api)
- [Documentation](https://aps.autodesk.com/en/docs/fusion-operations/v2/developers_guide/overview/)
- [Authentication](https://aps.autodesk.com/en/docs/oauth/v2/developers_guide/basics)

### Manufacturing Data Model API (Fusion Data API)

The Manufacturing Data Model API exposes Fusion design and manufacturing data through a GraphQL interface, enabling cloud-based read and write access to component properties, Bill of Materials, model hierarchy, and thumbnail assets. Allows programmatic access to granular design data without requiring the Fusion desktop application. Generally available since 2022.

- **Human URL:** [https://aps.autodesk.com/en/docs/mfgdataapi/v2/developers_guide/explorer/](https://aps.autodesk.com/en/docs/mfgdataapi/v2/developers_guide/explorer/)
- **Base URL:** `https://developer.api.autodesk.com/mfg/v3/graphql/public`

#### Tags

- GraphQL
- Manufacturing Data
- Design Data
- Bill of Materials

#### Properties

- [Documentation](https://aps.autodesk.com/en/docs/mfgdataapi/v1/developers_guide/about-graphql)
- [Documentation](https://aps.autodesk.com/en/docs/mfgdataapi/v2/developers_guide/explorer/)
- [Authentication](https://aps.autodesk.com/en/docs/oauth/v2/developers_guide/basics)
- [GitHub Repository](https://github.com/autodesk-platform-services/aps-fusion-data-samples)

## Common Properties

- [Website](https://www.autodesk.com/products/fusion-360/overview)
- [Documentation](https://aps.autodesk.com/developer/documentation)
- [Git Hub Org](https://github.com/autodesk-platform-services)
- [LinkedIn](https://www.linkedin.com/company/autodesk)
- [Blog](https://aps.autodesk.com/blog)
- [Blog](https://www.autodesk.com/products/fusion-360/blog)
- [Pricing](https://www.autodesk.com/products/fusion-360/overview)
- [Status Page](https://health.autodesk.com)
- [X (Twitter)](https://x.com/autodeskaps)
- [Plans](plans/autodesk-fusion-plans-pricing.yml)
- [Rate Limits](rate-limits/autodesk-fusion-rate-limits.yml)
- [Fin Ops](finops/autodesk-fusion-finops.yml)
- [Authentication](https://aps.autodesk.com/developer/overview/authentication-api)
- [Forum](https://forums.autodesk.com/t5/fusion-api-and-scripts-forum/bd-p/22)
- [OpenAPI](https://github.com/autodesk-platform-services/aps-sdk-openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
