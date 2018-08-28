swagger: "2.0"
x-collection-name: Azure CDN
x-complete: 1
info:
  title: CdnManagementClient
  description: use-these-apis-to-manage-azure-cdn-resources-through-the-azure-resource-manager--you-must-make-sure-that-requests-made-to-these-resources-are-secure-
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.Cdn/operations:
    get:
      summary: List Operations
      description: Lists all of the available CDN REST API operations.
      operationId: ListOperations
      x-api-path-slug: providersmicrosoft-cdnoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - CDN
      - Operations