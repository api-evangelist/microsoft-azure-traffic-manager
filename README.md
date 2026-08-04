# Azure Traffic Manager (microsoft-azure-traffic-manager)

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
