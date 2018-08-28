---
swagger: "2.0"
x-collection-name: Google Cloud Dataproc
x-complete: 0
info:
  title: Google Cloud Dataproc API Start Cancellation
  description: Starts asynchronous cancellation on a long-running operation. The server
    makes a best effort to cancel the operation, but success is not guaranteed. If
    the server doesn't support this method, it returns google.rpc.Code.UNIMPLEMENTED.
    Clients can use Operations.GetOperation or other methods to check whether the
    cancellation succeeded or whether the operation completed despite cancellation.
    On successful cancellation, the operation is not deleted; instead, it becomes
    an operation with an Operation.error value with a google.rpc.Status.code of 1,
    corresponding to Code.CANCELLED.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: dataproc.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}:
    delete:
      summary: Delete Operation
      description: Deletes a long-running operation. This method indicates that the
        client is no longer interested in the operation result. It does not cancel
        the operation. If the server doesn't support this method, it returns google.rpc.Code.UNIMPLEMENTED.
      operationId: dataproc.projects.regions.operations.delete
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
      summary: Get Operation State
      description: Gets the latest state of a long-running operation. Clients can
        use this method to poll the operation result at intervals as recommended by
        the API service.
      operationId: dataproc.projects.regions.operations.get
      x-api-path-slug: v1name-get
      parameters:
      - in: path
        name: name
        description: The name of the operation resource
      responses:
        200:
          description: OK
      tags:
      - Operation
  /v1/{name}:cancel:
    post:
      summary: Start Cancellation
      description: Starts asynchronous cancellation on a long-running operation. The
        server makes a best effort to cancel the operation, but success is not guaranteed.
        If the server doesn't support this method, it returns google.rpc.Code.UNIMPLEMENTED.
        Clients can use Operations.GetOperation or other methods to check whether
        the cancellation succeeded or whether the operation completed despite cancellation.
        On successful cancellation, the operation is not deleted; instead, it becomes
        an operation with an Operation.error value with a google.rpc.Status.code of
        1, corresponding to Code.CANCELLED.
      operationId: dataproc.projects.regions.operations.cancel
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