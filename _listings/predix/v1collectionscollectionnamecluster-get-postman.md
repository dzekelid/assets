{
  "info": {
    "name": "Predix Dynamic Mapping Returns clustered assets in a specified bounding box",
    "_postman_id": "7128524c-948a-42dc-922f-d8a223921060",
    "description": "Returns clusters of assets in the specified collection whose latest location exists within the specified\nbounding box. The clusters can also optionally be filtered by a single key-value pair.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "d42d2047-ba68-4a70-a9d4-73b6d3842d71",
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
              "id": "7d6090b3-374e-4d58-8036-d93a761f4d26"
            }
          ]
        }
      ]
    },
    {
      "name": "Return",
      "item": [
        {
          "id": "df5ae18e-495f-4f10-bc12-e09403278e4c",
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
              "id": "a48de7ee-9b62-4fb2-9b8a-598fe94daa41"
            }
          ]
        }
      ]
    },
    {
      "name": "Collection",
      "item": [
        {
          "id": "bad71a1e-bce0-4f59-8ec2-16297308b776",
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
              "id": "e044149b-eb03-4620-9728-25198cc47bee"
            }
          ]
        }
      ]
    },
    {
      "name": "Returns",
      "item": [
        {
          "id": "c6176c14-8e12-4aaf-a7eb-bb1300120886",
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
              "id": "42a57d3d-80ff-489c-90da-39a17274bf77"
            }
          ]
        },
        {
          "id": "4ed0ac84-372a-4262-9382-fba7320cfbba",
          "name": "returns-clusters-of-assets-in-the-specified-collection-whose-latest-location-exists-within-the-speci",
          "request": {
            "url": {
              "host": "{{default}}",
              "path": [
                "v1/collections/:collectionName/cluster"
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
            "description": "Returns clusters of assets in the specified collection whose latest location exists within the specified\nbounding box. The clusters can also optionally be filtered by a single key-value pair."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "b56bb8fe-702a-4bde-9d14-dfd3b1bcbb52"
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