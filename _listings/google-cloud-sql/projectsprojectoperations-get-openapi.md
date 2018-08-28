---
swagger: "2.0"
x-collection-name: Google Cloud SQL
x-complete: 0
info:
  title: Google Cloud SQL API Get Projects Project Operations
  description: Lists all instance operations that have been performed on the given
    Cloud SQL instance in the reverse chronological order of the start time.
  contact:
    name: Google
    url: https://google.com
  version: v1beta4
host: www.googleapis.com
basePath: /sql/v1beta4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{project}/operations:
    get:
      summary: Get Projects Project Operations
      description: Lists all instance operations that have been performed on the given
        Cloud SQL instance in the reverse chronological order of the start time.
      operationId: sql.operations.list
      x-api-path-slug: projectsprojectoperations-get
      parameters:
      - in: query
        name: instance
        description: Cloud SQL instance ID
      - in: query
        name: maxResults
        description: Maximum number of operations per response
      - in: query
        name: pageToken
        description: A previously-returned page token representing part of the larger
          set of results to view
      - in: path
        name: project
        description: Project ID of the project that contains the instance
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Project
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