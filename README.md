# SnapAPI (snapapi)

REST API for website screenshots, metadata extraction, text extraction, and PDF generation. Powered by headless Chromium. Free tier with 50 requests/month, no credit card required.

**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** company
- **submitted via:** [api-search/network#33](https://github.com/api-search/network/issues/33)

## APIs
- **SnapAPI** — `https://snap.michaelcli.com` — screenshots, metadata extraction, text extraction, PDF generation. X-API-Key auth. [OpenAPI](openapi/snapapi-openapi.json) · [Docs](https://snap.michaelcli.com) · [Signup](https://snap.michaelcli.com/api/signup)

## Tags
Screenshots, Website Screenshots, Metadata Extraction, Text Extraction, PDF Generation, Headless Chromium, Web Scraping, Developer Tools, REST

## Artifacts

### Capabilities (Naftiko 1.0.0-alpha2)
- [signup](capabilities/signup.yaml) — Free API key issuance
- [screenshot](capabilities/screenshot.yaml) — POST /api/screenshot + GET /api/usage
- [metadata](capabilities/metadata.yaml) — POST /api/metadata
- [text-extraction](capabilities/text-extraction.yaml) — POST /api/text
- [pdf](capabilities/pdf.yaml) — POST /api/pdf

### JSON Schema
- [Screenshot Request](json-schema/snapapi-screenshot-request-schema.json)
- [Screenshot Response](json-schema/snapapi-screenshot-response-schema.json)
- [Metadata](json-schema/snapapi-metadata-schema.json)
- [PDF Request](json-schema/snapapi-pdf-request-schema.json)
- [Text Extraction](json-schema/snapapi-text-schema.json)
- [Usage](json-schema/snapapi-usage-schema.json)

### JSON-LD
- [snapapi-context.jsonld](json-ld/snapapi-context.jsonld) — schema.org-aligned

### Examples
- [Signup](examples/snapapi-signup-example.json)
- [Screenshot](examples/snapapi-screenshot-example.json)
- [Metadata](examples/snapapi-metadata-example.json)
- [PDF](examples/snapapi-pdf-example.json)
- [Text](examples/snapapi-text-example.json)

### Rules
- [Spectral ruleset](rules/snapapi-rules.yml)

### Vocabulary
- [snapapi-vocabulary.yml](vocabulary/snapapi-vocabulary.yml)

### Commercial
- [Plans & Pricing](plans/snapapi-plans-pricing.yml) — Free (50/mo), Starter ($5/mo, 500), Basic ($15/mo, 2k), Pro ($39/mo, 10k), one-time $5/500 bundle
- [Rate Limits](rate-limits/snapapi-rate-limits.yml) — per-tier monthly quotas
- [FinOps](finops/snapapi-finops.yml) — FOCUS 1.3 alignment

## Common Properties
- [Website](https://snap.michaelcli.com)
- [Signup](https://snap.michaelcli.com/api/signup)
- [Upstream OpenAPI](https://snap.michaelcli.com/openapi.json)

## Timestamps
- **Created:** 2026-05-27
- **Modified:** 2026-05-27

## Maintainers
- **Kin Lane** — kin@apievangelist.com
