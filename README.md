# Superhero API (akabab) (superheroes)

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
