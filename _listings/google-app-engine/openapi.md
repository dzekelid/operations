swagger: "2.0"
x-collection-name: Google App Engine
x-complete: 1
info:
  title: Google App Engine Admin
  description: provisions-and-manages-app-engine-applications-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: appengine.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/apps/{appsId}/operations:
    get:
      summary: Get Operations
      description: 'Lists operations that match the specified filter in the request.
        If the server doesn''t support this method, it returns UNIMPLEMENTED.NOTE:
        the name binding below allows API services to override the binding to use
        different resource name schemes, such as users/*/operations.'
      operationId: appengine.apps.operations.list
      x-api-path-slug: v1appsappsidoperations-get
      parameters:
      - in: path
        name: appsId
        description: Part of `name`
      - in: query
        name: filter
        description: The standard list filter
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