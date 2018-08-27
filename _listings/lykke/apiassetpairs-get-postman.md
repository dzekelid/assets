{
  "info": {
    "name": "Lykke Get API Assetpairs",
    "_postman_id": "56b1825f-d79f-4888-acf0-fb299198a645",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "596eb5ed-baaf-4486-97d4-d402a7b78190",
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
          "id": "dc3a7f80-1c7e-43e3-b499-ebd6224f8dc7"
        }
      ]
    },
    {
      "id": "4aae4673-fefb-491a-8b59-9aee1a30738f",
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
          "id": "01d58866-d9c1-4c6d-984d-0423227dbd33"
        }
      ]
    },
    {
      "id": "12e55e32-31da-4688-99be-a2fc771d5ba5",
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
          "id": "122bc5a8-d43d-443e-9e1d-ffc1a2549db5"
        }
      ]
    },
    {
      "id": "04bc276b-bafc-4bd6-8875-1bea03a3b9e0",
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
          "id": "5cb35ead-a495-4f91-a400-3c580fe81b56"
        }
      ]
    },
    {
      "id": "772503b5-64bd-4cf7-b4ec-6e8dff7520a5",
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
          "id": "a860c00d-adf3-4f37-ad77-f3dfecd95922"
        }
      ]
    },
    {
      "id": "50351f9a-fd6a-4384-a6ef-0853e60560c9",
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
          "id": "44c42ca6-6cfe-4529-9b88-7569763db6cc"
        }
      ]
    },
    {
      "id": "b4b7123d-5684-4b06-8f46-129f5512c9cd",
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
          "id": "af685273-0f5c-4fde-907f-fee688e1bef9"
        }
      ]
    },
    {
      "id": "0d41cbec-cf80-4906-ad6d-18cac530790b",
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
          "id": "a580fc46-7953-4e57-a669-b256a06cea62"
        }
      ]
    },
    {
      "id": "fee72282-88f9-411e-bcea-f4950520a49f",
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
          "id": "087f41e0-5b96-41b6-865a-f3eda98e9e45"
        }
      ]
    },
    {
      "id": "d933de36-10ae-4367-ba15-aa8b36fa6416",
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
          "id": "734d9b8e-dd2c-49e7-9f27-292ccdb5d14d"
        }
      ]
    },
    {
      "id": "ce16827d-62e2-47ed-9e52-7d1ebdaab9e3",
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
          "id": "ee7239bc-ddb9-4f6f-bb59-be542a107ec1"
        }
      ]
    },
    {
      "id": "d7854342-d2b2-4b62-a0d9-ada96aaccd82",
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
          "id": "1808c2bb-0e15-4659-8ce7-86cf7d608b3f"
        }
      ]
    },
    {
      "id": "246d7cf7-7623-443f-96b6-786f3bb450e7",
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
          "id": "9bc1dfde-dad0-4ec2-9f57-872556f66a39"
        }
      ]
    },
    {
      "id": "294f5af2-f9ba-4625-a0e8-67c2fb1e8f2a",
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
          "id": "c55404aa-ba4c-4d4f-a2d2-dfd31b90d544"
        }
      ]
    },
    {
      "id": "7c1f9f4c-20fd-454a-849f-805f4012a733",
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
          "id": "55fa8679-50aa-4911-96ad-e875ebe38148"
        }
      ]
    },
    {
      "id": "34ebe7bf-a830-4ccb-be08-8f617673af8f",
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
          "id": "38f926dc-0e15-4e8f-a586-3463c4185d04"
        }
      ]
    },
    {
      "id": "93afaf75-9664-4cfa-baf2-16e02fc7cdca",
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
          "id": "e5d9375a-8fdf-4633-bbc6-e6ea6707f040"
        }
      ]
    },
    {
      "id": "8f9036ce-8882-4d59-8da5-554f9f28124e",
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
          "id": "038ec379-a0f0-47fa-a404-97b35ac1c5d9"
        }
      ]
    }
  ]
}