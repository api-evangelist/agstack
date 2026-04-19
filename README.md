# AgStack Foundation (agstack)

AgStack Foundation is a Linux Foundation project providing open-source digital infrastructure for the agriculture sector. Key projects include the Asset Registry (global field boundary registration with unique geo IDs), the OpenAgri Weather Service (agricultural weather forecasts, THI, spray conditions, UAV flight forecasts), and the OpenAgri Farm Calendar (farm operation recording with JSON-LD/OCSM linked data support). AgStack tools support EUDR compliance, precision agriculture, and interoperability across the agtech ecosystem through the OpenAgri Common Semantic Model.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/agstack/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-19

## APIs

### OpenAgri Weather Service

FastAPI-based weather service providing 5-day forecasts, current conditions, Temperature-Humidity Index (THI) for livestock heat stress, UAV flight condition forecasts, and spray condition assessments. Supports both JSON and JSON-LD/OCSM output formats for linked data interoperability. Part of the OpenAgri EU Horizon Europe project.

**Human URL:** [https://github.com/agstack/OpenAgri-WeatherService](https://github.com/agstack/OpenAgri-WeatherService)

#### Tags

- Agriculture
- Weather
- Open Source
- Linux Foundation

#### Properties

- [Documentation](https://github.com/agstack/OpenAgri-WeatherService)
- [GettingStarted](https://github.com/agstack/OpenAgri-WeatherService/blob/main/README.md)
- [OpenAPI](openapi/agstack-openagri-weather-service-openapi.yml)
- [JSONSchema: PredictionOut](json-schema/agstack-openagri-weather-service-predictionout-schema.json)
- [JSONSchema: WeatherDataOut](json-schema/agstack-openagri-weather-service-weatherdataout-schema.json)
- [JSONSchema: THIDataOut](json-schema/agstack-openagri-weather-service-thidataout-schema.json)
- [JSONSchema: SprayForecastResponse](json-schema/agstack-openagri-weather-service-sprayforecastresponse-schema.json)
- [JSONSchema: FlightStatusForecastResponse](json-schema/agstack-openagri-weather-service-flightstatusforecastresponse-schema.json)
- [JSONSchema: GeoJSONOut](json-schema/agstack-openagri-weather-service-geojsonout-schema.json)
- [JSONSchema: JSONLDGraph](json-schema/agstack-openagri-weather-service-jsonldgraph-schema.json)
- [JSONSchema: AuthToken](json-schema/agstack-openagri-weather-service-authtoken-schema.json)

---

### OpenAgri Farm Calendar

Django REST API for digital farm calendar management. Records farmer operations (planting, spraying, harvesting, irrigation), farm observations, parcel properties, and farm assets. Provides data in both JSON and JSON-LD formats conforming to the OpenAgri Common Semantic Model (OCSM). Part of the OpenAgri EU Horizon Europe project.

**Human URL:** [https://github.com/agstack/OpenAgri-FarmCalendar](https://github.com/agstack/OpenAgri-FarmCalendar)

#### Tags

- Agriculture
- Farm Management
- Open Source
- Linux Foundation

#### Properties

- [Documentation](https://github.com/agstack/OpenAgri-FarmCalendar)
- [GettingStarted](https://github.com/agstack/OpenAgri-FarmCalendar/blob/main/README.md)
- [OpenAPI](openapi/agstack-openagri-farm-calendar-openapi.yml)

---

### AgStack Asset Registry

The AgStack Asset Registry provides global field boundary registration and identification. Submit a field polygon (WKT or GeoJSON) and receive a permanent 256-bit (16-character alphanumeric) geo ID. Supports single and bulk registration, field retrieval, centroid calculation, and spatial overlap analysis. Production API available at api-ar.agstack.org.

**Human URL:** [https://github.com/agstack/asset-registry](https://github.com/agstack/asset-registry)

#### Tags

- Agriculture
- Geospatial
- Open Source
- Linux Foundation

#### Properties

- [Documentation](https://github.com/agstack/asset-registry)
- [APIReference](https://api-ar.agstack.org)
- [OpenAPI](openapi/agstack-asset-registry-openapi.yml)
- [JSONSchema: RegisterFieldWktRequest](json-schema/agstack-asset-registry-registerfieldwktrequest-schema.json)
- [JSONSchema: GeoJSONFeatureCollection](json-schema/agstack-asset-registry-geojsonfeaturecollection-schema.json)
- [JSONSchema: BulkPointResult](json-schema/agstack-asset-registry-bulkpointresult-schema.json)
- [JSONStructure: RegisterFieldWktRequest](json-structure/agstack-asset-registry-registerfieldwktrequest-structure.json)
- [JSONStructure: GeoJSONFeatureCollection](json-structure/agstack-asset-registry-geojsonfeaturecollection-structure.json)
- [JSONStructure: BulkPointResult](json-structure/agstack-asset-registry-bulkpointresult-structure.json)
- [Example: RegisterFieldWktRequest](examples/agstack-asset-registry-registerfieldwktrequest-example.json)
- [Example: GeoJSONFeatureCollection](examples/agstack-asset-registry-geojsonfeaturecollection-example.json)
- [Example: BulkPointResult](examples/agstack-asset-registry-bulkpointresult-example.json)

---

## Common Properties

- [Portal](https://agstack.org/)
- [Documentation](https://agstack.org/projects/)
- [GitHubOrganization](https://github.com/agstack)
- [JSON-LD Context](json-ld/agstack-context.jsonld)
- [SpectralRules](rules/agstack-spectral-rules.yml)
- [Vocabulary](vocabulary/agstack-vocabulary.yaml)
- [NaftikoCapability: OpenAgri Weather Service](capabilities/shared/agstack-openagri-weather-service-api.yaml)
- [NaftikoCapability: Asset Registry](capabilities/shared/agstack-asset-registry-api.yaml)
- [NaftikoCapability: Precision Agriculture Workflows](capabilities/precision-agriculture.yaml)

## Features

- **Field Boundary Registry** — Global registry for agricultural field boundaries — submit WKT or GeoJSON geometry, receive a permanent unique 16-character geo ID
- **Agricultural Weather Intelligence** — 5-day weather forecasts, current conditions, and agricultural indicators including THI, spray conditions, and UAV flight suitability
- **Digital Farm Calendar** — Record and manage farm operations (planting, irrigation, spraying, harvesting) with linked data (JSON-LD/OCSM) output
- **Linked Data Support** — All APIs support JSON-LD output conforming to the OpenAgri Common Semantic Model (OCSM) for semantic interoperability
- **EUDR Compliance Support** — Tools for EU Deforestation Regulation compliance — field boundary registration and supply chain traceability via INATrace
- **Irrigation Management** — Evapotranspiration (ETo) calculations and soil moisture analysis for data-driven irrigation decisions
- **Open Source Infrastructure** — All tools are Apache-2.0 licensed, Docker-ready, and deployable on any cloud or on-premises infrastructure

## Use Cases

- **Farmer Field Registration** — Farmers and agri-cooperatives register field boundaries in the global asset registry to enable data-driven farm management
- **Crop Protection Planning** — Check spray conditions and UAV flight forecasts before applying pesticides or fertilizers to minimize drift and maximize efficacy
- **Livestock Heat Stress Monitoring** — Monitor Temperature-Humidity Index to detect and prevent heat stress events in dairy and beef cattle herds
- **EUDR Supply Chain Compliance** — Register plot geolocations and trace agricultural commodities through the supply chain to demonstrate zero-deforestation compliance
- **Precision Irrigation** — Use evapotranspiration data and soil moisture analysis to schedule irrigation and optimize water usage
- **Interoperable Agtech Integration** — Share agricultural data between platforms using JSON-LD/OCSM linked data format for semantic interoperability

## Integrations

- **OpenWeatherMap** — Weather data source for current conditions and forecasts used by the OpenAgri Weather Service
- **OpenAgri** — EU Horizon Europe project (Grant No. 101134083) that funds and drives the OpenAgri microservices ecosystem
- **OCSM** — OpenAgri Common Semantic Model — linked data vocabulary for agricultural interoperability used across all OpenAgri APIs
- **INATrace** — Open-source blockchain-based track and trace system for agricultural supply chains
- **TerraTrac** — TechnoServe Labs mobile and web application for EUDR compliance field data collection integrated with the asset registry

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
