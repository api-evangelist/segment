# Segment GraphQL

## Title
Segment GraphQL Schema

## Description
Segment (now part of Twilio) is a customer data platform (CDP) that collects, transforms, and routes customer event data to hundreds of analytics, marketing, and data warehouse destinations. It exposes several REST APIs — the Public API, HTTP Tracking API, Profile API, Config API, and Pixel Tracking API — but does not offer a native public GraphQL endpoint.

## Native GraphQL
No. Segment does not provide a public GraphQL API. All official APIs are REST-based with JSON payloads over HTTPS.

## Endpoint
None (no native GraphQL endpoint).

## Docs Link
- Public API: https://docs.segmentapis.com/
- HTTP Tracking API: https://www.twilio.com/docs/segment/connections/sources/catalog/libraries/server/http-api
- Profile API: https://www.twilio.com/docs/segment/unify/profile-api
- Config API: https://www.twilio.com/docs/segment/api/config-api

## Schema Source
Conceptual schema derived from the Segment REST API surface: Public API, HTTP Tracking API, Profile API, and Config API. Types correspond to Segment's documented resource model and are intended for tooling, catalog enrichment, and schema mapping purposes.

## Types Modeled
Track, Identify, Page, Screen, Group, Alias, Source, Destination, Warehouse, Profile, Trait, Event, Property, Context, Integrations, Batch, Connection, Transformation, Protocol, TrackingPlan, Rule, Violation, Function, Catalog, Workspace, Environment, APIKey, Regulation, SuppressedUser, Privacy
