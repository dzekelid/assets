{
  "info": {
    "name": "Lykke Get API Assetpairrates",
    "_postman_id": "7f5b2d18-8bd7-4946-941b-f82884e88b00",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "723ac733-7869-4372-bb2b-f15f5e143b4b",
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
          "id": "ef2f1e4a-6fe5-40c9-91d3-3a8080310d44"
        }
      ]
    },
    {
      "id": "83f5f4b2-91ee-42b3-8454-3d846f8d08cf",
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
          "id": "3e45c740-bc4e-4dee-9bd1-0daf52589169"
        }
      ]
    },
    {
      "id": "880779a8-3f30-414a-acc1-8c610da585af",
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
          "id": "4585bcce-8638-4aed-8257-e70c817f77de"
        }
      ]
    },
    {
      "id": "22b7ab02-db14-46cc-b930-e8dcb4ecc6d0",
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
          "id": "353affe6-0e0b-4457-bf3e-b9784db22f5a"
        }
      ]
    },
    {
      "id": "65a9fc79-c265-4e82-a89c-7b712df12a0c",
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
          "id": "dd95ecb5-aa89-4f01-8058-89532e3c2e40"
        }
      ]
    },
    {
      "id": "aff5d8d7-5626-42ee-827d-843f966198d8",
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
          "id": "e79e0ba9-97bc-44c9-a2fb-f54b8281b4dc"
        }
      ]
    },
    {
      "id": "259f1876-a895-4f3d-a743-0ca4c09c3184",
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
          "id": "f4c73e29-c801-4e92-bd66-216bab2ec201"
        }
      ]
    },
    {
      "id": "95ca2b31-d511-4a3b-a682-95c35742c700",
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
          "id": "a79263d8-8724-4ee4-8485-8166450d33f7"
        }
      ]
    },
    {
      "id": "f1b3ca6a-442d-463d-b5a7-a1d73056b35d",
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
          "id": "b3cffe05-2ebf-4691-885d-306a30e70846"
        }
      ]
    },
    {
      "id": "d96f7618-2f73-4326-9e33-5e6fda48aeb5",
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
          "id": "bedaa803-6627-432d-89b3-131ee0f767c0"
        }
      ]
    },
    {
      "id": "2d4b2e6b-5a31-4322-8e6c-a6d9e6477e84",
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
          "id": "3d5ac44e-5fc0-4754-a9a4-c7fa5af93323"
        }
      ]
    },
    {
      "id": "50c8a1fa-e81f-48f9-9a8d-3728ba33b4f9",
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
          "id": "35ccd930-03a1-41d2-b617-9cc083f1091d"
        }
      ]
    },
    {
      "id": "2168f81c-6209-475d-9683-b9ee3807fe30",
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
          "id": "5a0cff90-075a-4074-a48b-3fbfde78ab8d"
        }
      ]
    },
    {
      "id": "4ff2e6eb-a234-4247-a2da-6d31c8f1da86",
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
          "id": "b7dec761-56f4-455a-bc69-5fe8d1728762"
        }
      ]
    },
    {
      "id": "c2e32436-be34-43ed-b2d1-b333b30ef8d9",
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
          "id": "8e5dc410-b99a-4c89-b264-111e95e23529"
        }
      ]
    },
    {
      "id": "c5994841-d23f-4c19-86fb-8d400554dfc7",
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
          "id": "2dd9a996-55c1-4a7c-828d-e729dd8447d6"
        }
      ]
    },
    {
      "id": "af4a9247-0371-4b32-9ce1-036fcdf56234",
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
          "id": "9f83f9f9-b0f2-435c-a839-5c1c7b7d8eb1"
        }
      ]
    }
  ]
}