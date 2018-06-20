---
swagger: "2.0"
x-collection-name: Azure Resource Health
x-complete: 1
info:
  title: Microsoft.ResourceHealth
  description: the-resource-health-client-
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
  /providers/Microsoft.ResourceHealth/operations:
    get:
      summary: Operations List
      description: Lists available operations for the resourcehealth resource provider
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-resourcehealthoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
---