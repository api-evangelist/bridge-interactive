# Bridge Interactive (bridge-interactive)

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
