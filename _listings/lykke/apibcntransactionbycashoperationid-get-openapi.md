---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Bcntransactionbycashoperation
  version: 1.0.0
  description: Get api bcntransactionbycashoperation.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/operations/ForwardWithdrawal:
    post:
      summary: Add API Operations Forwardwithdrawal
      description: Add api operations forwardwithdrawal.
      operationId: ApiOperationsForwardWithdrawalPost
      x-api-path-slug: apioperationsforwardwithdrawal-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: data
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Forwardwithdrawal
  /api/Operations/unsignedTransactions:
    get:
      summary: Get API Operations Unsignedtransactions
      description: Get api operations unsignedtransactions.
      operationId: ApiOperationsUnsignedTransactionsGet
      x-api-path-slug: apioperationsunsignedtransactions-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Unsignedtransactions
    post:
      summary: Add API Operations Unsignedtransactions
      description: Add api operations unsignedtransactions.
      operationId: ApiOperationsUnsignedTransactionsPost
      x-api-path-slug: apioperationsunsignedtransactions-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Unsignedtransactions
  /api/Operations/list/{status}:
    get:
      summary: Get API Operations List Status
      description: Get api operations list status.
      operationId: ApiOperationsListByStatusGet
      x-api-path-slug: apioperationsliststatus-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: status
      responses:
        200:
          description: OK
      tags:
      - Operations
      - List
      - Status
  /api/Operations/{id}:
    get:
      summary: Get API Operations
      description: Get api operations.
      operationId: ApiOperationsByIdGet
      x-api-path-slug: apioperationsid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Operations
  /api/Operations/{id}/cancel:
    post:
      summary: Add API Operations  Cancel
      description: Add api operations  cancel.
      operationId: ApiOperationsByIdCancelPost
      x-api-path-slug: apioperationsidcancel-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Operations
      - ""
      - Cancel
  /api/Operations/cancel:
    post:
      summary: Add API Operations Cancel
      description: Add api operations cancel.
      operationId: ApiOperationsCancelPost
      x-api-path-slug: apioperationscancel-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Cancel
  /api/Ethereum/{operationId}/transfer:
    post:
      summary: Add API Ethereum Operation Transfer
      description: Add api ethereum operation transfer.
      operationId: ApiEthereumByOperationIdTransferPost
      x-api-path-slug: apiethereumoperationidtransfer-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - Ethereum
      - Operation
      - Transfer
  /api/Ethereum/{operationId}/hash:
    post:
      summary: Add API Ethereum Operation Hash
      description: Add api ethereum operation hash.
      operationId: ApiEthereumByOperationIdHashPost
      x-api-path-slug: apiethereumoperationidhash-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - Ethereum
      - Operation
      - Hash
  /api/offchain/{operationId}/transferToTrusted:
    post:
      summary: Add API Offchain Operation Transfertotrusted
      description: Add api offchain operation transfertotrusted.
      operationId: ApiOffchainByOperationIdTransferToTrustedPost
      x-api-path-slug: apioffchainoperationidtransfertotrusted-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - Offchain
      - Operation
      - Transfertotrusted
  /api/TrustedWallets/{operationId}/transfer:
    post:
      summary: Add API Trustedwallets Operation Transfer
      description: Add api trustedwallets operation transfer.
      operationId: Transfer
      x-api-path-slug: apitrustedwalletsoperationidtransfer-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: operationId
      responses:
        200:
          description: OK
      tags:
      - Trustedwallets
      - Operation
      - Transfer
  /api/BcnTransactionByCashOperation/{id}:
    get:
      summary: Get API Bcntransactionbycashoperation
      description: Get api bcntransactionbycashoperation.
      operationId: ApiBcnTransactionByCashOperationByIdGet
      x-api-path-slug: apibcntransactionbycashoperationid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Bcntransactionbycashoperation
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