swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /directoryObjects/{id}:
    delete:
      summary: Delete Directory Object
      description: Delete directoryObject Deletes a directoryObject.
      operationId: DeleteDirectoryObject
      x-api-path-slug: directoryobjectsid-delete
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Object
    get:
      summary: Get Directory Object
      description: Get directoryObject Retrieve the properties and relationships of
        directoryObject object.
      operationId: GetDirectoryObject
      x-api-path-slug: directoryobjectsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Object
  /directoryRoles/{id}:
    get:
      summary: Get Directory Role
      description: Get directoryRole Retrieve the properties of a directoryRole object.
      operationId: GetDirectoryRole
      x-api-path-slug: directoryrolesid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Role
  /directoryRoles:
    get:
      summary: List Directory Roles
      description: List directoryRoles List the directory roles that are activated
        in the tenant.
      operationId: ListDirectoryRoles
      x-api-path-slug: directoryroles-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Directory
      - Roles
    post:
      summary: Activate Directory Role
      description: Activate directoryRole Activate a directory role. To read a directory
        role or update its members, it must first be activated in the tenant. Only
        the Company Administrators and the implicit Users directory roles are activated
        by default. To access and assign members to another directory role, you must
        first activate it with its corresponding directory role template (directoryRoleTemplate).
      operationId: ActivateDirectoryRole
      x-api-path-slug: directoryroles-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Directory
      - Role
  /directoryRoles/{id}/members/$ref:
    post:
      summary: Add Directory Role Member
      description: Add directory role member Use this API to create a new directory
        role member.
      operationId: AddDirectoryRoleMember
      x-api-path-slug: directoryrolesidmembersref-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Role
      - Member
  /directoryRoleTemplates/{id}:
    get:
      summary: Get Directory Role Template
      description: Get directoryRoleTemplate Retrieve the properties and relationships
        of a directoryroletemplate object.
      operationId: GetDirectoryRoleTemplate
      x-api-path-slug: directoryroletemplatesid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Role
      - Template
  /directoryRoleTemplates:
    get:
      summary: List Directory Role Templates
      description: List directoryRoleTemplates Retrieve a list of directoryRoleTemplate
        objects.
      operationId: ListDirectoryRoleTemplates
      x-api-path-slug: directoryroletemplates-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Directory
      - Role
      - Templates