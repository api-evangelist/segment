# Segment (segment)
Segment, now part of Twilio, is a customer data platform that collects, unifies, and routes user event data to hundreds of analytics and marketing tools. Their developer platform provides a suite of APIs for managing workspaces, tracking user events, querying unified customer profiles, and configuring data pipelines programmatically.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/segment/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Customer Data, Analytics, Tracking, Profiles, Identity Resolution, Data Integration

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Segment Public API
The Segment Public API allows developers to programmatically manage Segment workspaces and their resources. It supports full CRUD operations for sources, destinations, warehouses, tracking plans, and catalog entries. The API follows REST conventions with standard HTTP methods and predictable resource-oriented URLs. It is available for Team and Business tier customers and is the recommended API going forward, replacing the older Config API.

**Human URL:** [https://docs.segmentapis.com/](https://docs.segmentapis.com/)


#### Tags:

 - Customer Data, Analytics, Workspace Management, Sources, Destinations

#### Properties

- [Documentation](https://docs.segmentapis.com/)
- [OpenAPI](openapi/segment-public-api-openapi.yml)

### Segment HTTP Tracking API
The Segment HTTP Tracking API enables developers to record analytics data from any website or application by sending HTTP requests directly to Segment servers. It supports identify, track, page, screen, group, and alias calls, and Segment routes the collected data to configured destinations. The API accepts batch requests up to 500 KB and requires each payload to include a userId or anonymousId. It is a server-side alternative to Segment's client-side SDKs.

**Human URL:** [https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api)


#### Tags:

 - Analytics, Tracking, Events, Customer Data

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api)
- [OpenAPI](openapi/segment-http-tracking-api-openapi.yml)
- [AsyncAPI](asyncapi/segment-webhooks-asyncapi.yml)

### Segment Profile API
The Segment Profile API provides a single endpoint to read user-level and account-level customer data from Segment Unify. Developers can query the entire user or account object programmatically, including external IDs, traits, and events that make up a user's journey. The API uses basic authentication and typically delivers p95 response times under 200ms for the traits endpoint. It is commonly used for real-time personalization and customer data retrieval.

**Human URL:** [https://www.twilio.com/docs/segment/unify/profile-api](https://www.twilio.com/docs/segment/unify/profile-api)


#### Tags:

 - Customer Data, Profiles, Identity Resolution, Unify

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/unify/profile-api)
- [OpenAPI](openapi/segment-profile-api-openapi.yml)

### Segment Config API
The Segment Config API allows programmatic management of Segment workspaces, sources, destinations, and other configuration resources. It provides endpoints to list workspace sources and destinations, create or delete destinations, and manage tracking plans. As of early 2024, Segment has stopped issuing new Config API tokens and recommends migrating to the Public API for access to the latest features. The Config API remains functional for existing users but is no longer actively developed.

**Human URL:** [https://www.twilio.com/docs/segment/api/config-api](https://www.twilio.com/docs/segment/api/config-api)


#### Tags:

 - Configuration, Workspace Management, Sources, Destinations, Legacy

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/api/config-api)
- [OpenAPI](openapi/segment-config-api-openapi.yml)

### Segment Pixel Tracking API
The Segment Pixel Tracking API provides a way to collect analytics data using image pixel requests, which is useful in environments where JavaScript cannot execute, such as email clients. It supports identify, track, page, screen, group, and alias calls through pixel endpoints under the api.segment.io domain. This API is particularly suited for tracking email opens, ad impressions, and other contexts where embedding a tracking pixel is the only viable data collection method.

**Human URL:** [https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api)


#### Tags:

 - Tracking, Analytics, Pixel, Email

#### Properties

- [Documentation](https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/pixel-tracking-api)
- [OpenAPI](openapi/segment-pixel-tracking-api-openapi.yml)

## Common Properties

- [Portal](https://www.twilio.com/docs/segment)
- [Documentation](https://docs.segmentapis.com/)
- [Website](https://segment.com/)
- [PrivacyPolicy](https://www.twilio.com/en-us/legal/privacy)
- [TermsOfService](https://www.twilio.com/en-us/legal/tos)
- [Support](https://segment.com/help/articles/)
- [Blog](https://segment.com/blog/)
- [Login](https://app.segment.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
