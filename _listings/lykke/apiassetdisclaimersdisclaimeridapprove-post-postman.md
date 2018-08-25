{
  "info": {
    "name": "Lykke Add API Asset Dsclaimers Disclaimer Approve",
    "_postman_id": "2394eabc-4d3d-4dd8-8b90-cdb29e608372",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "9a3a983c-720b-416b-aee8-03e482ef0486",
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
          "id": "e1d9e461-f827-49e8-8442-b20e936f2ada"
        }
      ]
    },
    {
      "id": "9b231c68-2f00-44e3-832f-45e963cef4eb",
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
          "id": "6cc4d385-c746-4373-a682-2ef61ae52dd4"
        }
      ]
    },
    {
      "id": "27263cdc-2518-4f9e-b5b2-eb1ea636b852",
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
          "id": "c9c8cf69-3971-472a-b235-26a9c23df0a0"
        }
      ]
    },
    {
      "id": "62cc67ca-0d4a-4baa-8f7d-02ae94279c74",
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
          "id": "ceaf78b5-5bfe-42ee-94aa-1d80c69eb503"
        }
      ]
    },
    {
      "id": "4b1040bf-3ccc-4ab0-ba31-338a6f4c1d62",
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
          "id": "e219ff8e-9b7e-442e-a401-23561813e5da"
        }
      ]
    },
    {
      "id": "405f0ef5-01e3-4806-93af-9ad5778fed2d",
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
          "id": "1fae5f9b-3b05-4452-b263-ee0974b1dd5d"
        }
      ]
    },
    {
      "id": "0682dcfa-b4c8-4844-9bcb-9231f792d630",
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
          "id": "f060c3e7-6926-47f0-b882-47231b16ab4c"
        }
      ]
    },
    {
      "id": "e379d283-e896-48b1-ae7a-50c6caa6e0a1",
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
          "id": "0d7578e3-1f56-4a66-bb2a-40685982c2d3"
        }
      ]
    },
    {
      "id": "2bc2315a-7441-49ba-9e27-2bdb5a223ff8",
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
          "id": "f2afb20c-d79c-4524-9398-ced22562959a"
        }
      ]
    },
    {
      "id": "5ff59715-ce79-475e-9142-a3fde256dcc5",
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
          "id": "86cd62ed-9e23-4c93-bf5e-b0bbbaf02814"
        }
      ]
    },
    {
      "id": "9206b93a-e70f-4d65-adc4-4ecad9a83667",
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
          "id": "e856dcbf-e301-4ac9-9996-45b0d62dc433"
        }
      ]
    },
    {
      "id": "f6c3694c-f684-47dd-8a95-2ec7370febda",
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
          "id": "30ed5a06-f36d-4284-a4cf-f15fc7b66569"
        }
      ]
    }
  ]
}