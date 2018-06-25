---
name: Azure Storage
x-slug: azure-storage
description: Azure Storage offers non-relational data storage including Blob Storage,
  Table Storage, Queue Storage, and Files.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Operations
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-storage/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Storage API List Supported Operations
  x-api-slug: azure-storage-api
  description: Returns the list of operations supported by the import/export resource
    provider.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////providers/Microsoft.ImportExport/operations
  tags: Supported Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-storage/providersmicrosoft-importexportoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-storage/providersmicrosoft-importexportoperations-get-openapi.md
- name: Azure Storage API Operations List
  x-api-slug: azure-storage-api
  description: Lists all of the available REST API operations of the Microsoft.Storsimple
    provider
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com////providers/Microsoft.StorSimple/operations
  tags: Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-storage/providersmicrosoft-storsimpleoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-storage/providersmicrosoft-storsimpleoperations-get-openapi.md
- name: Azure Storage API
  x-api-slug: azure-storage-api
  description: Azure Storage offers non-relational data storage including Blob Storage,
    Table Storage, Queue Storage, and Files.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-storage.png
  humanURL: https://azure.microsoft.com/en-us/services/storage/
  baseURL: ://management.azure.com//
  tags: Operations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/azure-storage/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/storage/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/storage/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/storage/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/storage/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---