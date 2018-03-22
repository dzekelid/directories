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
  /?Action=ConnectDirectory:
    get:
      summary: ' Connect Directory '
      description: Creates an AD Connector to connect to an on-premises directory
      operationId: connectDirectory
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