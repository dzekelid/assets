---
swagger: "2.0"
x-collection-name: UK National Archives
x-complete: 0
info:
  title: Getty Images Search API Post Asset Registrations
  description: Register a list of customer assets..
  version: "3.0"
host: api.gettyimages.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v3/boards/{board_id}/assets:
    delete:
      summary: Delete Boards Board Assets
      description: <b>***beta***</b> remove assets from a board.
      operationId: deleteV3BoardsBoardAssets
      x-api-path-slug: v3boardsboard-idassets-delete
      parameters:
      - in: header
        name: Accept-Language
        description: Provide a header to specify the language of result values
      - in: query
        name: asset_ids
        description: List the assets to be removed from the board
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: path
        name: board_id
        description: Specify the board to remove assets from
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Board
      - Assets
    put:
      summary: Put Boards Board Assets
      description: <b>***beta***</b> add assets to a board.
      operationId: putV3BoardsBoardAssets
      x-api-path-slug: v3boardsboard-idassets-put
      parameters:
      - in: header
        name: Accept-Language
        description: Provide a header to specify the language of result values
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: body
        name: board_assets
        description: List assets to add to the board
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: board_id
        description: Specify the board to add assets to
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Board
      - Assets
  /v3/boards/{board_id}/assets/{asset_id}:
    delete:
      summary: Delete Boards Board Assets Asset
      description: <b>***beta***</b> remove an asset from a board.
      operationId: deleteV3BoardsBoardAssetsAsset
      x-api-path-slug: v3boardsboard-idassetsasset-id-delete
      parameters:
      - in: header
        name: Accept-Language
        description: Provide a header to specify the language of result values
      - in: path
        name: asset_id
        description: Specify the asset to remove from the board
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: path
        name: board_id
        description: Specify the board to remove an asset from
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Board
      - Assets
      - Asset
    put:
      summary: Put Boards Board Assets Asset
      description: <b>***beta***</b> add an asset to a board.
      operationId: putV3BoardsBoardAssetsAsset
      x-api-path-slug: v3boardsboard-idassetsasset-id-put
      parameters:
      - in: header
        name: Accept-Language
        description: Provide a header to specify the language of result values
      - in: path
        name: asset_id
        description: Specify the asset to add to the board
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: path
        name: board_id
        description: Specify the board to add an asset to
      responses:
        200:
          description: OK
      tags:
      - Boards
      - Board
      - Assets
      - Asset
  /v3/purchased-assets:
    get:
      summary: Get Purchased Assets
      description: Get previously purchased images and video.
      operationId: getV3PurchasedAssets
      x-api-path-slug: v3purchasedassets-get
      parameters:
      - in: header
        name: Authorization
        description: Provide access token in the format of Bearer {token}
      - in: query
        name: date_from
        description: If specified, retrieves previous purchases on or after this date
      - in: query
        name: date_to
        description: If specified, retrieves previous purchases on or before this
          date
      - in: query
        name: page
        description: Identifies page to return
      - in: query
        name: page_size
        description: Specifies page size
      responses:
        200:
          description: OK
      tags:
      - Purchased
      - Assets
  /v3/asset-changes/change-sets:
    put:
      summary: Put Asset Changes Change Sets
      description: Generates asset changes..
      operationId: putV3AssetChangesChangeSets
      x-api-path-slug: v3assetchangeschangesets-put
      parameters:
      - in: header
        name: Accept-Language
        description: Accept-Language parameter optional
      - in: header
        name: Authorization
        description: Authorization token required
      - in: query
        name: batch_size
        description: Specifies the number of assets to return
      - in: query
        name: channel_id
        description: Specifies the id of the channel for the asset data
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Changes
      - Change
      - Sets
  /v3/asset-changes/change-sets/{change-set-id}:
    delete:
      summary: Delete Asset Changes Change Sets Change Set
      description: Confirm asset changes acknowledges receipt of asset changes..
      operationId: deleteV3AssetChangesChangeSetsChangeSet
      x-api-path-slug: v3assetchangeschangesetschangesetid-delete
      parameters:
      - in: header
        name: Accept-Language
        description: Accept-Language parameter optional
      - in: header
        name: Authorization
        description: Authorization token required
      - in: path
        name: change-set-id
        description: Specify the change-set-id associated with a transaction resource
          whose receipt you want to confirm
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Changes
      - Change
      - Sets
      - Change
      - Set
  /v3/asset-changes/channels:
    get:
      summary: Get Asset Changes Channels
      description: Retrieves the channel data for the partner. this data can be used
        to populate the channel_id parameter in the put asset changes query..
      operationId: getV3AssetChangesChannels
      x-api-path-slug: v3assetchangeschannels-get
      parameters:
      - in: header
        name: Accept-Language
        description: Accept-Language parameter optional
      - in: header
        name: Authorization
        description: Authorization token required
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Changes
      - Channels
  /v3/asset-registrations:
    post:
      summary: Post Asset Registrations
      description: Register a list of customer assets..
      operationId: postV3AssetRegistrations
      x-api-path-slug: v3assetregistrations-post
      parameters:
      - in: header
        name: Accept-Language
        description: Accept-Language parameter optional
      - in: header
        name: Authorization
        description: Authorization token required
      - in: body
        name: request
        description: Specify JSON containing an array of asset ids to register
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Registrations
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