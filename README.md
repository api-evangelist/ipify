# ipify (ipify)

ipify operates two complementary IP APIs. The free Public IP Address API (api.ipify.org, api6.ipify.org, api64.ipify.org) returns the caller's public IPv4, IPv6, or dual-stack address as plain text, JSON, or JSONP — with no authentication, no rate limit, and no logging. The paid IP Geolocation API (geo.ipify.org), operated by WhoisXML API, resolves an IP, domain, or email to a country/region/city, ISP, and Autonomous System (ASN) profile using credit-metered subscription plans.

**URL:** [Visit APIs.json URL](https://www.ipify.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Development, IP Address, Geolocation, IP Intelligence, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### ipify Public IP Address API
Free, unauthenticated, unlimited public IP address lookup. Returns the caller's IPv4 (api.ipify.org), IPv6 (api6.ipify.org), or dual-stack (api64.ipify.org) address as plain text, JSON, or JSONP.

**Human URL:** [https://www.ipify.org/](https://www.ipify.org/)

#### Tags:

 - IP Address, Public IP, Development

#### Properties

- [Documentation](https://www.ipify.org/)
- [OpenAPI](openapi/ipify-ip-api.yml)
- [JSONSchema](json-schema/ip-api-ip-response-schema.json)
- [JSONStructure](json-structure/ip-api-ip-response-structure.json)
- [Example](examples/ip-api-ip-response-example.json)
- [NaftikoCapability](capabilities/ip-api-ip-address.yaml)
- [SourceCode — ipify-api (Go server)](https://github.com/rdegges/ipify-api)
- [SDK — Python](https://github.com/rdegges/python-ipify)
- [SDK — Go](https://github.com/rdegges/go-ipify)

### ipify IP Geolocation API
Paid, credit-metered IP geolocation API operated by WhoisXML API. Resolves an IP, domain, or email to country/region/city, ISP, and AS (ASN) profile. Country (1 credit), Country+City (2 credits), and deprecated Country+City+VPN (3 credits) tiers. Authentication via `apiKey` query parameter.

**Human URL:** [https://geo.ipify.org/](https://geo.ipify.org/)

#### Tags:

 - Geolocation, IP Intelligence, ASN

#### Properties

- [Documentation](https://geo.ipify.org/docs)
- [APIReference](https://geo.ipify.org/docs)
- [OpenAPI](openapi/ipify-geolocation-api.yml)
- [JSONSchema — Geolocation Response Schema](json-schema/geolocation-api-geolocation-response-schema.json)
- [JSONSchema — Account Balance Schema](json-schema/geolocation-api-account-balance-schema.json)
- [JSONStructure — Geolocation Response Structure](json-structure/geolocation-api-geolocation-response-structure.json)
- [JSONStructure — Account Balance Structure](json-structure/geolocation-api-account-balance-structure.json)
- [Example — Geolocation Response Example](examples/geolocation-api-geolocation-response-example.json)
- [Example — Account Balance Example](examples/geolocation-api-account-balance-example.json)
- [NaftikoCapability — Geolocation](capabilities/geolocation-api-geolocation.yaml)
- [NaftikoCapability — Account](capabilities/geolocation-api-account.yaml)
- [Pricing](https://geo.ipify.org/pricing)
- [Authentication](https://geo.ipify.org/docs)

## Common Properties

- [Website](https://www.ipify.org/)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [GitHubRepository — ipify-api (server)](https://github.com/rdegges/ipify-api)
- [GitHubRepository — python-ipify](https://github.com/rdegges/python-ipify)
- [GitHubRepository — go-ipify](https://github.com/rdegges/go-ipify)
- [JSON-LD](json-ld/ipify-context.jsonld)
- [SpectralRules](rules/ipify-rules.yml)
- [Vocabulary](vocabulary/ipify-vocabulary.yml)
- [Plans](plans/ipify-plans-pricing.yml)
- [RateLimits](rate-limits/ipify-rate-limits.yml)
- [FinOps](finops/ipify-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Public IP Lookup | Return the caller's public IPv4, IPv6, or dual-stack address with zero authentication. |
| Multi-Format Response | Plain text, JSON, or JSONP — pick what the client speaks natively. |
| Credit-Metered Geolocation | Resolve IP, domain, or email to country/region/city, ISP, and ASN. |
| Reverse DNS Lookup | Optionally return up to five reverse-DNS associated domains for an IP. |
| Account Balance Endpoint | Query remaining credits on the API key in real time. |
| 100 req/s Rate Ceiling | Hard 100 requests/second per API key on the Geolocation API. |
| Open Source Server | The free public IP server is MIT/Unlicense-licensed Go (github.com/rdegges/ipify-api). |

## Use Cases

| Name | Description |
|------|-------------|
| Cloud Server Provisioning | Bootstrapping cloud instances that need to know their own egress IP. |
| Firewall Tunneling Setup | Configuring SSH/VPN tunnels that need the client's current public IP. |
| Geotargeted Content | Personalize banners, currency, or language based on visitor country/city. |
| Fraud Detection | Flag suspicious traffic by ASN, ISP, or geographic mismatch. |
| Compliance Geofencing | Block or restrict access from disallowed regions or countries. |
| Bot and Scraping Defense | Cross-reference IP origin with AS classification (Hosting vs ISP) for traffic scoring. |

## Integrations

| Name | Description |
|------|-------------|
| WhoisXML API | Geolocation product line is part of WhoisXML API's broader IP/DNS intelligence catalog. |
| Heroku | Public IP API server (rdegges/ipify-api) is deployed on Heroku. |
| 20+ Community Client Libraries | Bash, C, Clojurescript, Crystal, Dart, Elixir, Go, Java, Kotlin, .NET, Node.js, Objective-C, PHP, Python, R, Rust, Swift, Xojo, and more. |

## Solutions

| Name | Description |
|------|-------------|
| Free Public IP Lookup | Drop-in HTTP call to api.ipify.org with no signup. Best for client-side IP discovery. |
| Server-Side IP Geolocation | Credit-metered Geolocation API for backend enrichment of inbound traffic. |
| Reverse IP Enrichment | Geolocation API with `reverseIp=1` for associating an IP with up to five domains. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ipify Public IP Address API](openapi/ipify-ip-api.yml)
- [ipify IP Geolocation API](openapi/ipify-geolocation-api.yml)

### JSON Schema

- [IP Response](json-schema/ip-api-ip-response-schema.json)
- [Geolocation Response](json-schema/geolocation-api-geolocation-response-schema.json)
- [Account Balance](json-schema/geolocation-api-account-balance-schema.json)

### JSON Structure

- [IP Response](json-structure/ip-api-ip-response-structure.json)
- [Geolocation Response](json-structure/geolocation-api-geolocation-response-structure.json)
- [Account Balance](json-structure/geolocation-api-account-balance-structure.json)

### JSON-LD

- [ipify Context](json-ld/ipify-context.jsonld)

### Examples

- [IP Response](examples/ip-api-ip-response-example.json)
- [Geolocation Response](examples/geolocation-api-geolocation-response-example.json)
- [Account Balance](examples/geolocation-api-account-balance-example.json)

## Capabilities

Naftiko capabilities organized as self-contained per-tag definitions, each exposing inline REST and MCP adapters.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [IP Address](capabilities/ip-api-ip-address.yaml) | ipify Public IP Address API | 1 | Cloud Provisioner / Browser Client / CLI User |
| [Geolocation](capabilities/geolocation-api-geolocation.yaml) | ipify IP Geolocation API | 3 | Fraud Analyst / Marketing Engineer / Security Operator |
| [Account](capabilities/geolocation-api-account.yaml) | ipify IP Geolocation API | 1 | FinOps Practitioner / Platform Operator |

## Vocabulary

- [ipify Vocabulary](vocabulary/ipify-vocabulary.yml) — Unified taxonomy mapping 5 resources, 2 actions, 3 workflows, and 8 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [ipify Rules](rules/ipify-rules.yml) — 33 rules across 12 categories enforcing ipify API conventions (HTTPS, GET-only, ipify-prefixed summaries, camelCase parameters, apiKey query auth on Geolocation).

## Plans

- [ipify Plans & Pricing](plans/ipify-plans-pricing.yml) — Public IP API (Free), Geolocation Free Trial, Basic, Advanced, Premium, and Custom tiers using API Commons Plans 0.1.

## Rate Limits

- [ipify Rate Limits](rate-limits/ipify-rate-limits.yml) — Public IP API explicitly unlimited; Geolocation API capped at 100 req/s per key plus monthly credit quota.

## FinOps

- [ipify FinOps](finops/ipify-finops.yml) — FOCUS-aligned FinOps profile for the Geolocation API (Tiered Subscription, monthly billing, credit-based meters).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
