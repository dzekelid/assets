---
name: Kentico Cloud
x-slug: kentico-cloud
description: 'Kentico Cloud is the #1 CMS that enables digital teams to collaborate
  quickly to create engaging personalized experiences across any device. Free 30-day
  trial!'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
x-kinRank: "7"
x-alexaRank: "369033"
tags: Assets
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/apis.md
specificationVersion: "0.14"
apis:
- name: Kentico Cloud - List assets
  x-api-slug: assets-get
  description: Retrieve a dynamically paginated list of assets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assets-get-openapi.md
- name: Kentico Cloud - View an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-get
  description: Retrieve information about a single asset specified by its external
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-openapi.md
- name: Kentico Cloud - Upsert an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-put
  description: "Add a new asset or update an existing asset specified by its external
    ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in the
    project, the system will try to create one. For existing assets, the API updates
    only the specified asset's descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-put-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-delete
  description: Removes an unused asset specified by its external ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-delete-openapi.md
- name: Kentico Cloud - Add an asset
  x-api-slug: assets-post
  description: "Use a file reference to link an existing [binary file](https://developer.kenticocloud.com/v1/reference#content-management-api-upload-file)
    to a new asset. You can also create assets by upserting (`PUT /assets/external-id/<external_id>`),
    see [Upsert an asset](https://developer.kenticocloud.com/v1/reference#content-management-api-upsert-asset-by-external-id).\r\n\r\n**Note:**
    Each binary file can be referenced only by a single asset."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assets-post-openapi.md
- name: Kentico Cloud - View an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
  description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
    This endpoint only allows updating of asset descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-get-openapi.md
- name: Kentico Cloud - Update an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-put
  description: Retrieve a dynamically paginated list of assets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-put-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-delete
  description: Removes an unused asset specified by its internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-delete-openapi.md
- name: Kentico Cloud - View an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-get
  description: Retrieve information about a single asset specified by its external
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-openapi.md
- name: Kentico Cloud - Upsert an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-put
  description: "Add a new asset or update an existing asset specified by its external
    ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in the
    project, the system will try to create one. For existing assets, the API updates
    only the specified asset's descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-put-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-delete
  description: Removes an unused asset specified by its external ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-delete-openapi.md
- name: Kentico Cloud - Add an asset
  x-api-slug: assets-post
  description: "Use a file reference to link an existing [binary file](https://developer.kenticocloud.com/v1/reference#content-management-api-upload-file)
    to a new asset. You can also create assets by upserting (`PUT /assets/external-id/<external_id>`),
    see [Upsert an asset](https://developer.kenticocloud.com/v1/reference#content-management-api-upsert-asset-by-external-id).\r\n\r\n**Note:**
    Each binary file can be referenced only by a single asset."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assets-post-openapi.md
- name: Kentico Cloud - View an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
  description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
    This endpoint only allows updating of asset descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-get-openapi.md
- name: Kentico Cloud - Update an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-put
  description: Retrieve a dynamically paginated list of assets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-put-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-delete
  description: Removes an unused asset specified by its internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-delete-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-delete
  description: Removes an unused asset specified by its internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-delete-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-delete
  description: Removes an unused asset specified by its internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-delete-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-delete
  description: Removes an unused asset specified by its internal ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-delete-openapi.md
- name: Kentico Cloud - Update an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-put
  description: Retrieve a dynamically paginated list of assets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-put-openapi.md
- name: Kentico Cloud - Update an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-put
  description: Retrieve a dynamically paginated list of assets.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-put-openapi.md
- name: Kentico Cloud - View an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
  description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
    This endpoint only allows updating of asset descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-get-openapi.md
- name: Kentico Cloud - View an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
  description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
    This endpoint only allows updating of asset descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-get-openapi.md
- name: Kentico Cloud - View an asset by ID
  x-api-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
  description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
    This endpoint only allows updating of asset descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsfcbb12e666a3467285d9d502d16b8d9c-get-openapi.md
- name: Kentico Cloud - Add an asset
  x-api-slug: assets-post
  description: "Use a file reference to link an existing [binary file](https://developer.kenticocloud.com/v1/reference#content-management-api-upload-file)
    to a new asset. You can also create assets by upserting (`PUT /assets/external-id/<external_id>`),
    see [Upsert an asset](https://developer.kenticocloud.com/v1/reference#content-management-api-upsert-asset-by-external-id).\r\n\r\n**Note:**
    Each binary file can be referenced only by a single asset."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assets-post-openapi.md
- name: Kentico Cloud - Add an asset
  x-api-slug: assets-post
  description: "Use a file reference to link an existing [binary file](https://developer.kenticocloud.com/v1/reference#content-management-api-upload-file)
    to a new asset. You can also create assets by upserting (`PUT /assets/external-id/<external_id>`),
    see [Upsert an asset](https://developer.kenticocloud.com/v1/reference#content-management-api-upsert-asset-by-external-id).\r\n\r\n**Note:**
    Each binary file can be referenced only by a single asset."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assets-post-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-delete
  description: Removes an unused asset specified by its external ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-delete-openapi.md
- name: Kentico Cloud - Delete an asset by ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-delete
  description: Removes an unused asset specified by its external ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-delete-openapi.md
- name: Kentico Cloud - Upsert an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-put
  description: "Add a new asset or update an existing asset specified by its external
    ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in the
    project, the system will try to create one. For existing assets, the API updates
    only the specified asset's descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-put-openapi.md
- name: Kentico Cloud - Upsert an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-put
  description: "Add a new asset or update an existing asset specified by its external
    ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in the
    project, the system will try to create one. For existing assets, the API updates
    only the specified asset's descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-put-openapi.md
- name: Kentico Cloud - Upsert an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-put
  description: "Add a new asset or update an existing asset specified by its external
    ID.\r\n\r\n**Note:** If no asset with the specified external ID exists in the
    project, the system will try to create one. For existing assets, the API updates
    only the specified asset's descriptions and title."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-put-openapi.md
- name: Kentico Cloud - View an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-get
  description: Retrieve information about a single asset specified by its external
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-openapi.md
- name: Kentico Cloud - View an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-get
  description: Retrieve information about a single asset specified by its external
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-openapi.md
- name: Kentico Cloud - View an asset by external ID
  x-api-slug: assetsexternalidwhichbrewingfitsyou-get
  description: Retrieve information about a single asset specified by its external
    ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28870-kenticocloud-com.jpg
  humanURL: https://kenticocloud.com/
  baseURL: https://deliver.kenticocloud.com//
  tags: SaaS, Technology, Enterprise, Relative Data, Service API, Cloud
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/kentico-cloud/assetsexternalidwhichbrewingfitsyou-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://kenticocloud.com/rss
- type: x-github
  url: https://github.com/kentico
- type: x-postman-collection
  url: https://app.getpostman.com/run-collection/519dd5697b81ba7336a3
- type: x-website
  url: https://kenticocloud.com/
- type: x-api-gallery
  url: http://kaltura.api.gallery.streamdata.io
- type: x-api-stack
  url: http://kentico.cloud.stack.network
- type: x-blog
  url: https://kenticocloud.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/kentico
- type: x-partners
  url: https://kenticocloud.com/partners
- type: x-pricing
  url: https://kenticocloud.com/pricing
- type: x-twitter
  url: https://twitter.com/kenticocloud
- type: x-website
  url: https://kenticocloud.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---