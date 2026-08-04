# segment (segment)

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

Segment is a customer data platform that helps companies collect, clean, and route customer data to hundreds of tools used for analytics, marketing, and data warehousing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Segment Public API

The Segment Public API allows developers to programmatically manage Segment workspaces and their resources. It supports full CRUD operations for sources, destinations, warehouses, tracking plans, and catalog entries. The API follows REST conventions with standard HTTP methods and predictable resource-oriented URLs. It is available for Team and Business tier customers and is the recommended API going forward, replacing the older Config API.

- **Human URL:** [https://docs.segmentapis.com/](https://docs.segmentapis.com/)
- **Base URL:** `https://api.segmentapis.com`

#### Tags

- Analytics
- Customer Data
- Destinations
- Sources
- Workspace Management

#### Properties

- [Documentation](https://docs.segmentapis.com/)
- [OpenAPI](openapi/segment-public-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segment-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segment-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Segment HTTP Tracking API

The Segment HTTP Tracking API enables developers to record analytics data from any website or application by sending HTTP requests directly to Segment servers. It supports identify, track, page, screen, group, and alias calls, and Segment routes the collected data to configured destinations. The API accepts batch requests up to 500 KB and requires each payload to include a userId or anonymousId. It is a server-side alternative to Segment's client-side SDKs.

- **Human URL:** [https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api)
- **Base URL:** `https://api.segment.io`

#### Tags

- Analytics
- Customer Data
- Events
- Tracking

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api)
- [OpenAPI](openapi/segment-http-tracking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segment-http-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segment-http-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/segment-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Segment Profile API

The Segment Profile API provides a single endpoint to read user-level and account-level customer data from Segment Unify. Developers can query the entire user or account object programmatically, including external IDs, traits, and events that make up a user's journey. The API uses basic authentication and typically delivers p95 response times under 200ms for the traits endpoint. It is commonly used for real-time personalization and customer data retrieval.

- **Human URL:** [https://www.twilio.com/docs/segment/unify/profile-api](https://www.twilio.com/docs/segment/unify/profile-api)
- **Base URL:** `https://profiles.segment.com`

#### Tags

- Customer Data
- Identity Resolution
- Profiles
- Unify

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/unify/profile-api)
- [OpenAPI](openapi/segment-profile-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segment-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segment-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Segment Config API

The Segment Config API allows programmatic management of Segment workspaces, sources, destinations, and other configuration resources. It provides endpoints to list workspace sources and destinations, create or delete destinations, and manage tracking plans. As of early 2024, Segment has stopped issuing new Config API tokens and recommends migrating to the Public API for access to the latest features. The Config API remains functional for existing users but is no longer actively developed.

- **Human URL:** [https://www.twilio.com/docs/segment/api/config-api](https://www.twilio.com/docs/segment/api/config-api)
- **Base URL:** `https://platform.segmentapis.com`

#### Tags

- Configuration
- Destinations
- Legacy
- Sources
- Workspace Management

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/api/config-api)
- [OpenAPI](openapi/segment-config-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segment-config-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segment-config-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Segment Pixel Tracking API

The Segment Pixel Tracking API provides a way to collect analytics data using image pixel requests, which is useful in environments where JavaScript cannot execute, such as email clients. It supports identify, track, page, screen, group, and alias calls through pixel endpoints under the api.segment.io domain. This API is particularly suited for tracking email opens, ad impressions, and other contexts where embedding a tracking pixel is the only viable data collection method.

- **Human URL:** [https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api)
- **Base URL:** `https://api.segment.io`

#### Tags

- Analytics
- Email
- Pixel
- Tracking

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api)
- [OpenAPI](openapi/segment-pixel-tracking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/segment-pixel-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/segment-pixel-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/segmentio)
- [LinkedIn](https://www.linkedin.com/company/segment-io)
- [JSON-LD](json-ld/segment-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/segment-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/segment-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/segment-destination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
