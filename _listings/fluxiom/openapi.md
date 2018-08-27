swagger: "2.0"
x-collection-name: Fluxiom
x-complete: 1
info:
  title: Fluxiom API
  description: the-fluxiom-api-allows-you-to-hook-into-fluxiom-and-connect-it-with-other-apps-
  termsOfService: http://www.fluxiom.com/terms
  version: v1
host: '{subdomain}.fluxiom.com'
basePath: /api/{format}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/assets:
    get:
      summary: Get assets
      description: Get assets
      operationId: get-assets
      x-api-path-slug: apiassets-get
      parameters:
      - in: query
        name: page
        description: page  tt integer tt current page number (defaults to 1)
      - in: query
        name: per_page
        description: per_page  tt integer tt number of items per page (max
      - in: query
        name: query
        description: query tt string tt search term
      - in: query
        name: tags
        description: tags  tt string tt tag names or IDs, comma separated
      responses:
        200:
          description: OK
      tags:
      - Assets
    post:
      summary: Create asset
      description: Create asset
      operationId: create-asset
      x-api-path-slug: apiassets-post
      parameters:
      - in: query
        name: description
        description: description   tt string
      - in: query
        name: file
        description: file          tt postdata  tt (required)
      - in: query
        name: tags
        description: tags          tt string    tt tag names or IDs, comma separated
      - in: query
        name: title
        description: title         tt string
      responses:
        200:
          description: OK
      tags:
      - Assets
  /api/assets/download/{id}:
    get:
      summary: Download asset
      description: Download asset
      operationId: download-asset
      x-api-path-slug: apiassetsdownloadid-get
      parameters:
      - in: path
        name: ID
        description: The unique ID for the asset
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Download
      - Id
  /api/assets/ID:
    get:
      summary: Get single asset
      description: Get single asset
      operationId: get-single-asset
      x-api-path-slug: apiassetsid-get
      responses:
        200:
          description: OK
      tags:
      - Assets
    put:
      summary: Update asset
      description: Update asset
      operationId: update-asset
      x-api-path-slug: apiassetsid-put
      parameters:
      - in: query
        name: description
        description: description   tt string
      - in: query
        name: tags
        description: tags          tt string tt tag names or IDs, comma separated
      - in: query
        name: title
        description: title         tt string
      responses:
        200:
          description: OK
      tags:
      - Assets
  /api/assets/ID/versions:
    get:
      summary: Get asset versions
      description: Get asset versions
      operationId: get-asset-versions
      x-api-path-slug: apiassetsidversions-get
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Versions
    post:
      summary: Create asset version
      description: Create asset version
      operationId: create-asset-version
      x-api-path-slug: apiassetsidversions-post
      parameters:
      - in: query
        name: comment
        description: comment     tt string
      - in: query
        name: file
        description: file        tt postdata
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Versions
  /api/assets/ID/versions/VID:
    get:
      summary: Get single asset version
      description: Get single asset version
      operationId: get-single-asset-version
      x-api-path-slug: apiassetsidversionsvid-get
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Versions
      - VID
  /api/assets/{id}:
    delete:
      summary: Delete asset
      description: Delete asset
      operationId: delete-asset
      x-api-path-slug: apiassetsid-delete
      parameters:
      - in: path
        name: id
        description: Unique id of the asset
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Id