---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Directories
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph API - Delete Directory Object
  x-api-slug: directoryobjectsid-delete
  description: Delete directoryObject Deletes a directoryObject.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-delete-openapi.md
- name: Microsoft Graph API - Get Directory Object
  x-api-slug: directoryobjectsid-get
  description: Get directoryObject Retrieve the properties and relationships of directoryObject
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-get-openapi.md
- name: Microsoft Graph API - Get Directory Role
  x-api-slug: directoryrolesid-get
  description: Get directoryRole Retrieve the properties of a directoryRole object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesid-get-openapi.md
- name: Microsoft Graph API - List Directory Roles
  x-api-slug: directoryroles-get
  description: List directoryRoles List the directory roles that are activated in
    the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-get-openapi.md
- name: Microsoft Graph API - Activate Directory Role
  x-api-slug: directoryroles-post
  description: Activate directoryRole Activate a directory role. To read a directory
    role or update its members, it must first be activated in the tenant. Only the
    Company Administrators and the implicit Users directory roles are activated by
    default. To access and assign members to another directory role, you must first
    activate it with its corresponding directory role template (directoryRoleTemplate).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-post-openapi.md
- name: Microsoft Graph API - Add Directory Role Member
  x-api-slug: directoryrolesidmembersref-post
  description: Add directory role member Use this API to create a new directory role
    member.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesidmembersref-post-openapi.md
- name: Microsoft Graph API - Get Directory Role Template
  x-api-slug: directoryroletemplatesid-get
  description: Get directoryRoleTemplate Retrieve the properties and relationships
    of a directoryroletemplate object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplatesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplatesid-get-openapi.md
- name: Microsoft Graph API - List Directory Role Templates
  x-api-slug: directoryroletemplates-get
  description: List directoryRoleTemplates Retrieve a list of directoryRoleTemplate
    objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplates-get-openapi.md
- name: Microsoft Graph API - Delete Directory Object
  x-api-slug: directoryobjectsid-delete
  description: Delete directoryObject Deletes a directoryObject.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-delete-openapi.md
- name: Microsoft Graph API - Delete Directory Object
  x-api-slug: directoryobjectsid-delete
  description: Delete directoryObject Deletes a directoryObject.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-delete-openapi.md
- name: Microsoft Graph API - Get Directory Object
  x-api-slug: directoryobjectsid-get
  description: Get directoryObject Retrieve the properties and relationships of directoryObject
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-get-openapi.md
- name: Microsoft Graph API - Get Directory Object
  x-api-slug: directoryobjectsid-get
  description: Get directoryObject Retrieve the properties and relationships of directoryObject
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryobjectsid-get-openapi.md
- name: Microsoft Graph API - Get Directory Role
  x-api-slug: directoryrolesid-get
  description: Get directoryRole Retrieve the properties of a directoryRole object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesid-get-openapi.md
- name: Microsoft Graph API - Get Directory Role
  x-api-slug: directoryrolesid-get
  description: Get directoryRole Retrieve the properties of a directoryRole object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesid-get-openapi.md
- name: Microsoft Graph API - List Directory Roles
  x-api-slug: directoryroles-get
  description: List directoryRoles List the directory roles that are activated in
    the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-get-openapi.md
- name: Microsoft Graph API - List Directory Roles
  x-api-slug: directoryroles-get
  description: List directoryRoles List the directory roles that are activated in
    the tenant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-get-openapi.md
- name: Microsoft Graph API - Activate Directory Role
  x-api-slug: directoryroles-post
  description: Activate directoryRole Activate a directory role. To read a directory
    role or update its members, it must first be activated in the tenant. Only the
    Company Administrators and the implicit Users directory roles are activated by
    default. To access and assign members to another directory role, you must first
    activate it with its corresponding directory role template (directoryRoleTemplate).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-post-openapi.md
- name: Microsoft Graph API - Activate Directory Role
  x-api-slug: directoryroles-post
  description: Activate directoryRole Activate a directory role. To read a directory
    role or update its members, it must first be activated in the tenant. Only the
    Company Administrators and the implicit Users directory roles are activated by
    default. To access and assign members to another directory role, you must first
    activate it with its corresponding directory role template (directoryRoleTemplate).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroles-post-openapi.md
- name: Microsoft Graph API - Add Directory Role Member
  x-api-slug: directoryrolesidmembersref-post
  description: Add directory role member Use this API to create a new directory role
    member.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesidmembersref-post-openapi.md
- name: Microsoft Graph API - Add Directory Role Member
  x-api-slug: directoryrolesidmembersref-post
  description: Add directory role member Use this API to create a new directory role
    member.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryrolesidmembersref-post-openapi.md
- name: Microsoft Graph API - Get Directory Role Template
  x-api-slug: directoryroletemplatesid-get
  description: Get directoryRoleTemplate Retrieve the properties and relationships
    of a directoryroletemplate object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplatesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplatesid-get-openapi.md
- name: Microsoft Graph API - Get Directory Role Template
  x-api-slug: directoryroletemplatesid-get
  description: Get directoryRoleTemplate Retrieve the properties and relationships
    of a directoryroletemplate object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplatesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplatesid-get-openapi.md
- name: Microsoft Graph API - List Directory Role Templates
  x-api-slug: directoryroletemplates-get
  description: List directoryRoleTemplates Retrieve a list of directoryRoleTemplate
    objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplates-get-openapi.md
- name: Microsoft Graph API - List Directory Role Templates
  x-api-slug: directoryroletemplates-get
  description: List directoryRoleTemplates Retrieve a list of directoryRoleTemplate
    objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Microsoft, Files, Notes, Tasks, Stack Network, API Provider, Contacts, Emails,
    Profiles, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/directories/master/_listings/microsoft-graph/directoryroletemplates-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://messente.api.gallery.streamdata.io
- type: x-api-stack
  url: http://microsoft.graph.stack.network
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---