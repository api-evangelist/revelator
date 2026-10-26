# Revelator (revelator)

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

Revelator is a music distribution and rights, royalties, and payments infrastructure platform for labels, distributors, and music businesses. Its REST API exposes the digital supply chain - distribution, catalog, analytics and trends, royalty accounting, and payments - behind a single OAuth2 Bearer-token interface using a child-account model.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/revelator/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/revelator/refs/heads/main/apis.yml)

## Tags

- Music
- Distribution
- Rights
- Royalties
- Payments
- Analytics

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Revelator Distribution API

Validates release metadata, configures retail/distribution options, queues releases for delivery to DSPs/stores, retrieves per-store distribution status, and processes takedowns.

- **Human URL:** [https://api-docs.revelator.com/en/distribution/](https://api-docs.revelator.com/en/distribution/)
- **Base URL:** `https://api.revelator.com`

#### Tags

- Distribution
- Releases
- DSP
- Delivery

#### Properties

- [Documentation](https://api-docs.revelator.com/en/distribution/)
- [API Reference](https://api-docs.revelator.com/en/distribution/)
- [OpenAPI](openapi/revelator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revelator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revelator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Revelator Catalog API

Manages enterprise accounts and their catalog of releases, tracks, and assets, including account signup/login, account switching, permissions, and common lookup data (currencies, countries, stores).

- **Human URL:** [https://api-docs.revelator.com/en/getting-started](https://api-docs.revelator.com/en/getting-started)
- **Base URL:** `https://api.revelator.com`

#### Tags

- Catalog
- Releases
- Tracks
- Assets

#### Properties

- [Documentation](https://api-docs.revelator.com/en/getting-started)
- [OpenAPI](openapi/revelator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revelator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revelator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Revelator Analytics API

Aggregated revenue, consumption, and engagement analytics across many dimensions (artist, country, track, release, distributor, playlist), plus key metrics, playlist performance, and artificial-streaming detection.

- **Human URL:** [https://api-docs.revelator.com/en/analytics/](https://api-docs.revelator.com/en/analytics/)
- **Base URL:** `https://api.revelator.com`

#### Tags

- Analytics
- Trends
- Streams
- Consumption

#### Properties

- [Documentation](https://api-docs.revelator.com/en/analytics/)
- [API Reference](https://api-docs.revelator.com/en/analytics/)
- [OpenAPI](openapi/revelator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revelator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revelator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Revelator Royalties & Accounting API

Manages rights contracts, payees, and licensors, and retrieves financial sale reports and user statements (royalty runs and raw DSP imports) with summary and detail downloads.

- **Human URL:** [https://api-docs.revelator.com/en/rights/](https://api-docs.revelator.com/en/rights/)
- **Base URL:** `https://api.revelator.com`

#### Tags

- Royalties
- Accounting
- Contracts
- Revenue

#### Properties

- [Documentation](https://api-docs.revelator.com/en/rights/)
- [API Reference](https://api-docs.revelator.com/en/revenue/)
- [OpenAPI](openapi/revelator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revelator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revelator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Revelator Payments & Wallet API

Configures payee payment methods via Tipalti, and mints, lists, and retrieves ERC1155 royalty tokens backed by track assets with Web3 smart-wallet holders for on-chain royalty distribution.

- **Human URL:** [https://api-docs.revelator.com/en/royalty-tokens/](https://api-docs.revelator.com/en/royalty-tokens/)
- **Base URL:** `https://api.revelator.com`

#### Tags

- Payments
- Wallet
- Payouts
- Royalty Tokens

#### Properties

- [Documentation](https://api-docs.revelator.com/en/integrations/)
- [API Reference](https://api-docs.revelator.com/en/royalty-tokens/)
- [OpenAPI](openapi/revelator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/revelator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/revelator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/revelator)
- [Website](https://www.revelator.com)
- [Documentation](https://api-docs.revelator.com)
- [Plans](plans/revelator-plans-pricing.yml)
- [Rate Limits](rate-limits/revelator-rate-limits.yml)
- [Fin Ops](finops/revelator-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
