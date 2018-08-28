---
swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 0
info:
  title: Amazon Lightsale API Get Operations
  version: 1.0.0
  description: Returns information about all operations.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetOperation:
    get:
      summary: Get Operation
      description: Returns information about a specific operation.
      operationId: getOperation
      x-api-path-slug: actiongetoperation-get
      parameters:
      - in: query
        name: operationId
        description: A GUID used to identify the operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Operations
  /?Action=GetOperations:
    get:
      summary: Get Operations
      description: Returns information about all operations.
      operationId: getOperations
      x-api-path-slug: actiongetoperations-get
      parameters:
      - in: query
        name: pageToken
        description: A token used for advancing to the next page of results from your
          get operations      request
        type: string
      responses:
        200:
          description: OK
      tags:
      - Operations
  /?Action=GetOperationsForResource:
    get:
      summary: Get Operations For Resource
      description: Gets operations for a specific resource (e.
      operationId: getOperationsForResource
      x-api-path-slug: actiongetoperationsforresource-get
      parameters:
      - in: query
        name: pageToken
        description: A token used for advancing to the next page of results from your
          get operations for      resource request
        type: string
      - in: query
        name: resourceName
        description: The name of the resource for which you are requesting information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Operations
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---