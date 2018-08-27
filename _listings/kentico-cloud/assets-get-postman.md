{
  "info": {
    "name": "Kentico Cloud List assets",
    "_postman_id": "c6c9c3f8-f1c6-444f-a1e5-28765021aaf1",
    "description": "Retrieve a dynamically paginated list of assets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "9c3680b2-d6da-491e-8720-86c2e594d796",
          "name": "AssetsGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/assets",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a dynamically paginated list of assets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92bae58a-eff6-494b-8593-7ae78e14e04b"
            }
          ]
        }
      ]
    }
  ]
}