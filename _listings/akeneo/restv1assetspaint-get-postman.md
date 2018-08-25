{
  "info": {
    "name": "Akeneo PIM API asset (2.1 only)",
    "_postman_id": "817b2ebc-592e-4c02-8e67-9fca9316000c",
    "description": "Assuming that the given code is the code of an existing asset",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Asset",
      "item": [
        {
          "id": "008dcd86-0033-4ee3-a4a5-35f36908cd59",
          "name": "RestV1AssetsPaintGet",
          "request": {
            "url": "http://example.com/api/rest/v1/assets/paint",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Assuming that the given code is the code of an existing asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53375478-18d7-48ac-be44-68ba75d71f8e"
            }
          ]
        }
      ]
    }
  ]
}