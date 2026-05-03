# United States Army Corps of Engineers

The U.S. Army Corps of Engineers (USACE) provides engineering and construction services for the nation, managing water resources, infrastructure, and environmental projects. USACE operates the Corps Water Management System (CWMS) Data API, a RESTful service providing real-time and historical access to water management data across the United States including time series measurements, location data, ratings, forecasts, and project information.

**Website:** [https://www.usace.army.mil/](https://www.usace.army.mil/)

## APIs

### CWMS Data API

The Corps Water Management System (CWMS) Data API provides public access to water resource data managed by the U.S. Army Corps of Engineers.

- **Documentation:** [cwms-data.usace.army.mil](https://cwms-data.usace.army.mil/cwms-data/)
- **Base URL:** `https://cwms-data.usace.army.mil/cwms-data`
- **GitHub:** [USACE/cwms-data-api](https://github.com/USACE/cwms-data-api)

## Artifacts

### OpenAPI Specifications

- [cwms-data-api-openapi.yml](openapi/cwms-data-api-openapi.yml) — OpenAPI 3.1 specification for the CWMS Data API covering locations, time series, levels, ratings, forecasts, projects, and basins.

### Examples

- [cwms-data-api-getTimeSeries-example.json](examples/cwms-data-api-getTimeSeries-example.json) — Example request/response for retrieving time series measurements.
- [cwms-data-api-getLocations-example.json](examples/cwms-data-api-getLocations-example.json) — Example request/response for retrieving location data.
- [cwms-data-api-getCatalog-example.json](examples/cwms-data-api-getCatalog-example.json) — Example request/response for browsing the CWMS data catalog.

### Spectral Rules

- [cwms-data-api-rules.yml](rules/cwms-data-api-rules.yml) — Spectral ruleset enforcing CWMS API conventions including office code documentation, timestamp format standards, and pagination requirements.

### Capabilities

- [water-resources-management.yaml](capabilities/water-resources-management.yaml) — Naftiko workflow capability for USACE water resources management, providing unified REST and MCP access to locations, time series, forecasts, and project data.
- [capabilities/shared/cwms-data-api.yaml](capabilities/shared/cwms-data-api.yaml) — Shared per-API Naftiko capability definition for the CWMS Data API.

### JSON Schema

- [cwms-data-api-location-schema.json](json-schema/cwms-data-api-location-schema.json) — JSON Schema for CWMS Location objects.
- [cwms-data-api-timeseries-schema.json](json-schema/cwms-data-api-timeseries-schema.json) — JSON Schema for CWMS Time Series objects.

### JSON Structure

- [cwms-data-api-location-structure.json](json-structure/cwms-data-api-location-structure.json) — Structure documentation for CWMS Location fields.
- [cwms-data-api-timeseries-structure.json](json-structure/cwms-data-api-timeseries-structure.json) — Structure documentation for CWMS Time Series fields.

### JSON-LD Context

- [united-states-army-corps-of-engineers-context.jsonld](json-ld/united-states-army-corps-of-engineers-context.jsonld) — Linked data context aligning CWMS vocabulary with SOSA/SSN observation ontologies, QUDT units, and schema.org.

### Vocabulary

- [united-states-army-corps-of-engineers-vocabulary.yml](vocabulary/united-states-army-corps-of-engineers-vocabulary.yml) — Domain vocabulary covering water resources management, CWMS data structures, hydrology terms, and engineering concepts.

## Additional Resources

| Resource | Link |
|---|---|
| Open Data | [usace.army.mil/open](https://www.usace.army.mil/open/) |
| Geospatial Data | [geospatial-usace.opendata.arcgis.com](https://geospatial-usace.opendata.arcgis.com/) |
| Water Data Platform | [water.usace.army.mil](https://water.usace.army.mil/data) |
| Permits Data | [permits.ops.usace.army.mil](https://permits.ops.usace.army.mil/) |
| GitHub | [github.com/USACE](https://github.com/USACE) |

**Maintained by:** [API Evangelist](https://apievangelist.com)
