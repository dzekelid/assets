{
  "info": {
    "name": "Lykke Get API All Asset Pair Rates",
    "_postman_id": "a629e329-74a5-4827-9f72-6291afe5fb3f",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "dfe5236d-f013-4a7b-b537-9812036e7e6a",
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
          "id": "b4e468ab-ef8a-465a-b8d4-b31fbdbd3246"
        }
      ]
    },
    {
      "id": "a544142c-3f7e-4138-8464-759273e10e07",
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
          "id": "b91827c3-179f-4362-89b8-8d4a8066df46"
        }
      ]
    },
    {
      "id": "036b084d-7039-4d53-8d49-bfe33d9907c7",
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
          "id": "8f1e083d-310b-4429-a3b6-a55a3354c24e"
        }
      ]
    }
  ]
}