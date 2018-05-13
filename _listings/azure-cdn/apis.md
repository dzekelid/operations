---
name: Azure CDN
description: Ensuring a consistent user experience is important. If your websites
  or mobile apps involve streaming media, gaming software, firmware updates (Smart
  TVs, consumer electronic appliances) or IoT endpoints (cars, sensors), Content Delivery
  Network helps you reduce load times, save bandwidth, and increase responsiveness.
image: ""
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Microsoft
- CDN
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-cdn/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure CDN API
  description: Ensuring a consistent user experience is important
  image: ""
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-cdn/providers-microsoft-cdn-operations-get.md
- name: Azure CDN API List Operations
  description: Lists all of the available CDN REST API operations.
  image: ""
  humanURL: https://azure.microsoft.com/en-us/services/cdn/
  baseURL: http:://management.azure.com//
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-cdn/providers-microsoft-cdn-operations-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-cdn/providers-microsoft-cdn-operations-get-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cdn/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cdn/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cdn/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cdn/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cdn/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cdn/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---