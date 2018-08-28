swagger: "2.0"
x-collection-name: AWS Directory Service
x-complete: 1
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
  /?Action=CreateTrust:
    get:
      summary: Create Trust
      description: AWS Directory Service for Microsoft Active Directory allows you
        to configure trust relationships.
      operationId: createTrust
      x-api-path-slug: actioncreatetrust-get
      parameters:
      - in: query
        name: ConditionalForwarderIpAddrs
        description: The IP addresses of the remote DNS server associated with RemoteDomainName
        type: string
      - in: query
        name: DirectoryId
        description: The Directory ID of the Microsoft AD in the AWS cloud for which
          to establish the trust relationship
        type: string
      - in: query
        name: RemoteDomainName
        description: The Fully Qualified Domain Name (FQDN) of the external domain
          for which to create the trust relationship
        type: string
      - in: query
        name: TrustDirection
        description: The direction of the trust relationship
        type: string
      - in: query
        name: TrustPassword
        description: The trust password
        type: string
      - in: query
        name: TrustType
        description: The trust relationship type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trust
  /?Action=ListSchemaExtensions:
    get:
      summary: List Schema Extensions
      description: Lists all schema extensions applied to a Microsoft AD Directory.
      operationId: listSchemaExtensions
      x-api-path-slug: actionlistschemaextensions-get
      parameters:
      - in: query
        name: DirectoryId
        description: The identifier of the directory from which to retrieve the schema
          extension information
        type: string
      - in: query
        name: Limit
        description: The maximum number of items to return
        type: string
      - in: query
        name: NextToken
        description: The ListSchemaExtensions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Schema Extension
  /?Action=VerifyTrust:
    get:
      summary: Verify Trust
      description: AWS Directory Service for Microsoft Active Directory allows you
        to configure and verify trust relationships.
      operationId: verifyTrust
      x-api-path-slug: actionverifytrust-get
      parameters:
      - in: query
        name: TrustId
        description: The unique Trust ID of the trust relationship to verify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Trust