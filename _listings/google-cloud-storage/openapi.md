swagger: "2.0"
x-collection-name: Google Cloud Storage
x-complete: 1
info:
  title: Google Cloud Storage
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}:
    delete:
      summary: Delete Transfer Operations
      description: This method is not supported and the server returns `UNIMPLEMENTED`.
      operationId: storagetransfer.transferOperations.delete
      x-api-path-slug: v1name-delete
      parameters:
      - in: path
        name: name
        description: The name of the operation resource to be deleted
      responses:
        200:
          description: OK
      tags:
      - Operation
    get:
      summary: Get Transfer Operations
      description: 'Lists operations that match the specified filter in the request.
        If the server doesn''t support this method, it returns `UNIMPLEMENTED`. NOTE:
        the `name` binding below allows API services to override the binding to use
        different resource name schemes, such as `users/*/operations`.'
      operationId: storagetransfer.transferOperations.list
      x-api-path-slug: v1name-get
      parameters:
      - in: query
        name: filter
        description: The standard list filter
      - in: path
        name: name
        description: The value `transferOperations`
      - in: query
        name: pageSize
        description: The standard list page size
      - in: query
        name: pageToken
        description: The standard list page token
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1/{name}:cancel:
    post:
      summary: Cancel Transfer Operation
      description: Cancels a transfer. Use the get method to check whether the cancellation
        succeeded or whether the operation completed despite cancellation.
      operationId: storagetransfer.transferOperations.cancel
      x-api-path-slug: v1namecancel-post
      parameters:
      - in: path
        name: name
        description: The name of the operation resource to be cancelled
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1/{name}:pause:
    post:
      summary: Pause Transfer Operation
      description: Pauses a transfer operation.
      operationId: storagetransfer.transferOperations.pause
      x-api-path-slug: v1namepause-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the transfer operation
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1/{name}:resume:
    post:
      summary: Resume Transfer Operation
      description: Resumes a transfer operation that is paused.
      operationId: storagetransfer.transferOperations.resume
      x-api-path-slug: v1nameresume-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the transfer operation
      responses:
        200:
          description: OK
      tags:
      - Operation