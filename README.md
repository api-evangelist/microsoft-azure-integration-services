# Microsoft Azure Integration Services (microsoft-azure-integration-services)

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

Microsoft Azure Integration Services is a collection of cloud-based integration capabilities that connect applications, data, and processes across cloud and on-premises environments. It includes API Management, Logic Apps, Service Bus, Event Grid, and Event Hubs to enable enterprise integration, messaging, and event-driven architectures.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/microsoft-azure-integration-services/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/microsoft-azure-integration-services/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Management
- Enterprise
- Event-Driven
- Integration
- Messaging

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Azure API Management

Azure API Management is a fully managed service that enables organizations to publish, secure, transform, maintain, and monitor APIs. It provides a gateway for routing API calls, enforcing usage policies, and providing developer portal capabilities for API consumers.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/api-management/](https://learn.microsoft.com/en-us/azure/api-management/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- API Gateway
- API Management
- Azure
- Developer Portal

#### Properties

- [OpenAPI](openapi/microsoft-azure-integration-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-azure-integration-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-integration-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://learn.microsoft.com/en-us/azure/api-management/)
- [Reference](https://learn.microsoft.com/en-us/rest/api/apimanagement/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/api-management/)
- [Changelog](https://learn.microsoft.com/en-us/azure/api-management/release-notes)

### Azure Logic Apps

Azure Logic Apps is a cloud-based platform for creating and running automated workflows that integrate apps, data, services, and systems. It provides a visual designer and hundreds of pre-built connectors to build workflows without writing code, enabling business process automation and enterprise integration scenarios.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/logic-apps/](https://learn.microsoft.com/en-us/azure/logic-apps/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Azure
- Integration
- Low-Code
- Workflow Automation

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/logic-apps/)
- [Reference](https://learn.microsoft.com/en-us/rest/api/logic/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-create-example-consumption-workflow)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/logic-apps/)
- [Changelog](https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-release-notes)
- [Postman Collection](collections/microsoft-azure-integration-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-integration-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Service Bus

Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics. It decouples applications and services from each other, providing reliable asynchronous message delivery, ordered messaging, dead-lettering, and session support for complex integration workflows.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/service-bus-messaging/](https://learn.microsoft.com/en-us/azure/service-bus-messaging/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Azure
- Message Queue
- Messaging
- Publish-Subscribe

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/service-bus-messaging/)
- [Reference](https://learn.microsoft.com/en-us/rest/api/servicebus/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-quickstart-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/service-bus/)
- [Client  Libraries](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview#client-libraries)
- [Postman Collection](collections/microsoft-azure-integration-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-integration-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Event Grid

Azure Event Grid is a highly scalable, fully managed publish-subscribe event distribution service. It enables event-driven architectures by routing events from Azure services and custom sources to event handlers such as Azure Functions, Logic Apps, and webhooks, with support for filtering and fanout.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/event-grid/](https://learn.microsoft.com/en-us/azure/event-grid/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Azure
- Event-Driven
- Eventing
- Pub-Sub

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/event-grid/)
- [Reference](https://learn.microsoft.com/en-us/rest/api/eventgrid/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/event-grid/custom-event-quickstart-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/event-grid/)
- [Postman Collection](collections/microsoft-azure-integration-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-integration-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Event Hubs

Azure Event Hubs is a big data streaming platform and event ingestion service capable of receiving and processing millions of events per second. It is used for telemetry ingestion, application logging, and real-time analytics pipelines, with support for Apache Kafka protocol, AMQP, and HTTPS.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/event-hubs/](https://learn.microsoft.com/en-us/azure/event-hubs/)
- **Base URL:** `https://management.azure.com/`

#### Tags

- Azure
- Big Data
- Event Streaming
- Kafka

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/event-hubs/)
- [Reference](https://learn.microsoft.com/en-us/rest/api/eventhub/)
- [Getting Started](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-create)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/event-hubs/)
- [Client  Libraries](https://learn.microsoft.com/en-us/azure/event-hubs/sdks)
- [Postman Collection](collections/microsoft-azure-integration-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-azure-integration-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://portal.azure.com/)
- [Website](https://azure.microsoft.com/en-us/products/category/integration)
- [Documentation](https://learn.microsoft.com/en-us/azure/?product=integration)
- [Getting Started](https://learn.microsoft.com/en-us/azure/integration-services/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/)
- [Blog](https://techcommunity.microsoft.com/category/azure/blog/integrationsonazureblog)
- [Support](https://azure.microsoft.com/en-us/support/)
- [Status Page](https://azure.status.microsoft/en-us/status)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [GitHub Organization](https://github.com/Azure)
- [YouTube](https://www.youtube.com/@MicrosoftAzure)
- [Community](https://techcommunity.microsoft.com/category/azure)
- [Console](https://portal.azure.com/)
- [Login](https://portal.azure.com/)
- [Sign Up](https://azure.microsoft.com/en-us/free/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
