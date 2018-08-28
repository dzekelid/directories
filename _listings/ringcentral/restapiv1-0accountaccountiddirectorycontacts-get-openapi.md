---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Corporate Directory Contacts
  description: |-
    Returns contact information on corporate users of federated accounts. Please note: 1. User, DigitalUser, VirtualUser and FaxUser types are returned as User type. 2.ApplicationExtension type is not returned. 3. Only extensions in Enabled, Disabled and NotActivated state are returned.
    App Permission
    ReadAccounts
    Usage Plan Group
    Medium
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/account/{accountId}/directory/contacts:
    get:
      summary: Get Corporate Directory Contacts
      description: |-
        Returns contact information on corporate users of federated accounts. Please note: 1. User, DigitalUser, VirtualUser and FaxUser types are returned as User type. 2.ApplicationExtension type is not returned. 3. Only extensions in Enabled, Disabled and NotActivated state are returned.
        App Permission
        ReadAccounts
        Usage Plan Group
        Medium
      operationId: listDirectoryContacts
      x-api-path-slug: restapiv1-0accountaccountiddirectorycontacts-get
      parameters:
      - in: path
        name: accountId
        description: accountId
      - in: query
        name: excludeFederatedContacts
        description: excludeFederatedContacts
      - in: header
        name: If-None-Match
        description: If-None-Match
      - in: query
        name: page
        description: page
      - in: query
        name: perPage
        description: perPage
      - in: query
        name: siteId
        description: Internal identifier of the business site to which extensions
          belongs
      - in: query
        name: type
        description: Type of an extension
      responses:
        200:
          description: OK
      tags:
      - Corporate
      - Directory
      - Contacts
  /restapi/v1.0/account/{accountId}/directory/contacts/{contactId}:
    get:
      summary: Get Corporate Directory Contact
      description: |-
        Returns contact information on a particular corporate user of a federated account.
        App Permission
        ReadAccounts
        Usage Plan Group
        Medium
      operationId: loadDirectoryContact
      x-api-path-slug: restapiv1-0accountaccountiddirectorycontactscontactid-get
      parameters:
      - in: path
        name: accountId
        description: Internal identifier of owning account
      - in: path
        name: contactId
        description: Internal identifier of extension to read information for
      responses:
        200:
          description: OK
      tags:
      - Corporate
      - Directory
      - Contact
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