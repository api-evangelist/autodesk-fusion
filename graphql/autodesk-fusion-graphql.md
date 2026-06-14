# Autodesk Fusion GraphQL API

## Description

Autodesk Fusion exposes design and manufacturing data through the **Manufacturing Data Model API** (also called the Fusion Data API), a native GraphQL interface built on Autodesk Platform Services (APS). It provides cloud-based read and write access to component properties, Bill of Materials structure, model hierarchy, parameters, physical properties, and thumbnail assets — all without requiring the Fusion desktop application to be running.

The API reached General Availability in 2022 and is versioned at v2 (with v1 still supported). It uses standard APS OAuth 2.0 (3-legged or 2-legged) for authentication.

## Endpoint

| Version | Endpoint URL |
|---------|-------------|
| v2 (current) | `https://developer.api.autodesk.com/mfg/v3/graphql/public` |
| v1 (legacy) | `https://developer.api.autodesk.com/mfg/v1/graphql` |

## Documentation

- Overview: https://aps.autodesk.com/en/docs/mfgdataapi/v1/developers_guide/about-graphql
- Interactive Explorer (v2): https://aps.autodesk.com/en/docs/mfgdataapi/v2/developers_guide/explorer/
- Samples repository: https://github.com/autodesk-platform-services/aps-fusion-data-samples
- APS Developer Portal: https://aps.autodesk.com/developer/overview/autodesk-fusion-api

## Authentication

All requests require an APS OAuth 2.0 Bearer token passed as `Authorization: Bearer <token>`.

- Scope required: `data:read` (read), `data:write` (mutations)
- Auth docs: https://aps.autodesk.com/en/docs/oauth/v2/developers_guide/basics

## GraphQL Support Notes

- **Native GraphQL**: Autodesk provides a first-party GraphQL endpoint — this is not a wrapper or community schema.
- **Interactive Explorer**: A browser-based schema explorer and query console is available in the APS developer portal (v2).
- **Introspection**: Introspection is enabled on the public endpoint, so tooling such as GraphQL Playground and Postman can fetch the live schema.
- **Subscriptions**: Not documented as available; the API is query/mutation only.
- **Pagination**: Cursor-based pagination using `pageInfo { hasNextPage, endCursor }` on connection types.
- **Design scope**: The schema covers the Fusion data model — hubs, projects, items/versions, components, occurrences, B-Rep topology, sketches, timeline features, parameters, materials, joints, assemblies, CAM operations, simulations, renders, and exports.
- **Fusion Operations** (MES) uses a separate REST API and does not share this GraphQL endpoint.
