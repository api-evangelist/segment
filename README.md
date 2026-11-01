# Twilio Segment

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Twilio Segment is a customer data platform that collects, cleans, and routes customer data to hundreds of downstream tools for analytics, marketing, and data warehousing. Its surface spans event collection (the HTTP Tracking API with identify, track, page, screen, group and alias calls, plus a pixel endpoint for environments where JavaScript cannot run), a Public API for programmatic management of workspaces, sources, destinations, warehouses, tracking plans, functions and transformations, Unify for identity resolution, Engage for audiences, Protocols for tracking-plan governance, Reverse ETL for warehouse-to-tool syncs, and connections to 90+ warehouses including BigQuery, Snowflake and Databricks. Segment was acquired by Twilio in a $3.2B all-stock deal completed in 2020 and now sits inside Twilio's platform; Twilio completed an operational review in March 2024 and retained the business despite activist-investor pressure to divest. The docs, pricing and legal pages have moved onto twilio.com, and the legacy Segment Analytics libraries for iOS and Android reached full sunset on 2026-03-31. The older Config API is deprecated — no new tokens have been issued since early 2024 — with the Public API as the recommended replacement. The Public API host is authenticated: api.segmentapis.com returns 401 anonymously, and no OpenAPI is publicly fetchable (see x-evidence).

**Areas:** Company · Customer Data Platform · CDP · Identity Resolution · Event Streaming · Reverse ETL · Data Pipeline · Customer Data · Analytics · Acquired

## Twilio Segment on APIs.io

Everything profiled for Twilio Segment is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/segment/](https://apis.io/providers/segment/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [segment Alias API](https://apis.io/apis/segment/segment-alias-api/) — Operations for merging two user identities together.
- [segment Batch API](https://apis.io/apis/segment/segment-batch-api/) — Operations for sending multiple calls in a single request.
- [segment Catalog API](https://apis.io/apis/segment/segment-catalog-api/) — Operations for browsing the Segment catalog of available sources and destination integrations.
- [segment Destinations API](https://apis.io/apis/segment/segment-destinations-api/) — Operations for managing destinations where collected data is sent.
- [segment Events API](https://apis.io/apis/segment/segment-events-api/) — Operations for retrieving events associated with a user or account profile.
- [segment External IDs API](https://apis.io/apis/segment/segment-external-ids-api/) — Operations for retrieving external identifiers linked to a user or account profile.
- [segment Functions API](https://apis.io/apis/segment/segment-functions-api/) — Operations for managing custom functions that transform or enrich data flowing through Segment.
- [segment Group API](https://apis.io/apis/segment/segment-group-api/) — Operations for associating users with groups or organizations.
- [segment Identify API](https://apis.io/apis/segment/segment-identify-api/) — Operations for identifying users and associating traits with them.
- [segment Labels API](https://apis.io/apis/segment/segment-labels-api/) — Operations for managing labels used to organize and control access to workspace resources.
- [segment Links API](https://apis.io/apis/segment/segment-links-api/) — Operations for retrieving linked profiles and relationships.
- [segment Page API](https://apis.io/apis/segment/segment-page-api/) — Operations for recording page views on websites.
- [segment Profiles API](https://apis.io/apis/segment/segment-profiles-api/) — Operations for retrieving user and account profile data from Segment Unify.
- [segment Regulations API](https://apis.io/apis/segment/segment-regulations-api/) — Operations for managing data privacy regulations and suppression requests.
- [segment Screen API](https://apis.io/apis/segment/segment-screen-api/) — Operations for recording screen views in mobile applications.
- [segment Sources API](https://apis.io/apis/segment/segment-sources-api/) — Operations for managing data collection sources within a workspace.
- [segment Track API](https://apis.io/apis/segment/segment-track-api/) — Operations for tracking events and actions performed by users.
- [segment Tracking Plans API](https://apis.io/apis/segment/segment-tracking-plans-api/) — Operations for managing tracking plans that enforce data schemas.
- [segment Traits API](https://apis.io/apis/segment/segment-traits-api/) — Operations for retrieving computed and custom traits for user and account profiles.
- [segment Transformations API](https://apis.io/apis/segment/segment-transformations-api/) — Operations for managing transformations that modify event data before it reaches destinations.
- [segment Warehouses API](https://apis.io/apis/segment/segment-warehouses-api/) — Operations for managing data warehouse connections, including creating and configuring warehouse destinations.
- [segment Workspaces API](https://apis.io/apis/segment/segment-workspaces-api/) — Operations for retrieving workspace information and configuration.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Segment Webhook Events](https://apis.io/asyncapis/segment/segment-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/segment/webhook/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/segment/](https://apis.io/graphqls/segment/segment-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Segment Agentic Access](https://apis.io/agentic-access/segment/segment-agentic-access/)

#### JSON Schema (30)

The data models the API reads and writes.

- [AliasCall](https://apis.io/schemas/segment/segment-aliascall/)
- [BatchCall](https://apis.io/schemas/segment/segment-batchcall/)
- [CatalogDestination](https://apis.io/schemas/segment/segment-catalogdestination/)
- [CatalogSource](https://apis.io/schemas/segment/segment-catalogsource/)
- [Context](https://apis.io/schemas/segment/segment-context/)
- [Cursor](https://apis.io/schemas/segment/segment-cursor/)
- [Segment Destination](https://apis.io/schemas/segment/segment-destination/)
- [DestinationConfig](https://apis.io/schemas/segment/segment-destinationconfig/)
- [Error](https://apis.io/schemas/segment/segment-error/)
- [ErrorResponse](https://apis.io/schemas/segment/segment-errorresponse/)
- [Segment Event](https://apis.io/schemas/segment/segment-event/)
- [ExternalId](https://apis.io/schemas/segment/segment-externalid/)
- [Function](https://apis.io/schemas/segment/segment-function/)
- [FunctionSetting](https://apis.io/schemas/segment/segment-functionsetting/)
- [GroupCall](https://apis.io/schemas/segment/segment-groupcall/)
- [IdentifyCall](https://apis.io/schemas/segment/segment-identifycall/)
- [Integrations](https://apis.io/schemas/segment/segment-integrations/)
- [Label](https://apis.io/schemas/segment/segment-label/)
- [PageCall](https://apis.io/schemas/segment/segment-pagecall/)
- [Pagination](https://apis.io/schemas/segment/segment-pagination/)
- [Regulation](https://apis.io/schemas/segment/segment-regulation/)
- [ScreenCall](https://apis.io/schemas/segment/segment-screencall/)
- [Segment Source](https://apis.io/schemas/segment/segment-source/)
- [SuccessResponse](https://apis.io/schemas/segment/segment-successresponse/)
- [TrackCall](https://apis.io/schemas/segment/segment-trackcall/)
- …and 5 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Segment Structure](https://apis.io/json-structure/segment/segment-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Segment Context](https://apis.io/jsonld/segment/segment-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Segment Domain Vocabulary](https://apis.io/vocabularies/segment/segment-vocabulary/)

#### Collections (27)

Postman and Open Collection request collections.

- [Segment Config Alias API](https://apis.io/collections/segment/open-segment-alias-api/)
- [Segment Config Alias Batch API](https://apis.io/collections/segment/open-segment-batch-api/)
- [Segment Config Alias Catalog API](https://apis.io/collections/segment/open-segment-catalog-api/)
- [Segment Config API](https://apis.io/collections/segment/open-segment-config-api/)
- [Segment Config Alias Destinations API](https://apis.io/collections/segment/open-segment-destinations-api/)
- [Segment Config Alias Events API](https://apis.io/collections/segment/open-segment-events-api/)
- [Segment Config Alias External IDs API](https://apis.io/collections/segment/open-segment-external-ids-api/)
- [Segment Config Alias Functions API](https://apis.io/collections/segment/open-segment-functions-api/)
- [Segment Config Alias Group API](https://apis.io/collections/segment/open-segment-group-api/)
- [Segment HTTP Tracking API](https://apis.io/collections/segment/open-segment-http-tracking-api/)
- [Segment Config Alias Identify API](https://apis.io/collections/segment/open-segment-identify-api/)
- [Segment Config Alias Labels API](https://apis.io/collections/segment/open-segment-labels-api/)
- [Segment Config Alias Links API](https://apis.io/collections/segment/open-segment-links-api/)
- [Segment Config Alias Page API](https://apis.io/collections/segment/open-segment-page-api/)
- [Segment Config Alias Pixel Tracking API](https://apis.io/collections/segment/open-segment-pixel-tracking-api/)
- [Segment Profile API](https://apis.io/collections/segment/open-segment-profile-api/)
- [Segment Config Alias Profiles API](https://apis.io/collections/segment/open-segment-profiles-api/)
- [Segment Public API](https://apis.io/collections/segment/open-segment-public-api/)
- [Segment Config Alias Regulations API](https://apis.io/collections/segment/open-segment-regulations-api/)
- [Segment Config Alias Screen API](https://apis.io/collections/segment/open-segment-screen-api/)
- [Segment Config Alias Sources API](https://apis.io/collections/segment/open-segment-sources-api/)
- [Segment Config Alias Track API](https://apis.io/collections/segment/open-segment-track-api/)
- [Segment Config Alias Tracking Plans API](https://apis.io/collections/segment/open-segment-tracking-plans-api/)
- [Segment Config Alias Traits API](https://apis.io/collections/segment/open-segment-traits-api/)
- [Segment Config Alias Transformations API](https://apis.io/collections/segment/open-segment-transformations-api/)
- …and 2 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Twilio Segment — asyncapi rules](https://apis.io/rules/segment/segment-asyncapi-spectral-rules/)
- [Twilio Segment — jsonschema rules](https://apis.io/rules/segment/segment-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Segment Authentication](https://apis.io/security/segment/segment-authentication/)
- [Segment Domain Security](https://apis.io/security/segment/segment-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Segment Plans Pricing](https://apis.io/plans/segment/segment-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Segment Rate Limits](https://apis.io/rate-limits/segment/segment-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Segment Finops](https://apis.io/finops/segment/segment-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://segment.com)
- [Documentation](https://www.twilio.com/docs/segment)
- [Getting started](https://www.twilio.com/docs/segment/api)
- [API reference](https://docs.segmentapis.com)
- [Pricing](https://segment.com/pricing)
- [Blog](https://segment.com/blog)
- [Terms of service](https://segment.com/legal/terms)
- [Privacy policy](https://segment.com/legal/privacy)
- [GitHub](https://github.com/segmentio)
- [Status](https://status.segment.com)

## API Evangelist rating

**Kin Score 41.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 66.2 |
| Contract governance | 13.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 50.0 |
| Access clarity | 14.5 |

**Agent readiness 26.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/segment/](https://apis.io/providers/segment/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Twilio Segment: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/segment/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
