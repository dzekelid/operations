swagger: "2.0"
x-collection-name: Azure Event Hubs
x-complete: 1
info:
  title: EventHubManagementClient
  description: azure-event-hubs-client
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
  /providers/Microsoft.EventHub/operations:
    get:
      summary: Operations List
      description: Lists all of the available Event Hub REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-eventhuboperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations