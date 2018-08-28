---
swagger: "2.0"
x-collection-name: Google Compute Engine
x-complete: 0
info:
  title: Google Compute Engine API Get Operation
  description: Retrieves the specified region-specific Operations resource.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /compute/v1/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/aggregated/operations:
    get:
      summary: Get Operations
      description: Retrieves an aggregated list of all operations.
      operationId: compute.globalOperations.aggregatedList
      x-api-path-slug: projectaggregatedoperations-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
      - Aggregation
  /{project}/global/operations:
    get:
      summary: Get Operations
      description: Retrieves a list of Operation resources contained within the specified
        project.
      operationId: compute.globalOperations.list
      x-api-path-slug: projectglobaloperations-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
  /{project}/global/operations/{operation}:
    delete:
      summary: Delete Operation
      description: Deletes the specified Operations resource.
      operationId: compute.globalOperations.delete
      x-api-path-slug: projectglobaloperationsoperation-delete
      parameters:
      - in: path
        name: operation
        description: Name of the Operations resource to delete
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
    get:
      summary: Get Operation
      description: Retrieves the specified Operations resource. Get a list of operations
        by making a list() request.
      operationId: compute.globalOperations.get
      x-api-path-slug: projectglobaloperationsoperation-get
      parameters:
      - in: path
        name: operation
        description: Name of the Operations resource to return
      - in: path
        name: project
        description: Project ID for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
  /{project}/regions/{region}/operations:
    get:
      summary: Get Operations
      description: Retrieves a list of Operation resources contained within the specified
        region.
      operationId: compute.regionOperations.list
      x-api-path-slug: projectregionsregionoperations-get
      parameters:
      - in: query
        name: filter
        description: Sets a filter expression for filtering listed resources, in the
          form filter={expression}
      - in: query
        name: maxResults
        description: The maximum number of results per page that should be returned
      - in: query
        name: orderBy
        description: Sorts list results by a certain order
      - in: query
        name: pageToken
        description: Specifies a page token to use
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
  /{project}/regions/{region}/operations/{operation}:
    delete:
      summary: Delete Operation
      description: Deletes the specified region-specific Operations resource.
      operationId: compute.regionOperations.delete
      x-api-path-slug: projectregionsregionoperationsoperation-delete
      parameters:
      - in: path
        name: operation
        description: Name of the Operations resource to delete
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
    get:
      summary: Get Operation
      description: Retrieves the specified region-specific Operations resource.
      operationId: compute.regionOperations.get
      x-api-path-slug: projectregionsregionoperationsoperation-get
      parameters:
      - in: path
        name: operation
        description: Name of the Operations resource to return
      - in: path
        name: project
        description: Project ID for this request
      - in: path
        name: region
        description: Name of the region for this request
      responses:
        200:
          description: OK
      tags:
      - Operation
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