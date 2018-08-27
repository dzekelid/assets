swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id}/colors/asset_string:
    get:
      summary: Get custom color
      description: Get custom color.
      operationId: get-custom-color
      x-api-path-slug: usersidcolorsasset-string-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
      - Colors
      - Asset
      - String
    put:
      summary: Update custom color
      description: Update custom color.
      operationId: update-custom-color
      x-api-path-slug: usersidcolorsasset-string-put
      parameters:
      - in: query
        name: hexcode
        description: The hexcode of the color to set for the context, if you choose
          to pass thenhexcode as a query parameter rather than in the request body
          you should NOTninclude the &#39;#&#39; unless you escape it first
      responses:
        200:
          description: OK
      tags:
      - Users
      - Id
      - Colors
      - Asset
      - String