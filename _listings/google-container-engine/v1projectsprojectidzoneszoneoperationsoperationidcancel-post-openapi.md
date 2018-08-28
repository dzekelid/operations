---
swagger: "2.0"
x-collection-name: Google Container Engine
x-complete: 0
info:
  title: Google Container Engine API Create Operation
  description: Cancels the specified operation.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: container.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/projects/{projectId}/zones/{zone}/operations:
    get:
      summary: Get Operations
      description: Lists all operations in a project in a specific zone or all zones.
      operationId: container.projects.zones.operations.list
      x-api-path-slug: v1projectsprojectidzoneszoneoperations-get
      parameters:
      - in: path
        name: projectId
        description: The Google Developers Console [project ID or project number](https://support
      - in: path
        name: zone
        description: The name of the Google Compute Engine [zone](/compute/docs/zones#available)
          to return operations for, or `-` for all zones
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1/projects/{projectId}/zones/{zone}/operations/{operationId}:
    get:
      summary: Get Operations
      description: Gets the specified operation.
      operationId: container.projects.zones.operations.get
      x-api-path-slug: v1projectsprojectidzoneszoneoperationsoperationid-get
      parameters:
      - in: path
        name: operationId
        description: The server-assigned `name` of the operation
      - in: path
        name: projectId
        description: The Google Developers Console [project ID or project number](https://support
      - in: path
        name: zone
        description: The name of the Google Compute Engine [zone](/compute/docs/zones#available)
          in which the cluster resides
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1/projects/{projectId}/zones/{zone}/operations/{operationId}:cancel:
    post:
      summary: Create Operation
      description: Cancels the specified operation.
      operationId: container.projects.zones.operations.cancel
      x-api-path-slug: v1projectsprojectidzoneszoneoperationsoperationidcancel-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: operationId
        description: The server-assigned `name` of the operation
      - in: path
        name: projectId
        description: The Google Developers Console [project ID or project number](https://support
      - in: path
        name: zone
        description: The name of the Google Compute Engine [zone](/compute/docs/zones#available)
          in which the operation resides
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