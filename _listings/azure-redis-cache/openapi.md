---
swagger: "2.0"
x-collection-name: Azure Redis Cache
x-complete: 1
info:
  title: RedisManagementClient
  description: rest-api-for-azure-redis-cache-service-
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
  /providers/Microsoft.Cache/operations:
    get:
      summary: Operations List
      description: Lists all of the available REST API operations of the Microsoft.Cache
        provider.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-cacheoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
---