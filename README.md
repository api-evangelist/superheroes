# Superhero API (superheroes)

Open-source REST API exposing 731 superheroes and villains from multiple comic
universes (Marvel, DC, Dark Horse, Image, and more) as pre-built JSON files
served from GitHub Pages with a jsDelivr CDN mirror. All endpoints are
unauthenticated GETs — no key, no sign-up.

**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** opensource
- **x-category:** Games & Comics
- **x-tier:** 3 (bulk-registered from public-apis)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Games & Comics

## Provider Profiled
The original apis.yml entry pointed at `superheroapi.com` (which requires a free
API token). This profiling pass redirected the repo at the open-source,
keyless reissue of the same dataset — **[akabab/superhero-api](https://github.com/akabab/superhero-api)** —
hosted at <https://akabab.github.io/superhero-api/api/>. The upstream
superheroapi.com is documented under `OriginalSource` in the common properties.

## API
- **Superhero API** — [Documentation](https://akabab.github.io/superhero-api/api/) · [GitHub](https://github.com/akabab/superhero-api) · [jsDelivr CDN](https://cdn.jsdelivr.net/gh/akabab/superhero-api@0.3.0/api/)

### Endpoints
| Method | Path | Purpose |
|---|---|---|
| GET | `/all.json` | All 731 character records in one response |
| GET | `/id/{id}.json` | Single character record |
| GET | `/powerstats/{id}.json` | Powerstats slice |
| GET | `/appearance/{id}.json` | Appearance slice |
| GET | `/biography/{id}.json` | Biography slice |
| GET | `/work/{id}.json` | Work slice |
| GET | `/connections/{id}.json` | Connections slice |
| GET | `/images/{size}/{filename}` | Static JPG at size `xs` / `sm` / `md` / `lg` |

## Generated Artifacts
| Artifact | Path |
|---|---|
| OpenAPI 3.0.3 | [openapi/superheroes-openapi.yml](openapi/superheroes-openapi.yml) |
| JSON Schema (Character, Powerstats, Appearance, Biography, Work, Connections, Images) | [json-schema/](json-schema/) |
| JSON Structure | [json-structure/superheroes-character-structure.json](json-structure/superheroes-character-structure.json) |
| JSON-LD Context | [json-ld/superheroes-context.jsonld](json-ld/superheroes-context.jsonld) |
| Examples | [examples/](examples/) |
| Spectral Rules | [rules/superheroes-rules.yml](rules/superheroes-rules.yml) |
| Vocabulary | [vocabulary/superheroes-vocabulary.yml](vocabulary/superheroes-vocabulary.yml) |
| Naftiko Capabilities | [capabilities/](capabilities/) — characters, powerstats, images |
| Plans / Pricing | [plans/superheroes-plans-pricing.yml](plans/superheroes-plans-pricing.yml) |
| Rate Limits | [rate-limits/superheroes-rate-limits.yml](rate-limits/superheroes-rate-limits.yml) |

## Pipeline Notes
- **GitHub org profiled:** [akabab](https://github.com/akabab) — `superhero-api` (70 stars, MIT, last push 2024-02-26). No SDKs published; no MCP servers found.
- **discover-crds:** skipped (not a Kubernetes-native API).
- **finops:** skipped (no commercial offering; pure FOSS hosted on GitHub Pages).
- **plans / rate-limits:** documented as free / fair-use-only.
- **Image surface:** four sizes (xs, sm, md, lg) per character slug, served as static JPGs.

## Tags
Games And Comics, Superheroes, Comic Books, Open Source, Static API, GitHub Pages, Public APIs

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## Maintainers
- **Kin Lane** — kin@apievangelist.com
