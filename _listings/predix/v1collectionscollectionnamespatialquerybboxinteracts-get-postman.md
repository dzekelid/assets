{
  "info": {
    "name": "Predix Dynamic Mapping Returns collection assets in specified bounding box",
    "_postman_id": "84f2d156-0426-425f-a5f5-4d531d53b4ba",
    "description": "Returns all assets in the specified collection whose latest location exist within the specified bounding box.\nThe bounding box is defined by two coordinates in the EPSG:4326 (WGS84) (for further details see\nhttp://epsg.io/4326):\n* left (longitude), bottom (latitude)\n* right (longitude), top (latitude)\nThe results can be filtered by including key and value pairs to match in location meta data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "12986339-a1cd-4993-979a-b92c2e224f97",
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
              "id": "50dd7c9b-1f04-4329-90f2-a28acf1b3fec"
            }
          ]
        }
      ]
    },
    {
      "name": "Return",
      "item": [
        {
          "id": "8559599c-efe6-4daf-8364-093fb789fbfe",
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
              "id": "b6b73429-1675-4a2c-8786-691806b06ab9"
            }
          ]
        }
      ]
    },
    {
      "name": "Collection",
      "item": [
        {
          "id": "5f7c2e66-de81-423b-95de-8d39bd2e334c",
          "name": "delete-the-asset-collection-specified-by-the-collection-name-any-associated-asset-and-asset-location",
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
            "method": "DELETE",
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
            "description": "Delete the asset collection specified by the collection name. Any associated asset and asset location data\nare also deleted"
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "8ce0608a-afb0-4ee0-a490-617e6f14e870"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "c7ec2d5d-1f5e-49cd-b2c1-61a60a2d5df3",
          "name": "returns-all-assets-in-the-specified-collection-whose-latest-location-exist-within-the-specified-boun",
          "request": {
            "url": {
              "host": "{{default}}",
              "path": [
                "v1/collections/:collectionName/spatial-query/bbox-interacts"
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
            "description": "Returns all assets in the specified collection whose latest location exist within the specified bounding box.\nThe bounding box is defined by two coordinates in the EPSG:4326 (WGS84) (for further details see\nhttp://epsg.io/4326):\n* left (longitude), bottom (latitude)\n* right (longitude), top (latitude)\nThe results can be filtered by including key and value pairs to match in location meta data."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "002d65ec-a0b6-489b-a694-5be006f15a28"
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