---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Assets
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Dynamic Mapping - Returns collection assets in specified bounding box
  x-api-slug: v1collectionscollectionnamespatialquerybboxinteracts-get
  description: |-
    Returns all assets in the specified collection whose latest location exist within the specified bounding box.
    The bounding box is defined by two coordinates in the EPSG:4326 (WGS84) (for further details see
    http://epsg.io/4326):
    * left (longitude), bottom (latitude)
    * right (longitude), top (latitude)
    The results can be filtered by including key and value pairs to match in location meta data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnamespatialquerybboxinteracts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnamespatialquerybboxinteracts-get-openapi.md
- name: Dynamic Mapping - Returns clustered assets in a specified bounding box
  x-api-slug: v1collectionscollectionnamecluster-get
  description: |-
    Returns clusters of assets in the specified collection whose latest location exists within the specified
    bounding box. The clusters can also optionally be filtered by a single key-value pair.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnamecluster-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnamecluster-get-openapi.md
- name: Dynamic Mapping - List all asset collections for a customer
  x-api-slug: v1collections-get
  description: |-
    Returns an array containing the names of all asset collections for the
    specified customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collections-get-openapi.md
- name: Dynamic Mapping - Return all asset ids for a collection
  x-api-slug: v1collectionscollectionname-get
  description: |-
    Returns the collection name and a list of ids of the assets that belong to
    the collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionname-get-openapi.md
- name: Dynamic Mapping - List all asset collections for a customer
  x-api-slug: v1collections-get
  description: |-
    Returns an array containing the names of all asset collections for the
    specified customer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collections-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collections-get-openapi.md
- name: Dynamic Mapping - Return all asset ids for a collection
  x-api-slug: v1collectionscollectionname-get
  description: |-
    Returns the collection name and a list of ids of the assets that belong to
    the collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionname-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---