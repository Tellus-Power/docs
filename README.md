# Tellus Power Open Platform — Developer Documentation

This repository powers [developers.telluspowergroup.com](https://telluspower.mintlify.app) — the developer portal for the Tellus Power Open Platform API.

## What's here

- **`api-reference/openapi.json`** — OpenAPI 3.1 specification for the Tellus Open Platform API (v1.3)
- **`guides/`** — Hand-written guides covering authentication, OCPP coexistence, errors, and rate limits
- **`docs.json`** — Mintlify navigation, branding, and configuration
- **`index.mdx`**, **`quickstart.mdx`** — Home page and quickstart guide

## Editing

The site is built on [Mintlify](https://mintlify.com). Every push to `main` triggers an automatic redeploy.

To preview locally:

```bash
npm i -g mint
mint dev
```

## Reporting issues

For documentation issues, open a GitHub issue. For platform / API questions, contact `support@telluspowergroup.com`.

## Related

- **[Tellus Console](https://console.telluspowergroup.com)** — Fleet operations and hardware diagnostics, built on this API
- **[telluspowergroup.com](https://www.telluspowergroup.com)** — Tellus Power corporate site
