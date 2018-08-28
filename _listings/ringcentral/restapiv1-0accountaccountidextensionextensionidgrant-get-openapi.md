---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Extension Grants
  description: "Returns the list of extension grants.\nApp Permission\nReadAccounts\nUser
    Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n   HTTP
    Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin to extension
    required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-408\nIn
    order to call this API endpoint, user needs to have [ReadExtensionGrant] permission
    for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
    is not found"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/extension/{extensionId}/grant:
    get:
      summary: Get Extension Grants
      description: "Returns the list of extension grants.\nApp Permission\nReadAccounts\nUser
        Permission\nReadExtensions\nUsage Plan Group\nLight\nError Codes\n\n \n  \n
        \  HTTP Code\n   Error Code\n   Error Message\n   \n \n\n401\nCMN-405\nLogin
        to extension required\n\n\n401\nOAU-151\nAuthorization method not supported\n\n\n403\nCMN-408\nIn
        order to call this API endpoint, user needs to have [ReadExtensionGrant] permission
        for requested resource.\n\n\n404\nCMN-102\nResource for parameter [accountId]
        is not found"
      operationId: listExtensionGrants
      x-api-path-slug: restapiv1-0accountaccountidextensionextensionidgrant-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of a RingCentral account or tilde (~) to
          indicate the account logged-in within the current session
      - in: path
        name: extensionId
        description: Internal identifier of an extension or tilde (~) to indicate
          the extension assigned to the account logged-in within the current session
      - in: query
        name: page
      - in: query
        name: perPage
      responses:
        200:
          description: OK
      tags:
      - Extension
      - Grants
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