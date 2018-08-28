---
swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 0
info:
  title: AWS Directory Service API Create Directory
  version: 1.0.0
  description: Creates a Simple AD directory.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ConnectDirectory:
    get:
      summary: Connect Directory
      description: Creates an AD Connector to connect to an on-premises directory.
      operationId: connectDirectory
      x-api-path-slug: actionconnectdirectory-get
      parameters:
      - in: query
        name: ConnectSettings
        description: A DirectoryConnectSettings object that contains additional information
          for the         operation
        type: string
      - in: query
        name: Description
        description: A textual description for the directory
        type: string
      - in: query
        name: Name
        description: The fully-qualified name of the on-premises directory, such as            corp
        type: string
      - in: query
        name: Password
        description: The password for the on-premises user account
        type: string
      - in: query
        name: ShortName
        description: The NetBIOS name of the on-premises directory, such as CORP
        type: string
      - in: query
        name: Size
        description: The size of the directory
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
  /?Action=CreateDirectory:
    get:
      summary: Create Directory
      description: Creates a Simple AD directory.
      operationId: createDirectory
      x-api-path-slug: actioncreatedirectory-get
      parameters:
      - in: query
        name: Description
        description: A textual description for the directory
        type: string
      - in: query
        name: Name
        description: The fully qualified name for the directory, such as corp
        type: string
      - in: query
        name: Password
        description: The password for the directory administrator
        type: string
      - in: query
        name: ShortName
        description: The short name of the directory, such as CORP
        type: string
      - in: query
        name: Size
        description: The size of the directory
        type: string
      - in: query
        name: VpcSettings
        description: A DirectoryVpcSettings object that contains additional information
          for the         operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
  /?Action=DeleteDirectory:
    get:
      summary: Delete Directory
      description: Deletes an AWS Directory Service directory.
      operationId: deleteDirectory
      x-api-path-slug: actiondeletedirectory-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
  /?Action=DescribeDirectories:
    get:
      summary: Describe Directories
      description: Obtains information about the directories that belong to this account.
      operationId: describeDirectories
      x-api-path-slug: actiondescribedirectories-get
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
      - Directories
  /?Action=GetDirectoryLimits:
    get:
      summary: Get Directory Limits
      description: Obtains directory limit information for the current region.
      operationId: getDirectoryLimits
      x-api-path-slug: actiongetdirectorylimits-get
      parameters:
      - in: query
        name: DirectoryLimits
        description: A DirectoryLimits object that contains the directory limits for
          the current         region
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directories
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