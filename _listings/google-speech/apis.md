---
name: Google Speech
x-slug: google-speech
description: Google Cloud Speech API enables developers to convert audio to text by
  applying powerful neural network models in an easy to use API. The API recognizes
  over 80 languages and variants, to support your global user base. You can transcribe
  the text of users dictating to an application&rsquo;s microphone, enable command-and-control
  through voice, or transcribe audio files, among many other use cases. Recognize
  audio uploaded in the request, and integrate with your audio storage on Google Cloud
  Storage, by using the same technology Google uses to power its own products.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Operations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Speech - Get Operations
  x-api-slug: v1beta1operations-get
  description: |-
    Lists operations that match the specified filter in the request. If the
    server doesn't support this method, it returns `UNIMPLEMENTED`.

    NOTE: the `name` binding below allows API services to override the binding
    to use different resource name schemes, such as `users/*/operations`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operations-get-openapi.md
- name: Google Cloud Speech - Delete Operation
  x-api-slug: v1beta1operationsname-delete
  description: |-
    Deletes a long-running operation. This method indicates that the client is
    no longer interested in the operation result. It does not cancel the
    operation. If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-delete-openapi.md
- name: Google Cloud Speech - Delete Operation
  x-api-slug: v1beta1operationsname-get
  description: |-
    Gets the latest state of a long-running operation.  Clients can use this
    method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-get-openapi.md
- name: Google Cloud Speech - Cancel Operation
  x-api-slug: v1beta1operationsnamecancel-post
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsnamecancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsnamecancel-post-openapi.md
- name: Google Cloud Speech - Cancel Operation
  x-api-slug: v1beta1operationsnamecancel-post
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsnamecancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsnamecancel-post-openapi.md
- name: Google Cloud Speech - Delete Operation
  x-api-slug: v1beta1operationsname-get
  description: |-
    Gets the latest state of a long-running operation.  Clients can use this
    method to poll the operation result at intervals as recommended by the API
    service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-get-openapi.md
- name: Google Cloud Speech - Delete Operation
  x-api-slug: v1beta1operationsname-delete
  description: |-
    Deletes a long-running operation. This method indicates that the client is
    no longer interested in the operation result. It does not cancel the
    operation. If the server doesn't support this method, it returns
    `google.rpc.Code.UNIMPLEMENTED`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operationsname-delete-openapi.md
- name: Google Cloud Speech - Get Operations
  x-api-slug: v1beta1operations-get
  description: |-
    Lists operations that match the specified filter in the request. If the
    server doesn't support this method, it returns `UNIMPLEMENTED`.

    NOTE: the `name` binding below allows API services to override the binding
    to use different resource name schemes, such as `users/*/operations`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/speech-api-lead_2x.png
  humanURL: https://cloud.google.com/speech/
  baseURL: ://speech.googleapis.com//
  tags: Google APIs, Speech Recognition, Machine Learning, Stack Network, API Service
    Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/google-speech/v1beta1operations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.spectrum.database.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.speech.stack.network
- type: x-code
  url: https://cloud.google.com/speech/docs/reference/libraries
- type: x-concepts
  url: https://cloud.google.com/speech/docs/best-practices
- type: x-documentation
  url: https://cloud.google.com/speech/docs/
- type: x-getting-started
  url: https://cloud.google.com/speech/docs/getting-started
- type: x-guides
  url: https://cloud.google.com/speech/docs/common/auth
- type: x-pricing
  url: https://cloud.google.com/speech/pricing
- type: x-rate-limits
  url: https://cloud.google.com/speech/limits
- type: x-samples
  url: https://cloud.google.com/speech/docs/samples
- type: x-website
  url: https://cloud.google.com/speech/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---