---
name: Google Cloud Container Builder
x-slug: google-cloud-container-builder
description: Google Cloud Container Builder lets you create Docker container images
  from application source code located in Google Cloud Storage. Container images created
  by Container Builder are automatically stored in Google Container Registry. You
  can deploy the container images you create on Google Container Engine, Google Compute
  Engine, Google App Engine flexible environment or other services where you can run
  applications from Docker containers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Operations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-container-builder/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Container Builder - Get Operation State
  x-api-slug: v1name-get
  description: |-
    Gets the latest state of a long-running operation.  Clients can use this
    method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
  humanURL: https://cloud.google.com/container-builder/
  baseURL: ://cloudbuild.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-container-builder/v1name-get-openapi.md
- name: Google Cloud Container Builder - Cancel Operation
  x-api-slug: v1namecancel-post
  description: |-
    Starts asynchronous cancellation on a long-running operation.  The server
    makes a best effort to cancel the operation, but success is not
    guaranteed.  If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.  Clients can use
    Operations.GetOperation or
    other methods to check whether the cancellation succeeded or whether the
    operation completed despite cancellation. On successful cancellation,
    the operation is not deleted; instead, it becomes an operation with
    an Operation.error value with a google.rpc.Status.code of 1,
    corresponding to `Code.CANCELLED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
  humanURL: https://cloud.google.com/container-builder/
  baseURL: ://cloudbuild.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-container-builder/v1namecancel-post-openapi.md
- name: Google Cloud Container Builder - Get Operation State
  x-api-slug: v1name-get
  description: |-
    Gets the latest state of a long-running operation.  Clients can use this
    method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
  humanURL: https://cloud.google.com/container-builder/
  baseURL: ://cloudbuild.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-container-builder/v1name-get-openapi.md
- name: Google Cloud Container Builder - Cancel Operation
  x-api-slug: v1namecancel-post
  description: |-
    Starts asynchronous cancellation on a long-running operation.  The server
    makes a best effort to cancel the operation, but success is not
    guaranteed.  If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.  Clients can use
    Operations.GetOperation or
    other methods to check whether the cancellation succeeded or whether the
    operation completed despite cancellation. On successful cancellation,
    the operation is not deleted; instead, it becomes an operation with
    an Operation.error value with a google.rpc.Status.code of 1,
    corresponding to `Code.CANCELLED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/container-builder-lead.png
  humanURL: https://cloud.google.com/container-builder/
  baseURL: ://cloudbuild.googleapis.com//
  tags: Containers, Google APIs, Stack Network, API Service Provider, API Provider,
    Deployments, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-container-builder/v1namecancel-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.billing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.container.builder.stack.network
- type: x-documentation
  url: https://cloud.google.com/container-builder/docs/
- type: x-pricing
  url: https://cloud.google.com/container-builder/pricing
- type: x-website
  url: https://cloud.google.com/container-builder/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---