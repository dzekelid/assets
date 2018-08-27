{
  "info": {
    "name": "Predix Dynamic Mapping Return all asset ids for a collection",
    "_postman_id": "492d0fe6-ad10-4ac0-9871-f295100cfe9f",
    "description": "Returns the collection name and a list of ids of the assets that belong to\nthe collection.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "e6e9f3de-fd3d-4e5d-928e-c99743388257",
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
              "id": "10185b60-ebe0-4fec-bf8d-4f39c8bde0c6"
            }
          ]
        }
      ]
    },
    {
      "name": "Return",
      "item": [
        {
          "id": "28d399b1-9bf3-4a8e-a122-70a351d8cf2d",
          "name": "returns-the-collection-name-and-a-list-of-ids-of-the-assets-that-belong-tothe-collection",
          "request": {
            "url": {
              "host": "{{default}}",
              "path": [
                "v1/collections/:collectionName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "collectionName",
                  "value": "collectionName",
                  "type": "string"
                }
              ]
            },
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
            "description": "Returns the collection name and a list of ids of the assets that belong to\nthe collection."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "387be817-d6f6-4200-a412-d95d56846054"
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