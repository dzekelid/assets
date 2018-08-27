---
swagger: "2.0"
x-collection-name: Fluxiom
x-complete: 0
info:
  title: Fluxiom API Get assets
  description: Get assets
  termsOfService: http://www.fluxiom.com/terms
  version: v1
host: '{subdomain}.fluxiom.com'
basePath: /api/{format}
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/assets:
    get:
      summary: Get assets
      description: Get assets
      operationId: get-assets
      x-api-path-slug: apiassets-get
      parameters:
      - in: query
        name: page
        description: page  tt integer tt current page number (defaults to 1)
      - in: query
        name: per_page
        description: per_page  tt integer tt number of items per page (max
      - in: query
        name: query
        description: query tt string tt search term
      - in: query
        name: tags
        description: tags  tt string tt tag names or IDs, comma separated
      responses:
        200:
          description: OK
      tags:
      - Assets
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---