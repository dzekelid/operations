swagger: "2.0"
x-collection-name: Azure Advisor
x-complete: 1
info:
  title: Azure Advisor API
  description: azure-advisor-is-a-personalized-recommendation-engine-that-helps-you-follow-azure-best-practices--it-analyzes-your-azure-resource-configuration-and-usage-telemetry-then-provides-recommendations-that-can-reduce-costs-and-improve-the-performance-security-and-reliability-of-your-applications-
  version: "2017-04-19"
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /providers/Microsoft.Advisor/operations:
    get:
      summary: List Operations
      description: Lists all the available Advisor REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-advisoroperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations