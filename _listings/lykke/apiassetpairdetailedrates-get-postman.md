{
  "info": {
    "name": "Lykke Get API Assetpairdetailedrates",
    "_postman_id": "e406b774-c2d1-46b3-997f-d89c3c3c9053",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "272f2d5c-f8ba-454f-8c4e-0dbc073abdbc",
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
          "id": "79f402ff-3558-44e5-8a0f-041144e892ed"
        }
      ]
    },
    {
      "id": "a6216ad1-3181-4c5b-9d98-6672977d2dc2",
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
          "id": "208db7fc-18b8-4541-acfe-815e851d8e6b"
        }
      ]
    },
    {
      "id": "4ae6d269-76bc-4d80-8ef0-d9690fabd231",
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
          "id": "b7158111-fc82-43ec-b239-9a65d847287b"
        }
      ]
    },
    {
      "id": "5d8748b3-ac64-4f47-8d23-09ce0650d9ad",
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
          "id": "1f96d7cb-5675-4a55-9941-cba41a1438a3"
        }
      ]
    },
    {
      "id": "92ccad28-b6ce-4823-8231-98a055851b3d",
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
          "id": "9fd54b41-1b06-4ce4-af37-be34c1a0bc88"
        }
      ]
    },
    {
      "id": "fcfa8f9b-fe71-4e71-b17d-13461a962a34",
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
          "id": "064f7853-3f3b-4199-9c61-b4cb5f24e7d8"
        }
      ]
    },
    {
      "id": "010d35c9-e940-49f0-8fa7-1ec4a2b220dd",
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
          "id": "3fcfb19e-e32e-4b02-a90b-0c80a0548fab"
        }
      ]
    },
    {
      "id": "7bfd2b27-f5b9-4abd-9e0b-a810d7e7884e",
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
          "id": "6236d54a-2f38-4954-8049-86f134ee06a1"
        }
      ]
    },
    {
      "id": "59374066-ca00-4127-b2e0-08588c132e07",
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
          "id": "341ffceb-3438-4e94-aba0-170ca070f6b2"
        }
      ]
    },
    {
      "id": "30621ee4-e197-44b5-9a17-8e266afe9a35",
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
          "id": "f460983c-eeb2-4671-bcb0-2059044cb73e"
        }
      ]
    },
    {
      "id": "76d73780-c735-4c1a-9ee6-b65cfb26bfcc",
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
          "id": "39fde357-3171-4f22-9405-d08b39ea4917"
        }
      ]
    },
    {
      "id": "69619e4b-1cf1-4522-830e-c97fa807ce32",
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
          "id": "7efa58f9-0e1e-4b22-808a-7a7f83f677cc"
        }
      ]
    },
    {
      "id": "2275d617-33b6-472e-8e48-c7ea38ea02d3",
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
          "id": "17d1b500-d4be-4ef1-afcc-8cf67963a98d"
        }
      ]
    },
    {
      "id": "7dc51003-3aa5-4556-808b-bdcc1b2c3ef3",
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
          "id": "e5d82930-ba00-4bf9-a9ca-ed69c366c8d1"
        }
      ]
    },
    {
      "id": "0178b16e-fecc-4028-b010-5dcc3fb39cf2",
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
          "id": "90b7d1e8-a58e-4d6d-af25-764036a10e5a"
        }
      ]
    }
  ]
}