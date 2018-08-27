---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 1
info:
  title: RingCentral Connect Platform API Explorer
  description: this-is-an-interactive-api-explorer-for-the-ringcentral-connect-platform--to-use-this-service-you-will-need-to-have-a-developer-account---links--a-hrefhttpsnetstorage-ringcentral-comdpwapiexplorerrcplatform-basic-ymlv20180514092722-target-blankringcentral-api-specaspannbspnbspopenapi-fka-swagger-formatnbspnbspnbspnbspspana-hrefhttpsgithub-comoaiopenapispecification-target-blanklearn-more-about-openapia
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
---