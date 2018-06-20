---
swagger: "2.0"
x-collection-name: Azure Storage
x-complete: 1
info:
  title: StorSimpleSeries8000ManagementClient
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
  /providers/Microsoft.ImportExport/operations:
    get:
      summary: List Supported Operations
      description: Returns the list of operations supported by the import/export resource
        provider.
      operationId: ListSupportedOperations
      x-api-path-slug: providersmicrosoft-importexportoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Supported Operations
  /providers/Microsoft.StorSimple/operations:
    get:
      summary: Operations List
      description: Lists all of the available REST API operations of the Microsoft.Storsimple
        provider
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-storsimpleoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
---