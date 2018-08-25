{
  "info": {
    "name": "Shopify Get a list of all theme assets",
    "_postman_id": "09be678b-1e6d-46e7-9aac-09fd5accf726",
    "description": "Get a list of all theme assets.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "37a8a47b-82d5-4a16-a6b2-68f69d2b5ce3",
          "name": "getAdminThemes110163843Assets.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/themes/110163843/assets.json",
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
            "description": "Get a list of all theme assets."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2adf2cfb-6419-4ba6-a3fd-147f5ad84d09"
            }
          ]
        }
      ]
    }
  ]
}