# Nexamp

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
