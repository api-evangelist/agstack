# AgStack Foundation (agstack)

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
