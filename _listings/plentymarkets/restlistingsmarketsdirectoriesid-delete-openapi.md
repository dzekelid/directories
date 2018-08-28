---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets Delete listing market directory
  description: Deletes a listing market directory by ID.
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/listings/markets/directories:
    get:
      summary: Get all listing market directories
      description: Gets all listing market directories.
      operationId: getRestListingsMarketsDirectories
      x-api-path-slug: restlistingsmarketsdirectories-get
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Market
      - Directories
    post:
      summary: Create listing market directory
      description: Creates a listing market directory.
      operationId: postRestListingsMarketsDirectories
      x-api-path-slug: restlistingsmarketsdirectories-post
      parameters:
      - in: body
        name: /rest/listings/markets/directories
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Market
      - Directory
  /rest/accounts/contacts/{contactId}/document:
    post:
      summary: Upload a document to contact directory
      description: Upload a document to contact directory.
      operationId: postRestAccountsContactsContactDocument
      x-api-path-slug: restaccountscontactscontactiddocument-post
      parameters:
      - in: path
        name: contactId
      - in: query
        name: key
        description: The storage key for the file to upload
      responses:
        200:
          description: OK
      tags:
      - Upload
      - Document
      - To
      - Contact
      - Directory
  /rest/listings/markets/directories/{id}:
    delete:
      summary: Delete listing market directory
      description: Deletes a listing market directory by ID.
      operationId: deleteRestListingsMarketsDirectories
      x-api-path-slug: restlistingsmarketsdirectoriesid-delete
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Market
      - Directory
    get:
      summary: Get a listing market directory
      description: Gets a listing market directory by ID.
      operationId: getRestListingsMarketsDirectories
      x-api-path-slug: restlistingsmarketsdirectoriesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Market
      - Directory
    put:
      summary: Update listing market directory
      description: Updates a listing market directory by ID.
      operationId: putRestListingsMarketsDirectories
      x-api-path-slug: restlistingsmarketsdirectoriesid-put
      parameters:
      - in: body
        name: /rest/listings/markets/directories/{id}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Listing
      - Market
      - Directory
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