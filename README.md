# Azure Traffic Manager (microsoft-azure-traffic-manager)
Azure Traffic Manager is a DNS-based traffic load balancer that enables you to distribute traffic optimally to services across global Azure regions, while providing high availability and responsiveness. It supports configurable routing methods including priority, weighted, performance, geographic, multivalue, and subnet routing.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-traffic-manager/refs/heads/main/apis.yml)

## Tags:

 - DNS Load Balancing, Failover, Global Routing, Networking, Traffic Distribution, Traffic Manager

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-04-28

## APIs

### Azure Traffic Manager Profiles REST API
REST API for creating, configuring, and managing Traffic Manager profiles. Profiles define the global DNS-based load balancing configuration including routing method, monitoring settings, and the collection of endpoints participating in the profile.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles](https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles)

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/trafficmanager/resource-manager/Microsoft.Network/stable/2022-04-01/trafficmanager.json)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/profiles?view=rest-trafficmanager-2022-04-01)
- [Getting Started](https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile)

### Azure Traffic Manager Endpoints REST API
REST API for managing endpoints within a Traffic Manager profile. Supports adding, updating, and removing Azure, external, and nested endpoints that receive traffic according to the profile's routing method and health monitoring configuration.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints](https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints)

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/endpoints?view=rest-trafficmanager-2022-04-01)
- [Getting Started](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-endpoint-types)

### Azure Traffic Manager Heatmap REST API
REST API for retrieving Traffic Manager heatmap data, which provides geographic visualization of DNS query volumes and endpoint selection by region. Useful for analyzing traffic distribution and routing decisions across the global user base.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map](https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map)

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/heat-map/get?view=rest-trafficmanager-2022-04-01)

### Azure Traffic Manager User Metrics REST API
REST API for managing real user measurements (RUM) keys used by Traffic Manager performance routing. User metrics enable Traffic Manager to make more accurate latency-based routing decisions using telemetry from end users.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys](https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys)

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/traffic-manager-user-metrics-keys?view=rest-trafficmanager-2022-04-01)

### Azure Traffic Manager Geographic Hierarchies REST API
REST API for retrieving the geographic hierarchy used by Traffic Manager for geographic routing. Returns the supported regions, countries, and subdivisions that can be configured as endpoint geo-mappings within geographic routing profiles.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies](https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies)

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies)
- [Reference](https://learn.microsoft.com/en-us/rest/api/trafficmanager/geographic-hierarchies/get-default?view=rest-trafficmanager-2022-04-01)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Website](https://azure.microsoft.com/en-us/products/traffic-manager)
- [Documentation](https://learn.microsoft.com/en-us/azure/traffic-manager/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/traffic-manager/quickstart-create-traffic-manager-profile)
- [Authentication](https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-scenarios)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/traffic-manager/)
- [SLA](https://azure.microsoft.com/en-us/support/legal/sla/traffic-manager/)
- [Status](https://status.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/options/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Sign Up](https://azure.microsoft.com/en-us/free)
- [SDK - Python](https://pypi.org/project/azure-mgmt-trafficmanager/)
- [SDK - .NET](https://www.nuget.org/packages/Azure.ResourceManager.TrafficManager)
- [SDK - JavaScript](https://www.npmjs.com/package/@azure/arm-trafficmanager)
- [SDK - Java](https://learn.microsoft.com/en-us/java/api/overview/azure/resourcemanager-trafficmanager-readme)
- [CLI Tools](https://learn.microsoft.com/en-us/cli/azure/network/traffic-manager)
- [GitHub Organization](https://github.com/Azure)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-traffic-manager)
- [FAQ](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-FAQs)
- [Training](https://learn.microsoft.com/en-us/training/modules/distribute-load-with-traffic-manager/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
