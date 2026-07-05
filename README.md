# SoftPro (softpro)

SoftPro is the market-leading provider of title, escrow, and real estate closing software, used by title agents, escrow officers, and closing attorneys to produce settlement documents, manage closing files, and disburse funds. **SoftPro 360** is its integrated vendor marketplace - a business exchange built into the SoftPro desktop and hosted products that lets users order title, escrow, and closing products and services (e-recording, closing protection letters and policy jackets, remote online notarization, eClosings, lien releases, property records, tax certificates, identity verification, and wire-fraud protection) from 100+ integrated service providers without leaving their SoftPro file, with order data flowing automatically back into the file.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/softpro/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/softpro/refs/heads/main/apis.yml)

## Access Model (Important)

SoftPro does **not** publish an open, self-service developer API or a public API reference. This entry is an honest, partner-gated stub:

- **Integration is partner-gated.** Vendors join the SoftPro 360 marketplace by submitting a [Become a Partner](https://www.softprocorp.com/become-a-partner/) request. There is no public developer signup.
- **Authentication is by API key.** Approved providers exchange order data with a customer's SoftPro file over a web service, and consumers connect a provider by entering the provider-issued API key under `360 > Services`. This confirms an API-key-authenticated web service, but the endpoints, payload schemas, protocol (REST vs SOAP), and base URLs are shared only with onboarded partners under agreement.
- **No public reference or OpenAPI.** A documents/API portal exists at `docs-api.softprocorp.com`, but it redirects to authentication and returns no public content. The [help portal](https://help.softprocorp.com/) contains end-user 360 application guides, not a developer API reference.
- **Modeled, not sourced.** The API entries below are **modeled** (`endpointsModeled`) from public marketplace descriptions. No endpoint surface, OpenAPI, plans, rate-limits, or FinOps artifacts have been fabricated.

## Tags

- Title Insurance
- Escrow
- Real Estate Closing
- Settlement
- Title Production
- SoftPro 360
- Integration Marketplace
- Partner API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## APIs (modeled - partner-gated)

### SoftPro 360 Integration API

Partner-gated web-service integration behind the SoftPro 360 vendor marketplace. Approved providers exchange closing, title, and escrow order data (orders, requests, status updates, and returned documents) with a customer's SoftPro file, authenticated with SoftPro 360 API keys. Endpoint surface and schemas are provided only to onboarded partners; modeled from public descriptions.

- **Human URL:** [https://www.softprocorp.com/real-estate-software-solutions/softpro-360-data-integration/](https://www.softprocorp.com/real-estate-software-solutions/softpro-360-data-integration/)

### SoftPro Sync API

SoftPro Sync connects two SoftPro customers through SoftPro 360 - one acting as requestor and the other as provider - so a requestor can order services such as title searches directly from another SoftPro customer without rekeying file data. Provider onboarding is by request; modeled from public descriptions.

- **Human URL:** [https://info.softprocorp.com/resources-for-softpro-sync-integration-in-softpro-360](https://info.softprocorp.com/resources-for-softpro-sync-integration-in-softpro-360)

## Pricing

The SoftPro 360 marketplace is included free with SoftPro software; individual services ordered through it are billed a la carte by the respective providers. SoftPro software licensing is quote-based - contact sales at sales@softprocorp.com or 800-848-0143. No public pricing/plans document is available to source.

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/softpro)
- [Website](https://www.softprocorp.com/)
- [Documentation](https://help.softprocorp.com/)
- [Become a Partner (Sign Up)](https://www.softprocorp.com/become-a-partner/)
- [Support](https://www.softprocorp.com/support/)
- [Blog](https://blog.softprocorp.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
