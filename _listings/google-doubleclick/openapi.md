---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 1
info:
  title: Google Doubleclick Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/directorySites:
    get:
      summary: Get Directory Sites
      description: Retrieves a list of directory sites, possibly filtered. This method
        supports paging.
      operationId: dfareporting.directorySites.list
      x-api-path-slug: userprofilesprofileiddirectorysites-get
      parameters:
      - in: query
        name: acceptsInStreamVideoPlacements
        description: This search filter is no longer supported and will have no effect
          on the results returned
      - in: query
        name: acceptsInterstitialPlacements
        description: This search filter is no longer supported and will have no effect
          on the results returned
      - in: query
        name: acceptsPublisherPaidPlacements
        description: Select only directory sites that accept publisher paid placements
      - in: query
        name: active
        description: Select only active directory sites
      - in: query
        name: countryId
        description: Select only directory sites with this country ID
      - in: query
        name: dfp_network_code
        description: Select only directory sites with this DFP network code
      - in: query
        name: ids
        description: Select only directory sites with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: query
        name: parentId
        description: Select only directory sites with this parent ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name, ID or URL
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Directory Site
    post:
      summary: Insert Directory Site
      description: Inserts a new directory site.
      operationId: dfareporting.directorySites.insert
      x-api-path-slug: userprofilesprofileiddirectorysites-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Directory Site
  /userprofiles/{profileId}/directorySites/{id}:
    get:
      summary: Get Directory Site
      description: Gets one directory site by ID.
      operationId: dfareporting.directorySites.get
      x-api-path-slug: userprofilesprofileiddirectorysitesid-get
      parameters:
      - in: path
        name: id
        description: Directory site ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Directory Site
---