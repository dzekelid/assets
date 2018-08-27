{
  "info": {
    "name": "Lykke Get API All Asset Description",
    "_postman_id": "d78c72f3-1f86-488a-9000-d80f28ca2a26",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "c66887f3-c6b3-462c-8650-241260f58d86",
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
          "id": "3677d4b6-fca1-49fb-b516-ebaf25b83cc7"
        }
      ]
    },
    {
      "id": "2dd901e6-ab54-471c-9395-01bc5a5218c6",
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
          "id": "6b9a3d83-896f-4853-8d17-f1693e979cf5"
        }
      ]
    }
  ]
}