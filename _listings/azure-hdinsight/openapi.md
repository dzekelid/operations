---
swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 1
info:
  title: HDInsightManagementClient
  description: the-hdinsight-management-client-
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
  /providers/Microsoft.HDInsight/operations:
    get:
      summary: Operations List
      description: Lists all of the available HDInsight REST API operations.
      operationId: Operations_List
      x-api-path-slug: providersmicrosoft-hdinsightoperations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Operations
---