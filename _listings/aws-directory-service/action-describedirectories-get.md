---
swagger: "2.0"
info:
  title: AWS Directory Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeDirectories:
    get:
      summary: ' Describe Directories '
      description: Obtains information about the directories that belong to this account
      operationId: describeDirectories
      parameters:
      - in: query
        name: DirectoryIds
        description: A list of identifiers of the directories for which to obtain
          the information
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: NextToken
        description: The DescribeDirectoriesResult
        type: string
      responses:
        200:
          description: OK
      tags:
      - directories
definitions: []
x-collection-name: AWS Directory Service
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