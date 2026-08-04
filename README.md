# Nexamp

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

Nexamp is a Boston-based clean energy company, founded in 2007 by two U.S. Army veterans, that develops, builds, owns and operates distributed solar generation and battery storage across the United States and is one of the country's largest fully integrated community solar providers. It runs end-to-end — project development and acquisition, engineering and design, construction, asset operations, and subscriber management — alongside power purchase agreements, land leasing for solar farm hosts, energy storage, and standalone development and asset-management services.

- Website — https://www.nexamp.com/
- Community portal — https://community.nexamp.com/
- Decarbonization Platform — https://portal.nexamp.com/
- Help Center — https://help.nexamp.com/hc/en-us
- Secondary-market listing — https://forgeglobal.com/nexamp_stock/

## API surface

**Nexamp publishes no public API.** Full contract discovery on 2026-08-01 found no OpenAPI/Swagger,
no GraphQL, no AsyncAPI or webhook catalogue, no MCP server, no A2A agent card, no `/.well-known/`
documents, no `llms.txt`, and no SDK in any public package registry. `developer.nexamp.com` and
`docs.nexamp.com` do not resolve, and the `Nexamp` GitHub organisation has zero public repositories.

An undocumented API host — `api.nexamp.com`, on Azure App Service — is gated behind Microsoft
Entra ID and **serves a TLS certificate that expired on 2024-05-14**. It is an internal/partner
surface, not an integration target.

Every probe and HTTP status is recorded in [`review.yml`](review.yml).

## Artifacts

| Artifact | File |
|---|---|
| Provider index | [`apis.yml`](apis.yml) |
| Contract-discovery review | [`review.yml`](review.yml) |
| Domain security (TLS/HSTS/DNSSEC/CAA/SPF/DMARC) | [`security/nexamp-domain-security.yml`](security/nexamp-domain-security.yml) |
| `/.well-known/` probe index | [`well-known/nexamp-well-known.yml`](well-known/nexamp-well-known.yml) |
| llms.txt | [`llms/nexamp-llms.txt`](llms/nexamp-llms.txt) |
