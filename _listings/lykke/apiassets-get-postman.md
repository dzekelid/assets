{
  "info": {
    "name": "Lykke Get API Assets",
    "_postman_id": "13c6acc0-3d1e-435f-ae8c-2c0603b9f028",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "e771bdb6-8129-4922-8a26-0da4292a6431",
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
          "id": "bffecd09-6a23-4377-894d-c9463fdf2499"
        }
      ]
    },
    {
      "id": "7b25f4d6-7b1f-4bb5-ad0f-4361d4179f4c",
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
          "id": "f2bd1f5b-54f1-466c-b3a2-2db2ec28f744"
        }
      ]
    },
    {
      "id": "ec843fac-d746-4bff-a0ba-281df43698d1",
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
          "id": "70a0c765-9958-4f35-aaad-162a03352c1c"
        }
      ]
    },
    {
      "id": "d325a50a-465c-45ed-930f-785b91a2a41c",
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
          "id": "c1978ab4-06cc-4ef6-9535-78c229681ae0"
        }
      ]
    },
    {
      "id": "1cb00266-4463-43c3-a330-fa59db0c40b9",
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
          "id": "448bd1f6-e889-4bb7-9200-82a81edb2be6"
        }
      ]
    },
    {
      "id": "1d3e61cf-b2b9-429e-a328-416787d3a602",
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
          "id": "06523832-12a7-4f62-b7e6-3863d18d580e"
        }
      ]
    },
    {
      "id": "f4817f09-d0f4-44d1-9bb7-e35da25b858e",
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
          "id": "159a03c9-bf4b-4924-9bd8-2841cc442bcb"
        }
      ]
    },
    {
      "id": "eac4d854-3cb5-47b7-b4ed-038bada30332",
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
          "id": "bbe7e8c0-b1a3-48eb-96b9-8cbaaa3075a6"
        }
      ]
    },
    {
      "id": "35e1428c-4d7f-40da-99cf-3c3c0b52545b",
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
          "id": "4709cb83-5d15-4a56-8ebf-47da73bda9ff"
        }
      ]
    },
    {
      "id": "5c3ac1d5-1880-44e0-8d05-17ef50858572",
      "name": "ApiAssetDescriptionByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AssetDescription/:id"
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
        "description": "Get API Assetdescription"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f6ef7246-4dfa-4be3-a863-6c5b331f3103"
        }
      ]
    },
    {
      "id": "1fa8720b-0dcd-414f-b813-69e06d4b930c",
      "name": "AssetDisclaimersGet",
      "request": {
        "url": "http://example.com/api/AssetDisclaimers",
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
        "description": "Get API Asset Dsclaimers"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "8a67ef7d-03c9-4caf-acb9-9c7720c262aa"
        }
      ]
    },
    {
      "id": "15123f9e-d3cd-4094-ab9d-61b96ca78d6a",
      "name": "AssetDisclaimersApprove",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AssetDisclaimers/:disclaimerId/approve"
          ],
          "variable": [
            {
              "id": "disclaimerId",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "POST",
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
        "description": "Add API Asset Dsclaimers Disclaimer Approve"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "aa165841-6665-4a91-af15-4b965178f8d2"
        }
      ]
    },
    {
      "id": "24ba1043-4e75-459d-81bd-405e6c027480",
      "name": "AssetDisclaimersDecline",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AssetDisclaimers/:disclaimerId/decline"
          ],
          "variable": [
            {
              "id": "disclaimerId",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "POST",
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
        "description": "Add API Asset Dsclaimers Disclaimer Decline"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d0226d4f-fd54-4a5e-a96b-a53b406f1285"
        }
      ]
    },
    {
      "id": "5bfa7c9c-0969-4073-a7da-c6e28175f423",
      "name": "ApiAssetPairByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AssetPair/:id"
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
        "description": "Get API Assetpair"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "cc8cbf9c-d0ba-4546-a6e8-250bd1065c5d"
        }
      ]
    },
    {
      "id": "67454ac6-8584-4954-8a43-57b7d31aae78",
      "name": "ApiAssetPairDetailedRatesGet",
      "request": {
        "url": "http://example.com/api/AssetPairDetailedRates?assetId=%7B%7D&period=%7B%7D&points=%7B%7D&withBid=%7B%7D",
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
        "description": "Get API Assetpairdetailedrates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "deb02fe5-3ea4-4c13-bdbe-07e17e3dd7d9"
        }
      ]
    },
    {
      "id": "a8c6b870-b406-4c78-9d11-cf67d45e0897",
      "name": "ApiAssetPairRatesGet",
      "request": {
        "url": "http://example.com/api/AssetPairRates?ignoreBase=%7B%7D",
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
        "description": "Get API Assetpairrates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d50be9db-58de-4ca0-a78b-d2333039139a"
        }
      ]
    },
    {
      "id": "0ec87d6a-b1ab-427f-93b2-216e96773305",
      "name": "ApiAssetPairRatesByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/AssetPairRates/:id"
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
        "description": "Get API Assetpairrates"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3c0daeb0-ec1a-430e-835b-f4465984de78"
        }
      ]
    },
    {
      "id": "7bcff948-f8b2-4644-a468-178f1b837a02",
      "name": "ApiAssetPairsGet",
      "request": {
        "url": "http://example.com/api/AssetPairs",
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
        "description": "Get API Assetpairs"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "852bdf19-8596-4789-8dc3-7ea015615a4c"
        }
      ]
    },
    {
      "id": "18ebd328-1c06-4909-b7e1-1addcc838204",
      "name": "ApiAssetsGet",
      "request": {
        "url": "http://example.com/api/Assets",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "Get API Assets"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "f43a48b9-1a4d-4d77-ad58-c6de2193f4d5"
        }
      ]
    }
  ]
}