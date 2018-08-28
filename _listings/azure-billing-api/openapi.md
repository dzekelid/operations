swagger: "2.0"
x-collection-name: Azure Billing API
x-complete: 1
info:
  title: ConsumptionManagementClient
  description: consumption-management-client-provides-access-to-consumption-resources-for-azure-webdirect-subscriptions--other-subscription-types-which-were-not-purchased-directly-through-the-azure-web-portal-are-not-supported-through-this-preview-api-
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
  /providers/Microsoft.Billing/operations:
    get:
      summary: Operations List
      description: Lists all of the available billing REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-billingoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operation
  /providers/Microsoft.Consumption/operations:
    get:
      summary: Operations List
      description: Lists all of the available consumption REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-consumptionoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operation