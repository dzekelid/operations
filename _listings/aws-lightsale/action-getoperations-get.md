---
swagger: "2.0"
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
  /?Action=GetOperations:
    get:
      summary: ' Get Operations '
      description: Returns information about all operations
      operationId: getOperations
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
      - operations
definitions: []
x-collection-name: AWS Lightsale
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