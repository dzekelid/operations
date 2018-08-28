swagger: "2.0"
x-collection-name: Azure Cognitive Services
x-complete: 1
info:
  title: CognitiveServicesManagementClient
  description: cognitive-services-management-client
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
  /providers/Microsoft.CognitiveServices/operations:
    get:
      summary: Operations List
      description: Lists all the available Cognitive Services account operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-cognitiveservicesoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Operation