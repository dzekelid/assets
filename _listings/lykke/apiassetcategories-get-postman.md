{
  "info": {
    "name": "Lykke Get API Asset Categories",
    "_postman_id": "34e71a12-d3e6-476d-ac19-295f5869ade3",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "7a280df6-3c9a-4da5-80d7-e42eb296b3d2",
      "name": "ApiAccountExistGet",
      "request": {
        "url": "http://example.com/api/AccountExist?email=%7B%7D&partnerId=%7B%7D",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API Account Exist"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6711b7d9-6404-4528-8ad2-1e18545dc3b2"
        }
      ]
    },
    {
      "id": "ef38c484-60eb-474c-8228-ac474d83f86d",
      "name": "ApiAllAssetDescriptionByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AllAssetDescription/:id"
          ],
          "variable": [
            {
              "id": "id",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Description"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "e5dbd521-65bf-407c-9d13-97bf9e33494a"
        }
      ]
    },
    {
      "id": "b836db9c-2bd1-4775-8d65-6245d811ae3c",
      "name": "ApiAllAssetPairRatesGet",
      "request": {
        "url": "http://example.com/api/AllAssetPairRates",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pair Rates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "ecb6120b-d1e0-4904-843e-bcd89f566ee1"
        }
      ]
    },
    {
      "id": "595c2649-bf95-40fa-9dc2-4661a09b3517",
      "name": "ApiAllAssetPairRatesByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AllAssetPairRates/:id"
          ],
          "variable": [
            {
              "id": "id",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pair Rates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "4b04968b-d95d-4e41-9dd5-c904087eceb1"
        }
      ]
    },
    {
      "id": "0a613438-8e9e-4538-ac9d-6be8e0780dc8",
      "name": "ApiAllAssetPairsGet",
      "request": {
        "url": "http://example.com/api/AllAssetPairs",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pairs"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "fe5f39a1-29e9-4e68-92da-d59dfc05c10b"
        }
      ]
    },
    {
      "id": "fd15d2c8-17da-461e-92cc-54ccfcf12145",
      "name": "ApiAllAssetPairsByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AllAssetPairs/:id"
          ],
          "variable": [
            {
              "id": "id",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API All Asset Pairs"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "59f620f4-4f01-4230-bfa4-152b6ca15da3"
        }
      ]
    },
    {
      "id": "606d69b5-3d43-4e88-8fce-846c308e83bb",
      "name": "ApiApplicationInfoGet",
      "request": {
        "url": "http://example.com/api/ApplicationInfo",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API Application Information"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f51faba9-1253-44dc-be17-706fbe6759f8"
        }
      ]
    },
    {
      "id": "310cc1b3-298a-4a84-a3c1-7eab1204596b",
      "name": "ApiAppSettingsGet",
      "request": {
        "url": "http://example.com/api/AppSettings",
        "method": "GET",
        "header": [
          {
            "key": "Authorization",
            "value": "{}",
            "description": "access token",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Get API Application Settings"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "87cd269d-0267-42bf-84e6-d778855c2de2"
        }
      ]
    },
    {
      "id": "88138571-eaba-4bca-a569-3e4efade9ac5",
      "name": "ApiAssetcategoriesGet",
      "request": {
        "url": "http://example.com/api/assetcategories",
        "method": "GET",
        "header": [
          {
            "key": "Authorization",
            "value": "{}",
            "description": "access token",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "Get API Asset Categories"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "7bd5999e-6927-435b-91f1-830e7031375d"
        }
      ]
    }
  ]
}