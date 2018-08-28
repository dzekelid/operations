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