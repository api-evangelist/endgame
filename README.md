# Endgame

Endgame was an endpoint security company (endpoint protection, threat hunting, adversary detection) that was acquired by Elastic N.V. and folded into Elastic Security.

**Status: acquired — no independent API surface.** As of a live probe on 2026-07-20, `endgame.com` is a redirect-only domain: the site root and every `/.well-known/` discovery path return HTTP 301 to <https://www.elastic.co/security/endpoint-security>. There is no Endgame developer portal, API documentation, OpenAPI description, SDK, CLI, webhook/event surface, changelog, status page, or MCP server.

Successor product: <https://www.elastic.co/security/endpoint-security>

Artifacts in this profile:

- `security/endgame-domain-security.yml` — probed TLS/HSTS/DNS posture
- `well-known/endgame-well-known.yml` — verified-absent discovery surface
- `llms/endgame-llms.txt` — agent-readable status and successor pointers
