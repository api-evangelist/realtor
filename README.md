# realtor (realtor)

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
