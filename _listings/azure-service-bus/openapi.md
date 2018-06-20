---
swagger: "2.0"
x-collection-name: Azure Service Bus
x-complete: 1
info:
  title: ServiceBusManagementClient
  description: azure-service-bus-client
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.ServiceBus/operations:
    get:
      summary: Operations List
      description: Lists all of the available ServiceBus REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-servicebusoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
---