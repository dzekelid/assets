{
  "info": {
    "name": "Lykke Get API All Asset Pair Rates",
    "_postman_id": "25857560-cf85-4c9b-9341-ff6fda4539b7",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "870ef607-812b-491c-bd2a-5460cdc4c24e",
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
          "id": "e0fe3082-dfaa-4c60-ba33-9f4a743c33cb"
        }
      ]
    },
    {
      "id": "82a6d46b-1a94-4d49-a084-6ea7defb246b",
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
          "id": "2d86195e-4a15-4e75-8d7d-9c1a399bd2dd"
        }
      ]
    },
    {
      "id": "a872fd91-faca-454d-b389-5ef9b779a6c1",
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
          "id": "fdb8034f-3354-41a6-accf-e0c73240ce85"
        }
      ]
    },
    {
      "id": "9837ad26-1de6-4bfc-8060-178ea8546ab9",
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
          "id": "5145fab4-34a2-41c1-aea7-a01d51b03da2"
        }
      ]
    }
  ]
}