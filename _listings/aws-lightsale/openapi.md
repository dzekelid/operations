swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 1
info:
  title: AWS Lightsale API
  version: 1.0.0
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