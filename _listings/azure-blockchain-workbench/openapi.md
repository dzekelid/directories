---
swagger: "2.0"
x-collection-name: Azure Blockchain Workbench
x-complete: 1
info:
  title: Azure Blockchain Workbench REST API
  description: the-azure-blockchain-workbench-rest-api-is-a-workbench-extensibility-point-which-allows-developers-to-create-and-manage-blockchain-applications-manage-users-and-organizations-within-a-consortium-integrate-blockchain-applications-into-services-and-platforms-perform-transactions-on-a-blockchain-and-retrieve-transactional-and-contract-data-from-a-blockchain-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/graphProxy/{version}/users:
    get:
      summary: Get Graph Proxy Version Users
      description: |-
        Represents a proxy method to the Azure Active Directory Graph API for users.
                     See https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/api/user_list for more details.
      operationId: GraphProxy-UsersGet
      x-api-path-slug: apiv1graphproxyversionusers-get
      parameters:
      - in: path
        name: version
        description: The version for the graph api endpoint
      responses:
        200:
          description: OK
      tags:
      - Graph
      - Proxy
      - Version
      - Users
---