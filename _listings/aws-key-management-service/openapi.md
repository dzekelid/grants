swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 1
info:
  title: AWS Key Management Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateGrant:
    get:
      summary: Create Grant
      description: Adds a grant to a key to specify who can use the key and under
        what conditions.
      operationId: createGrant
      x-api-path-slug: actioncreategrant-get
      parameters:
      - in: query
        name: Constraints
        description: The conditions under which the operations permitted by the grant
          are allowed
        type: string
      - in: query
        name: GranteePrincipal
        description: The principal that is given permission to perform the operations
          that the grant      permits
        type: string
      - in: query
        name: GrantTokens
        description: A list of grant tokens
        type: string
      - in: query
        name: KeyId
        description: The unique identifier for the customer master key (CMK) that
          the grant applies      to
        type: string
      - in: query
        name: Name
        description: A friendly name for identifying the grant
        type: string
      - in: query
        name: Operations
        description: A list of operations that the grant permits
        type: string
      - in: query
        name: RetiringPrincipal
        description: The principal that is given permission to retire the grant by
          using RetireGrant operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Grants
  /?Action=ListGrants:
    get:
      summary: List Grants
      description: List the grants for a specified key.
      operationId: listGrants
      x-api-path-slug: actionlistgrants-get
      parameters:
      - in: query
        name: KeyId
        description: A unique identifier for the customer master key
        type: string
      - in: query
        name: Limit
        description: When paginating results, specify the maximum number of items
          to return in the response
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only in a
          subsequent request after      you receive a response with truncated results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Grants
  /?Action=ListRetirableGrants:
    get:
      summary: List Retirable Grants
      description: |-
        Returns a list of all grants for which the grant's RetiringPrincipal
              matches the one specified.
      operationId: listRetirableGrants
      x-api-path-slug: actionlistretirablegrants-get
      parameters:
      - in: query
        name: Limit
        description: When paginating results, specify the maximum number of items
          to return in the response
        type: string
      - in: query
        name: Marker
        description: Use this parameter only when paginating results and only in a
          subsequent request after      you receive a response with truncated results
        type: string
      - in: query
        name: RetiringPrincipal
        description: The retiring principal for which to list grants
        type: string
      responses:
        200:
          description: OK
      tags:
      - Grants
  /?Action=RetireGrant:
    get:
      summary: Retire Grant
      description: Retires a grant.
      operationId: retireGrant
      x-api-path-slug: actionretiregrant-get
      parameters:
      - in: query
        name: GrantId
        description: Unique identifier of the grant to retire
        type: string
      - in: query
        name: GrantToken
        description: Token that identifies the grant to be retired
        type: string
      - in: query
        name: KeyId
        description: The Amazon Resource Name of the CMK associated with the grant
        type: string
      responses:
        200:
          description: OK
      tags:
      - Grants
  /?Action=RevokeGrant:
    get:
      summary: Revoke Grant
      description: Revokes a grant.
      operationId: revokeGrant
      x-api-path-slug: actionrevokegrant-get
      parameters:
      - in: query
        name: GrantId
        description: Identifier of the grant to be revoked
        type: string
      - in: query
        name: KeyId
        description: A unique identifier for the customer master key associated with
          the grant
        type: string
      responses:
        200:
          description: OK
      tags:
      - Grants