# Superhero API (akabab) (superheroes)

Open-source REST API exposing 731 superheroes and villains drawn from multiple comic universes (Marvel, DC, Dark Horse, Image, and more) under a single, unauthenticated JSON surface. The dataset is rebuilt from the original superheroapi.com source, cleaned up, and republished as static JSON files served from GitHub Pages and the jsDelivr CDN. Each character includes powerstats, appearance, biography, work, connections, and a multi-resolution image set.

**APIs.json:** [https://akabab.github.io/superhero-api/api/](https://akabab.github.io/superhero-api/api/)

## Tags

- Games And Comics
- Superheroes
- Comic Books
- Open Source
- Static API
- GitHub Pages
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Superhero API

The Superhero API is a static JSON REST surface that returns a single consolidated dataset of 731 characters or per-character / per-property records. All responses are pre-built JSON files served from GitHub Pages (akabab.github.io) with a jsDelivr CDN mirror. Endpoints cover the full character record (/id/{id}.json) and individual property slices (powerstats, appearance, biography, work, connections), plus a bulk /all.json file containing every character. A separate image surface serves four sizes (xs, sm, md, lg) per character slug.

- **Human URL:** [https://akabab.github.io/superhero-api/api/](https://akabab.github.io/superhero-api/api/)
- **Base URL:** `https://akabab.github.io/superhero-api/api`

#### Tags

- Games And Comics
- Superheroes

#### Properties

- [Documentation](https://akabab.github.io/superhero-api/api/)
- [Source Code](https://github.com/akabab/superhero-api)
- [OpenAPI](openapi/superheroes-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/superheroes.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/superheroes.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://akabab.github.io/superhero-api/api/)
- [Source Code](https://github.com/akabab/superhero-api)
- [GitHub Organization](https://github.com/akabab)
- [License](https://github.com/akabab/superhero-api/blob/master/LICENSE)
- [C D N](https://cdn.jsdelivr.net/gh/akabab/superhero-api@0.3.0/api/)
- [Original Source](https://superheroapi.com)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/superheroes-rules.yml)
- [Vocabulary](vocabulary/superheroes-vocabulary.yml)
- [JSON-LD](json-ld/superheroes-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/superheroes-character-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/superheroes-powerstats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/superheroes-appearance-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/superheroes-biography-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/superheroes-work-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/superheroes-connections-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/superheroes-images-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/superheroes-character-structure.json)
- [Example](examples/superheroes-character-example.json)
- [Example](examples/superheroes-all-example.json)
- [Example](examples/superheroes-powerstats-example.json)
- [Rate Limits](rate-limits/superheroes-rate-limits.yml)
- [Plans](plans/superheroes-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
