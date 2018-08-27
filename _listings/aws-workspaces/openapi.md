---
swagger: "2.0"
x-collection-name: AWS WorkSpaces
x-complete: 1
info:
  title: AWS WorkSpaces Service API
  version: 1.0.0
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
---