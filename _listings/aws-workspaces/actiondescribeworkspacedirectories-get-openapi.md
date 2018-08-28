---
swagger: "2.0"
x-collection-name: AWS WorkSpaces
x-complete: 0
info:
  title: AWS WorkSpaces Service API Describe Workspace Directories
  version: 1.0.0
  description: Retrieves information about the AWS Directory Service directories in
    the region that are registered with Amazon WorkSpaces and are available to your
    account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeWorkspaceDirectories:
    get:
      summary: Describe Workspace Directories
      description: Retrieves information about the AWS Directory Service directories
        in the region that are registered with Amazon WorkSpaces and are available
        to your account.
      operationId: describeWorkspaceDirectories
      x-api-path-slug: actiondescribeworkspacedirectories-get
      parameters:
      - in: query
        name: DirectoryIds
        description: An array of strings that contains the directory identifiers to
          retrieve information for
        type: string
      - in: query
        name: NextToken
        description: The NextToken value from a previous call to this operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Workspace Directories
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