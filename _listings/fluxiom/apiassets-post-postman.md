{
  "info": {
    "name": "Fluxiom API Create asset",
    "_postman_id": "bcecd603-fd09-405d-9df1-f521a8fe80c3",
    "description": "Create asset",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Assets",
      "item": [
        {
          "id": "2104398f-1166-406c-b137-563b4ac11dd7",
          "name": "get-assets",
          "request": {
            "url": "http://TODO Add Value for parameter....fluxiom.com/api/TODO Add Value for parameter.../api/assets?page=%7B%7D&per_page=%7B%7D&query=%7B%7D&tags=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get assets"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ce882f1-24c0-4a8d-9b30-caf7ef6c051e"
            }
          ]
        },
        {
          "id": "604256f0-d1e9-413c-adb0-77c9fb9cf0dc",
          "name": "create-asset",
          "request": {
            "url": "http://TODO Add Value for parameter....fluxiom.com/api/TODO Add Value for parameter.../api/assets?description=%7B%7D&file=%7B%7D&tags=%7B%7D&title=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb3ba456-a9bd-429f-b0d9-d40b37e19c73"
            }
          ]
        }
      ]
    }
  ]
}