---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Add API Asset Dsclaimers Disclaimer Decline
  version: 1.0.0
  description: Add api asset dsclaimers disclaimer decline.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/Assets:
    get:
      summary: Get API Assets
      description: Get api assets.
      operationId: ApiAssetsGet
      x-api-path-slug: apiassets-get
      responses:
        200:
          description: OK
      tags:
      - Assets
  /api/Assets/{id}:
    get:
      summary: Get API Assets
      description: Get api assets.
      operationId: ApiAssetsByIdGet
      x-api-path-slug: apiassetsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assets
  /api/Assets/description/list:
    post:
      summary: Add API Assets Description List
      description: Add api assets description list.
      operationId: ApiAssetsDescriptionListPost
      x-api-path-slug: apiassetsdescriptionlist-post
      parameters:
      - in: body
        name: request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Description
      - List
  /api/Assets/{assetId}/attributes:
    get:
      summary: Get API Assets Asset Attributes
      description: Get api assets asset attributes.
      operationId: ApiAssetsByAssetIdAttributesGet
      x-api-path-slug: apiassetsassetidattributes-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Asset
      - Attributes
  /api/Assets/{assetId}/attributes/{key}:
    get:
      summary: Get API Assets Asset Attributes Key
      description: Get api assets asset attributes key.
      operationId: ApiAssetsByAssetIdAttributesByKeyGet
      x-api-path-slug: apiassetsassetidattributeskey-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: key
      responses:
        200:
          description: OK
      tags:
      - Assets
      - Asset
      - Attributes
      - Key
  /api/Dicts/assets:
    get:
      summary: Get API Dicts Assets
      description: Get api dicts assets.
      operationId: ApiDictsAssetsGet
      x-api-path-slug: apidictsassets-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Dicts
      - Assets
  /api/AllAssetDescription/{id}:
    get:
      summary: Get API All Asset Description
      description: Get api all asset description.
      operationId: ApiAllAssetDescriptionByIdGet
      x-api-path-slug: apiallassetdescriptionid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Description
  /api/AllAssetPairRates:
    get:
      summary: Get API All Asset Pair Rates
      description: Get api all asset pair rates.
      operationId: ApiAllAssetPairRatesGet
      x-api-path-slug: apiallassetpairrates-get
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pair
      - Rates
  /api/AllAssetPairRates/{id}:
    get:
      summary: Get API All Asset Pair Rates
      description: Get api all asset pair rates.
      operationId: ApiAllAssetPairRatesByIdGet
      x-api-path-slug: apiallassetpairratesid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pair
      - Rates
  /api/AllAssetPairs:
    get:
      summary: Get API All Asset Pairs
      description: Get api all asset pairs.
      operationId: ApiAllAssetPairsGet
      x-api-path-slug: apiallassetpairs-get
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pairs
  /api/AllAssetPairs/{id}:
    get:
      summary: Get API All Asset Pairs
      description: Get api all asset pairs.
      operationId: ApiAllAssetPairsByIdGet
      x-api-path-slug: apiallassetpairsid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Pairs
  /api/assetcategories:
    get:
      summary: Get API Asset Categories
      description: Get api asset categories.
      operationId: ApiAssetcategoriesGet
      x-api-path-slug: apiassetcategories-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Categories
  /api/AssetDisclaimers:
    get:
      summary: Get API Asset Dsclaimers
      description: Get api asset dsclaimers.
      operationId: AssetDisclaimersGet
      x-api-path-slug: apiassetdisclaimers-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
  /api/AssetDisclaimers/{disclaimerId}/approve:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Approve
      description: Add api asset dsclaimers disclaimer approve.
      operationId: AssetDisclaimersApprove
      x-api-path-slug: apiassetdisclaimersdisclaimeridapprove-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: disclaimerId
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
      - Disclaimer
      - Approve
  /api/AssetDisclaimers/{disclaimerId}/decline:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Decline
      description: Add api asset dsclaimers disclaimer decline.
      operationId: AssetDisclaimersDecline
      x-api-path-slug: apiassetdisclaimersdisclaimeriddecline-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: disclaimerId
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
      - Disclaimer
      - Decline
  /api/HotWallet/addresses/{destinationAddress}/{assetId}/validity:
    get:
      summary: Get API Hotwallet Addresses Destinationaddress Asset Vality
      description: Get api hotwallet addresses destinationaddress asset vality.
      operationId: AddressValidity
      x-api-path-slug: apihotwalletaddressesdestinationaddressassetidvalidity-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: destinationAddress
      responses:
        200:
          description: OK
      tags:
      - Hotwallet
      - Resses
      - Destinationaddress
      - Asset
      - Vality
  /api/SwiftCredentials/{assetId}:
    get:
      summary: Get API Swiftcredentials Asset
      description: Get api swiftcredentials asset.
      operationId: ApiSwiftCredentialsByAssetIdGet
      x-api-path-slug: apiswiftcredentialsassetid-get
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Swiftcredentials
      - Asset
  /api/Wallets/depositaddress/{assetId}:
    post:
      summary: Add API Wallets Depositaddress Asset
      description: Add api wallets depositaddress asset.
      operationId: ApiWalletsDepositaddressByAssetIdPost
      x-api-path-slug: apiwalletsdepositaddressassetid-post
      parameters:
      - in: path
        name: assetId
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Wallets
      - Depositaddress
      - Asset
  /api/AssetDescription/{id}:
    get:
      summary: Get API Assetdescription
      description: Get api assetdescription.
      operationId: ApiAssetDescriptionByIdGet
      x-api-path-slug: apiassetdescriptionid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assetdescription
  /api/AssetPair/{id}:
    get:
      summary: Get API Assetpair
      description: Get api assetpair.
      operationId: ApiAssetPairByIdGet
      x-api-path-slug: apiassetpairid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assetpair
  /api/AssetPairDetailedRates:
    get:
      summary: Get API Assetpairdetailedrates
      description: Get api assetpairdetailedrates.
      operationId: ApiAssetPairDetailedRatesGet
      x-api-path-slug: apiassetpairdetailedrates-get
      parameters:
      - in: query
        name: assetId
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: period
      - in: query
        name: points
      - in: query
        name: withBid
      responses:
        200:
          description: OK
      tags:
      - Assetpairdetailedrates
  /api/AssetPairRates:
    get:
      summary: Get API Assetpairrates
      description: Get api assetpairrates.
      operationId: ApiAssetPairRatesGet
      x-api-path-slug: apiassetpairrates-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: ignoreBase
      responses:
        200:
          description: OK
      tags:
      - Assetpairrates
  /api/AssetPairRates/{id}:
    get:
      summary: Get API Assetpairrates
      description: Get api assetpairrates.
      operationId: ApiAssetPairRatesByIdGet
      x-api-path-slug: apiassetpairratesid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Assetpairrates
  /api/AssetPairs:
    get:
      summary: Get API Assetpairs
      description: Get api assetpairs.
      operationId: ApiAssetPairsGet
      x-api-path-slug: apiassetpairs-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Assetpairs
  /api/BaseAssets:
    get:
      summary: Get API Baseassets
      description: Get api baseassets.
      operationId: ApiBaseAssetsGet
      x-api-path-slug: apibaseassets-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Baseassets
  /api/LastBaseAssets:
    get:
      summary: Get API Lastbaseassets
      description: Get api lastbaseassets.
      operationId: ApiLastBaseAssetsGet
      x-api-path-slug: apilastbaseassets-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: "n"
      responses:
        200:
          description: OK
      tags:
      - Lastbaseassets
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