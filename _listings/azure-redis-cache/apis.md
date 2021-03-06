---
name: Azure Redis Cache
x-slug: azure-redis-cache
description: Azure Redis Cache is based on the popular open source Redis cache. It
  gives you access to a secure, dedicated Redis cache, managed by Microsoft and accessible
  from any application within Azure.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Operations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-redis-cache/apis.md
specificationVersion: "0.14"
apis:
- name: RedisManagementClient - Operations List
  x-api-slug: providersmicrosoft-cacheoperations-get
  description: Lists all of the available REST API operations of the Microsoft.Cache
    provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-redis-cache-performance.png
  humanURL: https://azure.microsoft.com/en-us/services/cache/
  baseURL: ://management.azure.com//
  tags: Caching, Microsoft, Stack Network, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-redis-cache/providersmicrosoft-cacheoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-redis-cache/providersmicrosoft-cacheoperations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.recovery.services.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.redis.cache.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/redis-cache/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cache/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/cache/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cache/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---