# AgStack Foundation (agstack)

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

AgStack Foundation is a Linux Foundation project providing open-source digital infrastructure for the agriculture sector. Key projects include the Asset Registry (global field boundary registration with unique geo IDs), the OpenAgri Weather Service (agricultural weather forecasts, THI, spray conditions, UAV flight forecasts), and the OpenAgri Farm Calendar (farm operation recording with JSON-LD/OCSM linked data support). AgStack tools support EUDR compliance, precision agriculture, and interoperability across the agtech ecosystem through the OpenAgri Common Semantic Model.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Agriculture
- Linux Foundation
- Open Source
- Geospatial
- Precision Agriculture
- Linked Data

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### OpenAgri Weather Service

FastAPI-based weather service providing 5-day forecasts, current conditions, Temperature-Humidity Index (THI) for livestock heat stress, UAV flight condition forecasts, and spray condition assessments. Supports both JSON and JSON-LD/OCSM output formats for linked data interoperability. Part of the OpenAgri EU Horizon Europe project.

- **Human URL:** [https://github.com/agstack/OpenAgri-WeatherService](https://github.com/agstack/OpenAgri-WeatherService)

#### Tags

- Agriculture
- Weather
- Open Source
- Linux Foundation

#### Properties

- [Documentation](https://github.com/agstack/OpenAgri-WeatherService)
- [Getting Started](https://github.com/agstack/OpenAgri-WeatherService/blob/main/README.md)
- [OpenAPI](openapi/agstack-openagri-weather-service-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agstack-openagri-weather-service.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agstack-openagri-weather-service.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/agstack-openagri-weather-service-predictionout-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-weatherdataout-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-thidataout-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-sprayforecastresponse-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-flightstatusforecastresponse-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-geojsonout-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-jsonldgraph-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-authtoken-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-pointout-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-validationerror-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-httpvalidationerror-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-openagri-weather-service-body-token-auth-token-post-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/agstack-openagri-weather-service-predictionout-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-weatherdataout-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-thidataout-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-sprayforecastresponse-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-flightstatusforecastresponse-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-geojsonout-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-jsonldgraph-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-authtoken-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-pointout-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-validationerror-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-httpvalidationerror-structure.json)
- [JSON Structure](json-structure/agstack-openagri-weather-service-body-token-auth-token-post-structure.json)
- [Example](examples/agstack-openagri-weather-service-predictionout-example.json)
- [Example](examples/agstack-openagri-weather-service-weatherdataout-example.json)
- [Example](examples/agstack-openagri-weather-service-thidataout-example.json)
- [Example](examples/agstack-openagri-weather-service-sprayforecastresponse-example.json)
- [Example](examples/agstack-openagri-weather-service-flightstatusforecastresponse-example.json)
- [Example](examples/agstack-openagri-weather-service-geojsonout-example.json)
- [Example](examples/agstack-openagri-weather-service-jsonldgraph-example.json)
- [Example](examples/agstack-openagri-weather-service-authtoken-example.json)
- [Example](examples/agstack-openagri-weather-service-pointout-example.json)
- [Example](examples/agstack-openagri-weather-service-validationerror-example.json)
- [Example](examples/agstack-openagri-weather-service-httpvalidationerror-example.json)
- [Example](examples/agstack-openagri-weather-service-body-token-auth-token-post-example.json)

### OpenAgri Farm Calendar

Django REST API for digital farm calendar management. Records farmer operations (planting, spraying, harvesting, irrigation), farm observations, parcel properties, and farm assets. Provides data in both JSON and JSON-LD formats conforming to the OpenAgri Common Semantic Model (OCSM). Part of the OpenAgri EU Horizon Europe project.

- **Human URL:** [https://github.com/agstack/OpenAgri-FarmCalendar](https://github.com/agstack/OpenAgri-FarmCalendar)

#### Tags

- Agriculture
- Farm Management
- Open Source
- Linux Foundation

#### Properties

- [Documentation](https://github.com/agstack/OpenAgri-FarmCalendar)
- [Getting Started](https://github.com/agstack/OpenAgri-FarmCalendar/blob/main/README.md)
- [OpenAPI](openapi/agstack-openagri-farm-calendar-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agstack-openagri-farm-calendar.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agstack-openagri-farm-calendar.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### AgStack Asset Registry

The AgStack Asset Registry provides global field boundary registration and identification. Submit a field polygon (WKT or GeoJSON) and receive a permanent 256-bit (16-character alphanumeric) geo ID. Supports single and bulk registration, field retrieval, centroid calculation, and spatial overlap analysis. Production API available at api-ar.agstack.org.

- **Human URL:** [https://github.com/agstack/asset-registry](https://github.com/agstack/asset-registry)

#### Tags

- Agriculture
- Geospatial
- Open Source
- Linux Foundation

#### Properties

- [Documentation](https://github.com/agstack/asset-registry)
- [API Reference](https://api-ar.agstack.org)
- [OpenAPI](openapi/agstack-asset-registry-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agstack-asset-registry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agstack-asset-registry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/agstack-asset-registry-registerfieldwktrequest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-asset-registry-geojsonfeaturecollection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agstack-asset-registry-bulkpointresult-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/agstack-asset-registry-registerfieldwktrequest-structure.json)
- [JSON Structure](json-structure/agstack-asset-registry-geojsonfeaturecollection-structure.json)
- [JSON Structure](json-structure/agstack-asset-registry-bulkpointresult-structure.json)
- [Example](examples/agstack-asset-registry-registerfieldwktrequest-example.json)
- [Example](examples/agstack-asset-registry-geojsonfeaturecollection-example.json)
- [Example](examples/agstack-asset-registry-bulkpointresult-example.json)

## Common Properties

- [Portal](https://agstack.org/)
- [Documentation](https://agstack.org/projects/)
- [GitHub Organization](https://github.com/agstack)
- [About](https://agstack.org/about/)
- [About](https://lfaidata.foundation/)
- [JSON-LD](json-ld/agstack-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/agstack-spectral-rules.yml)
- [Vocabulary](vocabulary/agstack-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
