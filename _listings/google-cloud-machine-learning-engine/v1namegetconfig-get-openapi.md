---
swagger: "2.0"
x-collection-name: Google Cloud Machine Learning Engine
x-complete: 0
info:
  title: Google Cloud Machine Learning API Get Operation
  description: |-
    Get the service account information associated with your project. You need
    this information in order to grant the service account persmissions for
    the Google Cloud Storage location where you put your model training code
    for training the model with Google Cloud Machine Learning.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: ml.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}/operations:
    get:
      summary: Get Operations
      description: |-
        Lists operations that match the specified filter in the request. If the
        server doesn't support this method, it returns `UNIMPLEMENTED`.

        NOTE: the `name` binding below allows API services to override the binding
        to use different resource name schemes, such as `users/*/operations`.
      operationId: ml.projects.operations.list
      x-api-path-slug: v1nameoperations-get
      parameters:
      - in: query
        name: filter
        description: The standard list filter
      - in: path
        name: name
        description: The name of the operation collection
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
      - Machine Learning
      - Operation
  /v1/{name}:cancel:
    post:
      summary: Cancel Operation
      description: |-
        Starts asynchronous cancellation on a long-running operation.  The server
        makes a best effort to cancel the operation, but success is not
        guaranteed.  If the server doesn't support this method, it returns
        `google.rpc.Code.UNIMPLEMENTED`.  Clients can use
        Operations.GetOperation or
        other methods to check whether the cancellation succeeded or whether the
        operation completed despite cancellation. On successful cancellation,
        the operation is not deleted; instead, it becomes an operation with
        an Operation.error value with a google.rpc.Status.code of 1,
        corresponding to `Code.CANCELLED`.
      operationId: ml.projects.operations.cancel
      x-api-path-slug: v1namecancel-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the operation resource to be cancelled
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Operation
  /v1/{name}:getConfig:
    get:
      summary: Get Operation
      description: |-
        Get the service account information associated with your project. You need
        this information in order to grant the service account persmissions for
        the Google Cloud Storage location where you put your model training code
        for training the model with Google Cloud Machine Learning.
      operationId: ml.projects.getConfig
      x-api-path-slug: v1namegetconfig-get
      parameters:
      - in: path
        name: name
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Operation
  /v1/{name}:predict:
    post:
      summary: Predict Operation
      description: |-
        Performs prediction on the data in the request.

        **** REMOVE FROM GENERATED DOCUMENTATION
      operationId: ml.projects.predict
      x-api-path-slug: v1namepredict-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
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