# Geocode Earth (geocode-earth)

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
