swagger: "2.0"
x-collection-name: Azure Service Fabric
x-complete: 1
info:
  title: ServiceFabricManagementClient
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
  /providers/Microsoft.ServiceFabric/operations:
    get:
      summary: Operations List
      description: Lists all of the available ServiceFabric REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-servicefabricoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations