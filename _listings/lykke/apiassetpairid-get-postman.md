{
  "info": {
    "name": "Lykke Get API Assetpair",
    "_postman_id": "c9fe812e-a4d3-4ec9-a19e-7ac2baddcdba",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "31a85387-1bef-4fa1-a823-9a01ae7d1fa8",
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
          "id": "0a293d7f-c2dd-4cf1-b033-233f381b7326"
        }
      ]
    },
    {
      "id": "49877a5d-a289-4f05-b553-7848521e4f83",
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
          "id": "645fd96d-b969-4a5a-9a61-c79f6b0c15a2"
        }
      ]
    },
    {
      "id": "40e5c934-8740-4feb-a7e2-5c15a04b01e2",
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
          "id": "3496df32-0743-4087-abdf-6372a4dc9bf9"
        }
      ]
    },
    {
      "id": "ea61179c-076a-419d-bc3e-f9567323b498",
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
          "id": "486c3ed5-ea1d-4093-9d57-f728e866ef0e"
        }
      ]
    },
    {
      "id": "36dc9c44-3126-46be-a4bb-cf862f0b0e85",
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
          "id": "0ce5c5b5-b747-4a96-a2f5-85377feb223f"
        }
      ]
    },
    {
      "id": "4843e476-6777-42b7-b9d0-9a2e2e67301b",
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
          "id": "58c71f80-1fbd-4eaa-be02-c098f0474195"
        }
      ]
    },
    {
      "id": "c7b1892a-2741-4245-866e-05e5988f5340",
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
          "id": "f9516623-cbc2-4bd2-a4f7-4a39ad74d914"
        }
      ]
    },
    {
      "id": "aa6ddbb2-645f-41b7-b7dd-731901f0bcde",
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
          "id": "bbcbb260-a67d-4dc9-ba03-eae700083309"
        }
      ]
    },
    {
      "id": "2d56364f-df62-4a0f-badc-79b24e27a07a",
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
          "id": "eaa3b2c0-4338-4fdc-ac02-8775c739f66d"
        }
      ]
    },
    {
      "id": "40a76859-bded-484a-afe4-4258201af4fa",
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
          "id": "d6a85b82-0600-47d8-b1c0-84e8d420d115"
        }
      ]
    },
    {
      "id": "c8370d44-d8da-4d3d-a637-38a02230a1e8",
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
          "id": "a8baee9b-7771-4e51-9d3d-28ab172f4b27"
        }
      ]
    },
    {
      "id": "946192fc-08e0-436d-bf40-b3e04ffda0bf",
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
          "id": "be5aea20-252e-4b30-90fd-199c56e1c1b4"
        }
      ]
    },
    {
      "id": "60ebce10-d04b-4488-8551-f09d4d927e7c",
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
          "id": "c927acb9-66b8-449b-8437-c319bafe4631"
        }
      ]
    },
    {
      "id": "57f49020-90f2-4d68-bf4a-0b60e5f2d802",
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
          "id": "3d93b49e-ca71-40ac-a3a1-4da2cd128fa0"
        }
      ]
    }
  ]
}