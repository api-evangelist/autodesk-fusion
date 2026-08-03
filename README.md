# Autodesk Fusion (autodesk-fusion)

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
