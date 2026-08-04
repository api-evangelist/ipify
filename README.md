# ipify (ipify)

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

ipify operates two complementary IP APIs. The free Public IP Address API (api.ipify.org, api6.ipify.org, api64.ipify.org) returns the caller's public IPv4, IPv6, or dual-stack address as plain text, JSON, or JSONP — with no authentication, no rate limit, and no logging. The paid IP Geolocation API (geo.ipify.org), operated by WhoisXML API, resolves an IP, domain, or email to a country/region/city, ISP, and Autonomous System (ASN) profile using credit-metered subscription plans.

**APIs.json:** [https://www.ipify.org/](https://www.ipify.org/)

## Tags

- Development
- IP Address
- Geolocation
- IP Intelligence
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### ipify Public IP Address API

Free, unauthenticated, unlimited public IP address lookup. Returns the caller's IPv4 (api.ipify.org), IPv6 (api6.ipify.org), or dual-stack (api64.ipify.org) address as plain text, JSON, or JSONP.

- **Human URL:** [https://www.ipify.org/](https://www.ipify.org/)
- **Base URL:** `https://api.ipify.org`

#### Tags

- IP Address
- Public IP
- Development

#### Properties

- [Documentation](https://www.ipify.org/)
- [OpenAPI](openapi/ipify-ip-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipify-ip-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipify-ip-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/ip-api-ip-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/ip-api-ip-response-structure.json)
- [Example](examples/ip-api-ip-response-example.json)
- [Source Code](https://github.com/rdegges/ipify-api)
- [SDK](https://github.com/rdegges/python-ipify)
- [SDK](https://github.com/rdegges/go-ipify)

### ipify IP Geolocation API

Paid, credit-metered IP geolocation API operated by WhoisXML API. Resolves an IP, domain, or email to country/region/city, ISP, and AS (ASN) profile. Country (1 credit), Country+City (2 credits), and deprecated Country+City+VPN (3 credits) tiers. Authentication via `apiKey` query parameter.

- **Human URL:** [https://geo.ipify.org/](https://geo.ipify.org/)
- **Base URL:** `https://geo.ipify.org/api/v2`

#### Tags

- Geolocation
- IP Intelligence
- ASN

#### Properties

- [Documentation](https://geo.ipify.org/docs)
- [API Reference](https://geo.ipify.org/docs)
- [OpenAPI](openapi/ipify-geolocation-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ipify-geolocation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ipify-geolocation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/geolocation-api-geolocation-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/geolocation-api-account-balance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/geolocation-api-geolocation-response-structure.json)
- [JSON Structure](json-structure/geolocation-api-account-balance-structure.json)
- [Example](examples/geolocation-api-geolocation-response-example.json)
- [Example](examples/geolocation-api-account-balance-example.json)
- [Pricing](https://geo.ipify.org/pricing)
- [Authentication](https://geo.ipify.org/docs)

## Common Properties

- [Website](https://www.ipify.org/)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [GitHub Repository](https://github.com/rdegges/ipify-api)
- [GitHub Repository](https://github.com/rdegges/python-ipify)
- [GitHub Repository](https://github.com/rdegges/go-ipify)
- [J S O N- L D](json-ld/ipify-context.jsonld)
- [Spectral Rules](rules/ipify-rules.yml)
- [Vocabulary](vocabulary/ipify-vocabulary.yml)
- [Plans](plans/ipify-plans-pricing.yml)
- [Rate Limits](rate-limits/ipify-rate-limits.yml)
- [Fin Ops](finops/ipify-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
