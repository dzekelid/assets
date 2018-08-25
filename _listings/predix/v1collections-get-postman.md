{
  "info": {
    "name": "Predix Dynamic Mapping List all asset collections for a customer",
    "_postman_id": "0b0dc86e-7ca4-48c1-bbdb-6b3409a1f2d6",
    "description": "Returns an array containing the names of all asset collections for the\nspecified customer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "c0459662-be54-4e33-ac45-cd4c8800166f",
          "name": "returns-an-array-containing-the-names-of-all-asset-collections-for-thespecified-customer",
          "request": {
            "url": "{{default}}/v1/collections?No Name=%7B%7D",
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
            "description": "Returns an array containing the names of all asset collections for the\nspecified customer."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "40309a4e-5ceb-42ed-8324-ae1c4dcb2e76"
            }
          ]
        }
      ]
    }
  ],
  "variable": [
    {
      "key": "default",
      "value": "http://www.example.com/"
    }
  ]
}