---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Perform a search operation.
  description: Perform a search operation..
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/logs:
    get:
      summary: Perform a search operation.
      description: Perform a search operation..
      operationId: getRestLogs
      x-api-path-slug: restlogs-get
      parameters:
      - in: query
        name: additionalInfo
        description: Filter that restricts the search result to log entries that match
          an additional info
      - in: query
        name: code
        description: Filter that restricts the search result to log entries with a
          custom code
      - in: query
        name: fromDate
        description: Filter that restricts the search result to log entries created
          after this date
      - in: query
        name: identifier
        description: Filter that restricts the search result to log entries with custom
          identifier(s)
      - in: query
        name: integration
        description: Filter that restricts the search result to log entries with custom
          integration key(s)
      - in: query
        name: itemsPerPage
        description: The number of items to list per page
      - in: query
        name: level
        description: Filter that restricts the search result to log entries of a custom
          level
      - in: query
        name: page
        description: The page of results to search for
      - in: query
        name: referenceType
        description: Filter that restricts the search result to log entries with custom
          reference types
      - in: query
        name: referenceValue
        description: Filter that restricts the search result to log entries with custom
          reference values
      - in: query
        name: toDate
        description: Filter that restricts the search result to log entries created
          before this date
      - in: query
        name: with
        description: An array with child instances to be loaded
      responses:
        200:
          description: OK
      tags:
      - Perform
      - Search
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