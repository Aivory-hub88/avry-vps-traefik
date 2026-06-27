# avry-vps-traefik

Traefik dynamic configuration for the Aivory production VPS.

- `dynamic/aivory-secure.yml` — security middleware (headers, rate-limit, Cloudflare IP allowlist, etc.)
- `dynamic/ip-fallback.yml` — IP fallback router rules

**Not tracked:** `letsencrypt/acme.json` (Let's Encrypt account key + issued certificate private keys) — lives only on the VPS at `traefik/letsencrypt/`.
