{
  "info": {
    "name": "Lykke Get API Assets",
    "_postman_id": "6bafc472-fd03-4d8e-8d21-6685ab6f558a",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "7e614be7-e644-475e-be02-bc2318925fe6",
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
          "id": "45b4e9e5-f5a5-44a0-9377-1eca7dcd693b"
        }
      ]
    },
    {
      "id": "a8206756-9059-4c5f-94f8-5781db228f33",
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
          "id": "1d23318a-1694-4f1b-b8c0-a37572a9a976"
        }
      ]
    },
    {
      "id": "23e276c2-57ea-4b9d-8726-b78b6f9e0cb6",
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
          "id": "e4172cab-7507-48ef-b0e6-3ac544717f2e"
        }
      ]
    },
    {
      "id": "c36e4c16-672d-453a-be7c-866d45c7ff46",
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
          "id": "3cd8957b-8251-4f43-8ea9-02fd6feb6fb3"
        }
      ]
    },
    {
      "id": "ed9d5188-7bf6-4685-a718-c1d6bd3b957d",
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
          "id": "29540bad-aa9d-4e79-9c41-5f4da7b0a38a"
        }
      ]
    },
    {
      "id": "8b37a9b5-1d1d-4b89-9dd2-10bb0b1a135d",
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
          "id": "2ceb1301-fec8-4747-929f-68c6bfa3ce37"
        }
      ]
    },
    {
      "id": "d8131103-4720-4642-bd3a-6d04b0878cdc",
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
          "id": "ffa2490c-89f4-404a-a6d6-dbbae8704150"
        }
      ]
    },
    {
      "id": "1c85492a-0f2d-4e18-b478-612de547cc5b",
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
          "id": "80588029-2dda-4ff2-8189-1dcccd65a36d"
        }
      ]
    },
    {
      "id": "dd088a6d-2358-4153-ad19-ad17bc898b67",
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
          "id": "226c6a84-f260-4424-81bb-773dc07afcc1"
        }
      ]
    },
    {
      "id": "a8553c65-3087-4808-bb71-75e984fb60d4",
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
          "id": "45b49ecb-3d24-4749-a2fb-fe61d05a190a"
        }
      ]
    },
    {
      "id": "f5a98564-aaa1-4314-a3ba-97bb68cd8887",
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
          "id": "c8d79eb4-3f16-4c3b-9597-1b6e180731c6"
        }
      ]
    },
    {
      "id": "79e0753e-7fa4-4fb8-9f52-68cdd9828d1d",
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
          "id": "9a0994c8-05e8-44b0-b7cd-f3708ba2d248"
        }
      ]
    },
    {
      "id": "1fec742b-1b4f-4939-bd66-59ec8a13235f",
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
          "id": "670cd6df-b7f8-47e8-bffe-abe65cf68726"
        }
      ]
    },
    {
      "id": "02fe17b5-eea3-45c1-a7ff-6b7ab3846874",
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
          "id": "abb7a216-198e-4f47-b44c-6192d0d71450"
        }
      ]
    },
    {
      "id": "20fd4d35-cf7f-4f39-ae07-4595c9485e5e",
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
          "id": "20d6b633-1879-489f-bb20-aebc5faac24c"
        }
      ]
    },
    {
      "id": "76524ed6-f490-46bf-a594-b37d91e634cd",
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
          "id": "43eefd9f-a3a5-4f11-82f8-e9e09e69b6f8"
        }
      ]
    },
    {
      "id": "560026a6-f696-4e5b-882a-46120c5936df",
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
          "id": "db337143-76e7-452b-8f47-52992daa9885"
        }
      ]
    },
    {
      "id": "591a14ce-87d6-4a9e-876e-201d1f7ea934",
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
          "id": "9d6b4c20-6c53-43ad-9ddb-7b25b3464e75"
        }
      ]
    },
    {
      "id": "c6c691aa-15dc-4a8c-aba9-e337163819fe",
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
          "id": "da9b331e-fe89-4489-ac5f-e69f1a54d1cd"
        }
      ]
    },
    {
      "id": "b027c672-cb65-43ee-b606-40db8d2dde40",
      "name": "ApiAssetsByIdGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "example.com",
          "path": [
            "api/Assets/:id"
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
        "description": "Get API Assets"
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "6468e002-c6e5-4bb0-99d3-bd2f5c5e6ae6"
        }
      ]
    }
  ]
}