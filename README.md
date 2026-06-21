# Bridge Interactive (bridge-interactive)

Bridge Interactive (a Zillow Group company) is a real-estate data-access platform that normalizes MLS listing data to RESO standards and serves it through the Bridge API. The Bridge Data Output platform exposes a proprietary RESTful Bridge Web API and a RESO-compliant RESO Web API (OData) for properties, members, offices, open houses, and media, all secured with a Bearer server token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bridge-interactive/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bridge-interactive/refs/heads/main/apis.yml)

## Tags

- Real Estate
- MLS
- RESO
- Listings
- Property Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Bridge Listings and Properties API

Query normalized real-estate listings and property records for a dataset via the proprietary Bridge Web API, with field selection, sorting, near (geo) search, and per-field filter operators (eq, ne, gt, lt, gte, lte).

- **Human URL:** [https://bridgedataoutput.com/docs/platform/API/bridge](https://bridgedataoutput.com/docs/platform/API/bridge)
- **Base URL:** `https://api.bridgedataoutput.com/api/v2`

#### Tags

- Listings
- Property
- Real Estate

#### Properties

- [Documentation](https://bridgedataoutput.com/docs/platform/API/bridge)
- [API Reference](https://bridgedataoutput.com/docs/platform/API)
- [OpenAPI](openapi/bridge-interactive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridge-interactive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridge-interactive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bridge Agents API

Retrieve agent (RESO Member) records for a dataset, including name, contact, license, and office association, with filtering and field selection.

- **Human URL:** [https://bridgedataoutput.com/docs/platform/API/bridge](https://bridgedataoutput.com/docs/platform/API/bridge)
- **Base URL:** `https://api.bridgedataoutput.com/api/v2`

#### Tags

- Agents
- Members
- Real Estate

#### Properties

- [Documentation](https://bridgedataoutput.com/docs/platform/API/bridge)
- [OpenAPI](openapi/bridge-interactive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridge-interactive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridge-interactive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bridge Offices API

Retrieve brokerage office (RESO Office) records for a dataset, including office name, address, and contact, filterable by location and other fields.

- **Human URL:** [https://bridgedataoutput.com/docs/platform/API/bridge](https://bridgedataoutput.com/docs/platform/API/bridge)
- **Base URL:** `https://api.bridgedataoutput.com/api/v2`

#### Tags

- Offices
- Brokerages
- Real Estate

#### Properties

- [Documentation](https://bridgedataoutput.com/docs/platform/API/bridge)
- [OpenAPI](openapi/bridge-interactive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridge-interactive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridge-interactive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bridge Open Houses API

Retrieve scheduled open house (RESO OpenHouse) records for a dataset, including date, time window, and the associated listing.

- **Human URL:** [https://bridgedataoutput.com/docs/platform/API/bridge](https://bridgedataoutput.com/docs/platform/API/bridge)
- **Base URL:** `https://api.bridgedataoutput.com/api/v2`

#### Tags

- Open Houses
- Events
- Real Estate

#### Properties

- [Documentation](https://bridgedataoutput.com/docs/platform/API/bridge)
- [OpenAPI](openapi/bridge-interactive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridge-interactive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridge-interactive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bridge Media API

Retrieve listing media (RESO Media) records such as photos and virtual tours, available as a RESO resource and via $expand on Property.

- **Human URL:** [https://bridgedataoutput.com/docs/explorer/reso-web-api](https://bridgedataoutput.com/docs/explorer/reso-web-api)
- **Base URL:** `https://api.bridgedataoutput.com/api/v2`

#### Tags

- Media
- Photos
- Real Estate

#### Properties

- [Documentation](https://bridgedataoutput.com/docs/explorer/reso-web-api)
- [OpenAPI](openapi/bridge-interactive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridge-interactive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridge-interactive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bridge RESO Web API

RESO Data Dictionary-aligned OData endpoints (Property, Member, Office, OpenHouse, Media) with $filter, $select, $top, $skip, $orderby, $expand, a $metadata service document, and a replication endpoint for full extracts.

- **Human URL:** [https://bridgedataoutput.com/docs/explorer/reso-web-api](https://bridgedataoutput.com/docs/explorer/reso-web-api)
- **Base URL:** `https://api.bridgedataoutput.com/api/v2`

#### Tags

- RESO
- OData
- Web API

#### Properties

- [Documentation](https://bridgedataoutput.com/docs/explorer/reso-web-api)
- [API Reference](https://bridgedataoutput.com/docs/platform/API)
- [OpenAPI](openapi/bridge-interactive-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bridge-interactive.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bridge-interactive.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bridge-interactive)
- [Website](https://www.bridgeinteractive.com)
- [Documentation](https://bridgedataoutput.com/docs/platform/)
- [Plans](plans/bridge-interactive-plans-pricing.yml)
- [Rate Limits](rate-limits/bridge-interactive-rate-limits.yml)
- [Fin Ops](finops/bridge-interactive-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
