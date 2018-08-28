---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Deployment Operations List
  description: Gets all deployments operations for a deployment.
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
  /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/deployments/{deploymentName}/operations/{operationId}:
    get:
      summary: Deployment Operations Get
      description: Gets a deployments operation.
      operationId: DeploymentOperations_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnamedeploymentsdeploymentnameoperationsoperationid-get
      parameters:
      - in: path
        name: deploymentName
        description: The name of the deployment
      - in: query
        name: No Name
      - in: path
        name: operationId
        description: The ID of the operation to get
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Deployment Operations
  /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/deployments/{deploymentName}/operations:
    get:
      summary: Deployment Operations List
      description: Gets all deployments operations for a deployment.
      operationId: DeploymentOperations_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnamedeploymentsdeploymentnameoperations-get
      parameters:
      - in: query
        name: $top
        description: The number of results to return
      - in: path
        name: deploymentName
        description: The name of the deployment with the operation to get
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Deployment Operations
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