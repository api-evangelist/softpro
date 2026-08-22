# SoftPro (softpro)

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
