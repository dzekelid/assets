---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud Delete an asset by ID
  description: Removes an unused asset specified by its internal ID.
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /assets:
    get:
      summary: List assets
      description: Retrieve a dynamically paginated list of assets.
      operationId: AssetsGet
      x-api-path-slug: assets-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - List
      - Assets
    post:
      summary: Add an asset
      description: "Use a file reference to link an existing [binary file](https://developer.kenticocloud.com/v1/reference#content-management-api-upload-file)
        to a new asset. You can also create assets by upserting (`PUT /assets/external-id/<external_id>`),
        see [Upsert an asset](https://developer.kenticocloud.com/v1/reference#content-management-api-upsert-asset-by-external-id).\r\n\r\n**Note:**
        Each binary file can be referenced only by a single asset."
      operationId: AssetsPost
      x-api-path-slug: assets-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Asset
  /assets/external-id/which-brewing-fits-you:
    get:
      summary: View an asset by external ID
      description: Retrieve information about a single asset specified by its external
        ID.
      operationId: AssetsExternalIdWhichBrewingFitsYouGet
      x-api-path-slug: assetsexternalidwhichbrewingfitsyou-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Asset
      - By
      - External
      - ID
    put:
      summary: Upsert an asset by external ID
      description: "Add a new asset or update an existing asset specified by its external
        ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in
        the project, the system will try to create one. For existing assets, the API
        updates only the specified asset's descriptions and title."
      operationId: AssetsExternalIdWhichBrewingFitsYouPut
      x-api-path-slug: assetsexternalidwhichbrewingfitsyou-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Upsert
      - Asset
      - By
      - External
      - ID
    delete:
      summary: Delete an asset by ID
      description: Removes an unused asset specified by its external ID.
      operationId: AssetsExternalIdWhichBrewingFitsYouDelete
      x-api-path-slug: assetsexternalidwhichbrewingfitsyou-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Asset
      - By
      - ID
  /assets/fcbb12e6-66a3-4672-85d9-d502d16b8d9c:
    get:
      summary: View an asset by ID
      description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
        This endpoint only allows updating of asset descriptions and title."
      operationId: AssetsFcbb12e666a3467285d9D502d16b8d9cGet
      x-api-path-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Asset
      - By
      - ID
    put:
      summary: Update an asset by ID
      description: Retrieve a dynamically paginated list of assets.
      operationId: AssetsFcbb12e666a3467285d9D502d16b8d9cPut
      x-api-path-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Asset
      - By
      - ID
    delete:
      summary: Delete an asset by ID
      description: Removes an unused asset specified by its internal ID.
      operationId: AssetsFcbb12e666a3467285d9D502d16b8d9cDelete
      x-api-path-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Asset
      - By
      - ID
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