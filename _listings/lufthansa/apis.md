---
name: Lufthansa
x-slug: lufthansa
description: Book your flights to Germany, Italy, UK or France online at attractive
  low fares. Fly via Frankfurt, Munich or Zurich - Lufthansa United States of America
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
x-kinRank: "7"
x-alexaRank: "3886"
tags: Operations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/apis.md
specificationVersion: "0.14"
apis:
- name: LH Public - Flight Status at Arrival Airport
  x-api-slug: operationsflightstatusarrivalsairportcodefromdatetime-get
  description: Status of all arrivals at a given airport up to 4 hours from the provided
    date time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1
  tags: Airlines, API Provider, Profiles, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusarrivalsairportcodefromdatetime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusarrivalsairportcodefromdatetime-get-openapi.md
- name: LH Public - Flight Status at Departure Airport
  x-api-slug: operationsflightstatusdeparturesairportcodefromdatetime-get
  description: Status of all departures from a given airport up to 4 hours from the
    provided date time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1
  tags: Airlines, API Provider, Profiles, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusdeparturesairportcodefromdatetime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusdeparturesairportcodefromdatetime-get-openapi.md
- name: LH Public - Flight Status by Route
  x-api-slug: operationsflightstatusrouteorigindestinationdate-get
  description: Status of flights between a given origin and destination on a given
    date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1
  tags: Airlines, API Provider, Profiles, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusrouteorigindestinationdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusrouteorigindestinationdate-get-openapi.md
- name: LH Public - Flight Status
  x-api-slug: operationsflightstatusflightnumberdate-get
  description: Status of a particular flight (boarding, delayed, etc.).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1
  tags: Airlines, API Provider, Profiles, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusflightnumberdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsflightstatusflightnumberdate-get-openapi.md
- name: LH Public - Flight Schedules
  x-api-slug: operationsschedulesorigindestinationfromdatetime-get
  description: Scheduled flights between given airports on a given date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1
  tags: Airlines, API Provider, Profiles, General Data, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsschedulesorigindestinationfromdatetime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/operations/master/_listings/lufthansa/operationsschedulesorigindestinationfromdatetime-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://lota.data.api.gallery.streamdata.io
- type: x-api-stack
  url: http://lufthansa.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/lufthansa
- type: x-twitter
  url: https://twitter.com/lufthansa
- type: x-website
  url: http://lufthansa.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---