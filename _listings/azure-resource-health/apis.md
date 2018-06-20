---
name: Azure Resource Health
x-slug: azure-resource-health
description: Resource health helps you diagnose and get support when an Azure issue
  impacts your resources. It informs you about the current and past health of your
  resources and helps you mitigate issues. Resource health provides technical support
  when you need help with Azure service issues.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Operations
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Resource Health API Operations List
  x-api-slug: azure-resource-health-api
  description: Lists available operations for the resourcehealth resource provider
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com////providers/Microsoft.ResourceHealth/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/providersmicrosoft-resourcehealthoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/providersmicrosoft-resourcehealthoperations-get-openapi.md
- name: Azure Resource Health API
  x-api-slug: azure-resource-health-api
  description: Resource health helps you diagnose and get support when an Azure issue
    impacts your resources. It informs you about the current and past health of your
    resources and helps you mitigate issues. Resource health provides technical support
    when you need help with Azure service issues.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/openapi.md
x-common:
- type: x-faq
  url: https://docs.microsoft.com/en-us/azure/resource-health/resource-health-faq
- type: x-website
  url: https://docs.microsoft.com/en-us/azure/resource-health/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---