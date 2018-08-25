{
  "info": {
    "name": "Lykke Get API All Asset Pairs",
    "_postman_id": "8c4e850b-473c-4d27-8272-5518ad808711",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "0735b337-9737-4f4c-8f06-88f78a107da5",
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
          "id": "ef1e7977-6782-4725-bc78-4d62cadb8635"
        }
      ]
    },
    {
      "id": "cda9816d-5793-4e1f-a35b-de3211a74183",
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
          "id": "ef651f10-5855-4db9-afcb-a4c55dbb96cd"
        }
      ]
    },
    {
      "id": "09e6187d-0afa-4652-a605-17873fa5b330",
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
          "id": "6a24168a-61c6-4d55-8b85-df0ced722b00"
        }
      ]
    },
    {
      "id": "4402a103-c773-4710-8828-1e4f74e82b0e",
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
          "id": "57b38ea2-f8ae-43d8-a377-b8646594dda1"
        }
      ]
    },
    {
      "id": "7ea0a232-1351-493e-9c55-35139ea4410d",
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
          "id": "41ba858d-d6ce-4ecc-a3b5-d4cbeae55989"
        }
      ]
    }
  ]
}