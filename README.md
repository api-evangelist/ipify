# ipify (ipify)

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
