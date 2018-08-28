---
name: Google Cloud Machine Learning Engine
x-slug: google-cloud-machine-learning-engine
description: Google Cloud Machine Learning Engine is a managed service that enables
  you to easily build machine learning models, that work on any type of data, of any
  size. Create your model with the powerful TensorFlow framework that powers many
  Google products, from Google Photos to Google Cloud Speech. Build models of any
  size with our managed scalable infrastructure. Your trained model is immediately
  available for use with our global prediction platform that can support thousands
  of users and TBs of data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Operations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Machine Learning Engine - Get Operations
  x-api-slug: v1nameoperations-get
  description: |-
    Lists operations that match the specified filter in the request. If the
    server doesn't support this method, it returns `UNIMPLEMENTED`.

    NOTE: the `name` binding below allows API services to override the binding
    to use different resource name schemes, such as `users/*/operations`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1nameoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1nameoperations-get-openapi.md
- name: Google Cloud Machine Learning Engine - Cancel Operation
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1namecancel-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Operation
  x-api-slug: v1namegetconfig-get
  description: |-
    Get the service account information associated with your project. You need
    this information in order to grant the service account persmissions for
    the Google Cloud Storage location where you put your model training code
    for training the model with Google Cloud Machine Learning.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1namegetconfig-get-openapi.md
- name: Google Cloud Machine Learning Engine - Predict Operation
  x-api-slug: v1namepredict-post
  description: |-
    Performs prediction on the data in the request.

    **** REMOVE FROM GENERATED DOCUMENTATION
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1namepredict-post-openapi.md
- name: Google Cloud Machine Learning Engine - Predict Operation
  x-api-slug: v1namepredict-post
  description: |-
    Performs prediction on the data in the request.

    **** REMOVE FROM GENERATED DOCUMENTATION
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1namepredict-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Operation
  x-api-slug: v1namegetconfig-get
  description: |-
    Get the service account information associated with your project. You need
    this information in order to grant the service account persmissions for
    the Google Cloud Storage location where you put your model training code
    for training the model with Google Cloud Machine Learning.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1namegetconfig-get-openapi.md
- name: Google Cloud Machine Learning Engine - Cancel Operation
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1namecancel-post-openapi.md
- name: Google Cloud Machine Learning Engine - Get Operations
  x-api-slug: v1nameoperations-get
  description: |-
    Lists operations that match the specified filter in the request. If the
    server doesn't support this method, it returns `UNIMPLEMENTED`.

    NOTE: the `name` binding below allows API services to override the binding
    to use different resource name schemes, such as `users/*/operations`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1nameoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-cloud-machine-learning-engine/v1nameoperations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.key.management.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.machine.learning.engine.stack.network
- type: x-change-log
  url: https://cloud.google.com/ml-engine/docs/resources/release-notes
- type: x-command-line-interface
  url: https://cloud.google.com/sdk/gcloud/reference/ml-engine/
- type: x-concepts
  url: https://cloud.google.com/ml-engine/docs/concepts/
- type: x-documentation
  url: https://cloud.google.com/ml-engine/docs/
- type: x-getting-started
  url: https://cloud.google.com/ml-engine/docs/quickstarts/
- type: x-pricing
  url: https://cloud.google.com/ml-engine/pricing
- type: x-rate-limits
  url: https://cloud.google.com/ml-engine/quotas
- type: x-service-level-agreements
  url: https://cloud.google.com/ml-engine/sla
- type: x-support
  url: https://cloud.google.com/ml-engine/docs/resources/support
- type: x-terms-of-service
  url: https://cloud.google.com/terms/
- type: x-tutorials
  url: https://cloud.google.com/ml-engine/docs/tutorials/
- type: x-versioning
  url: https://cloud.google.com/ml-engine/docs/concepts/versioning
- type: x-website
  url: https://cloud.google.com/ml-engine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---