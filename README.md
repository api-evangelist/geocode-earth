# Geocode Earth (geocode-earth)

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

Geocode Earth is a hosted geocoding and address autocomplete API built by the team that maintains Pelias, the open-source geocoder. It provides forward (search), autocomplete, reverse, and structured geocoding plus place lookup over fully open data (OpenStreetMap, OpenAddresses, Who's on First, and Geonames), with results that can be stored without restrictive licensing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/geocode-earth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/geocode-earth/refs/heads/main/apis.yml)

## Tags

- Geocoding
- Address Autocomplete
- Reverse Geocoding
- Mapping
- Pelias
- Open Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Geocode Earth Search API

Forward geocoding that turns a free-text place or address string into structured GeoJSON results with coordinates, ranked by relevance and filterable by country, layer, and source.

- **Human URL:** [https://geocode.earth/docs/forward/search/](https://geocode.earth/docs/forward/search/)
- **Base URL:** `https://api.geocode.earth/v1`

#### Tags

- Geocoding
- Forward
- Search

#### Properties

- [Documentation](https://geocode.earth/docs/forward/search/)
- [API Reference](https://geocode.earth/docs/)
- [OpenAPI](openapi/geocode-earth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocode-earth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocode-earth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocode Earth Autocomplete API

Type-ahead geocoding optimized for partial, real-time user input, returning ranked suggestions as the user types and supporting focus.point to prefer nearby results.

- **Human URL:** [https://geocode.earth/docs/forward/autocomplete/](https://geocode.earth/docs/forward/autocomplete/)
- **Base URL:** `https://api.geocode.earth/v1`

#### Tags

- Autocomplete
- Typeahead
- Forward

#### Properties

- [Documentation](https://geocode.earth/docs/forward/autocomplete/)
- [OpenAPI](openapi/geocode-earth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocode-earth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocode-earth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocode Earth Reverse API

Reverse geocoding that converts a latitude/longitude point into the nearest address, venue, or (with the layers parameter) the administrative area that contains it.

- **Human URL:** [https://geocode.earth/docs/reverse/reverse/](https://geocode.earth/docs/reverse/reverse/)
- **Base URL:** `https://api.geocode.earth/v1`

#### Tags

- Reverse Geocoding
- Coordinates

#### Properties

- [Documentation](https://geocode.earth/docs/reverse/reverse/)
- [OpenAPI](openapi/geocode-earth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocode-earth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocode-earth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocode Earth Structured Search API

Forward geocoding from separate address components (address, locality, region, postalcode, country, and more) instead of a single free-text string, for cases where structured fields are already known.

- **Human URL:** [https://geocode.earth/docs/forward/structured/](https://geocode.earth/docs/forward/structured/)
- **Base URL:** `https://api.geocode.earth/v1`

#### Tags

- Structured
- Geocoding
- Forward

#### Properties

- [Documentation](https://geocode.earth/docs/forward/structured/)
- [OpenAPI](openapi/geocode-earth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocode-earth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocode-earth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Geocode Earth Place API

Looks up one or more records directly by their Geocode Earth global identifier (gid), returning the full GeoJSON feature without running a search.

- **Human URL:** [https://geocode.earth/docs/](https://geocode.earth/docs/)
- **Base URL:** `https://api.geocode.earth/v1`

#### Tags

- Place
- Lookup
- GID

#### Properties

- [Documentation](https://geocode.earth/docs/)
- [OpenAPI](openapi/geocode-earth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geocode-earth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geocode-earth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/pelias)
- [LinkedIn](https://www.linkedin.com/company/geocode-earth)
- [Website](https://geocode.earth/)
- [Documentation](https://geocode.earth/docs/)
- [Plans](plans/geocode-earth-plans-pricing.yml)
- [Rate Limits](rate-limits/geocode-earth-rate-limits.yml)
- [Fin Ops](finops/geocode-earth-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
