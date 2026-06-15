# realtor (realtor)

Realtor.com is an online real estate marketplace operated by Move, Inc., providing home listings, neighborhood information, and tools for buyers, sellers, and renters.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/realtor/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Realtor.com Connections Plus API

The Realtor.com Connections Plus API provides a direct connection between the Realtor.com lead delivery system and supporting CRM platforms. It enables real estate agents, brokers, and offices to receive buyer and seller leads in real time via API rather than email. The API delivers richer lead data including listing URLs, geographic coordinates, dates, and MLS information that are not available through standard email delivery.

- **Human URL:** [https://www.realtor.com/marketing/connections/](https://www.realtor.com/marketing/connections/)
- **Base URL:** `https://api.example.com`

#### Tags

- Agents
- Brokers
- CRM
- Leads
- Real Estate

#### Properties

- [Documentation](https://www.realtor.com/marketing/connections/)
- [AsyncAPI](asyncapi/realtor-connections-plus-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/realtor-property-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtor-property-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Realtor.com Lead Delivery API

The Realtor.com Lead Delivery API is an end-to-end integration layer that delivers real estate leads directly from Realtor.com to third-party CRM systems. It provides faster and more secure lead delivery compared to traditional email-based methods, with consistent formatting and additional data fields.

- **Human URL:** [https://www.realtor.com/marketing/connections/](https://www.realtor.com/marketing/connections/)
- **Base URL:** `https://api.example.com`

#### Tags

- CRM Integration
- Delivery
- Leads
- Notifications
- Real Estate

#### Properties

- [Documentation](https://www.realtor.com/marketing/connections/)
- [AsyncAPI](asyncapi/realtor-lead-delivery-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/realtor-property-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtor-property-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Realtor.com Property Data API

The Realtor.com Property Data API provides programmatic access to real estate listing data from Realtor.com, one of the largest property listing platforms in the United States. It offers endpoints for searching properties by location, price range, bedrooms, bathrooms, and other criteria, as well as retrieving detailed property information including listing status, photos, and neighborhood data.

- **Human URL:** [https://rapidapi.com/apidojo/api/realty-in-us](https://rapidapi.com/apidojo/api/realty-in-us)
- **Base URL:** `https://realtor.p.rapidapi.com`

#### Tags

- MLS
- Property Data
- Property Listings
- Real Estate
- Search

#### Properties

- [Documentation](https://rapidapi.com/apidojo/api/realty-in-us)
- [OpenAPI](openapi/realtor-property-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/realtor-property-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/realtor-property-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/realtor-com)
- [JSON-LD](json-ld/realtor-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/realtor-lead-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/realtor-property-schema.json) — [JSON Schema](https://json-schema.org/specification)
