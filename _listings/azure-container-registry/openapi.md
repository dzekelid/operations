swagger: "2.0"
x-collection-name: Azure Container Registry
x-complete: 1
info:
  title: ContainerRegistryManagementClient
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
  /providers/Microsoft.ContainerRegistry/operations:
    get:
      summary: Operations List
      description: Lists all of the available Azure Container Registry REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-containerregistryoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operation