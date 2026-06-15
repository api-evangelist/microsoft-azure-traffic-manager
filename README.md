# Azure Traffic Manager (microsoft-azure-traffic-manager)

Azure Traffic Manager is a DNS-based traffic load balancer that enables you to distribute traffic optimally to services across global Azure regions, while providing high availability and responsiveness. It supports configurable routing methods including priority, weighted, performance, geographic, multivalue, and subnet routing.

**APIs.json:** [https://azure.microsoft.com/en-us/services/traffic-manager/](https://azure.microsoft.com/en-us/services/traffic-manager/)

## Tags

- DNS Load Balancing
- Failover
- Global Routing
- Networking
- Traffic Distribution
- Traffic Manager

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### Azure Traffic Manager Profiles REST API

REST API for creating, configuring, and managing Traffic Manager profiles. Profiles define the global DNS-based load balancing configuration including routing method, monitoring settings, and the collection of endpoints participating in the profile.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles](https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles)
- **Base URL:** `https://management.azure.com`

#### Tags

- Profiles
- Routing
- Traffic Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/trafficmanager/resource-manager/Microsoft.Network/stable/2022-04-01/trafficmanager.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles?view=rest-trafficmanager-2022-04-01)
- [Getting Started](https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile)
- [Postman Collection](collections/microsoft-azure-traffic-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-traffic-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Traffic Manager Endpoints REST API

REST API for managing endpoints within a Traffic Manager profile. Supports adding, updating, and removing Azure, external, and nested endpoints that receive traffic according to the profile's routing method and health monitoring configuration.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints](https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints)
- **Base URL:** `https://management.azure.com`

#### Tags

- Endpoints
- Health Monitoring
- Traffic Manager

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints?view=rest-trafficmanager-2022-04-01)
- [Getting Started](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-endpoint-types)
- [Postman Collection](collections/microsoft-azure-traffic-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-traffic-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Traffic Manager Heatmap REST API

REST API for retrieving Traffic Manager heatmap data, which provides geographic visualization of DNS query volumes and endpoint selection by region. Useful for analyzing traffic distribution and routing decisions across the global user base.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map](https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map)
- **Base URL:** `https://management.azure.com`

#### Tags

- Analytics
- Heatmap
- Traffic Analytics

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map/get?view=rest-trafficmanager-2022-04-01)
- [Postman Collection](collections/microsoft-azure-traffic-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-traffic-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Traffic Manager User Metrics REST API

REST API for managing real user measurements (RUM) keys used by Traffic Manager performance routing. User metrics enable Traffic Manager to make more accurate latency-based routing decisions using telemetry from end users.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys](https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys)
- **Base URL:** `https://management.azure.com`

#### Tags

- Performance
- Real User Measurements
- User Metrics

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys?view=rest-trafficmanager-2022-04-01)
- [Postman Collection](collections/microsoft-azure-traffic-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-traffic-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Traffic Manager Geographic Hierarchies REST API

REST API for retrieving the geographic hierarchy used by Traffic Manager for geographic routing. Returns the supported regions, countries, and subdivisions that can be configured as endpoint geo-mappings within geographic routing profiles.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies](https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies)
- **Base URL:** `https://management.azure.com`

#### Tags

- Geographic Hierarchy
- Geographic Routing
- Regions

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies/get-default?view=rest-trafficmanager-2022-04-01)
- [Postman Collection](collections/microsoft-azure-traffic-manager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-traffic-manager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Website](https://azure.microsoft.com/en-us/products/traffic-manager)
- [Documentation](https://learn.microsoft.com/en-us/azure/traffic-manager/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/traffic-manager/)
- [S L A](https://azure.microsoft.com/en-us/support/legal/sla/traffic-manager/)
- [Status Page](https://status.azure.com/)
- [Blog](https://azure.microsoft.com/en-us/blog/topics/networking/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [Login](https://portal.azure.com)
- [S D Ks](https://azure.microsoft.com/en-us/downloads/)
- [S D K -  Python](https://pypi.org/project/azure-mgmt-trafficmanager/)
- [S D K - . N E T](https://www.nuget.org/packages/Azure.ResourceManager.TrafficManager)
- [S D K -  Java Script](https://www.npmjs.com/package/@azure/arm-trafficmanager)
- [S D K -  Java](https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-trafficmanager-readme)
- [C L I  Tools](https://learn.microsoft.com/en-us/cli/azure/network/traffic-manager)
- [Changelog](https://azure.microsoft.com/en-us/updates/?product=traffic-manager)
- [GitHub Organization](https://github.com/Azure)
- [Git Hub  R E S T  A P I  Specs](https://github.com/Azure/azure-rest-api-specs/tree/main/specification/trafficmanager)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-traffic-manager)
- [Community](https://learn.microsoft.com/en-us/answers/tags/175/azure-traffic-manager)
- [F A Q](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-FAQs)
- [Training](https://learn.microsoft.com/en-us/training/modules/distribute-load-with-traffic-manager/)
- [M C P Server](https://github.com/Azure/Azure-Resource-Manager-MCP)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
