---
swagger: "2.0"
x-collection-name: Azure Blockchain Workbench
x-complete: 0
info:
  title: Azure Blockchain Workbench Get Graph Proxy Version Users
  description: |-
    Represents a proxy method to the Azure Active Directory Graph API for users.
                 See https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/api/user_list for more details.
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