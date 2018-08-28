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
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft.ResourceHealth - Operations List
  x-api-slug: providersmicrosoft-resourcehealthoperations-get
  description: Lists available operations for the resourcehealth resource provider
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-health.png
  humanURL: https://docs.microsoft.com/en-us/azure/resource-health/
  baseURL: ://management.azure.com//
  tags: Microsoft, Monitoring, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/providersmicrosoft-resourcehealthoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-resource-health/providersmicrosoft-resourcehealthoperations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.redis.cache.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.resource.health.stack.network
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