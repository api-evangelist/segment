# segment (segment)

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
