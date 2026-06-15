# Microsoft Azure Integration Services (microsoft-azure-integration-services)

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
