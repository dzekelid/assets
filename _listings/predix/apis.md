---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Assets
created: "2018-08-27"
modified: "2018-08-27"
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
- name: Dynamic Mapping - Add an asset location into a collection.
  x-api-slug: v1collectionscollectionnameassetsassetid-put
  description: |-
    Insert a location entry into the named collection for the given asset identifier and timestamp. In addition to
    adding the new asset location, the request also controls the retention of the location history that is
    stored for the given asset in the given collection.

      - If the mandatory property retain_history is set to false then all existing location history for the
      given asset is removed before the new location is added.

      - If the retain_history property is set to true and the optional property purge_history_before is not set
      then the new location is added to the existing set of locations for the given asset.

      - If retain_history is set to true and the optional property purge_history_before is set then any existing
      locations for the given asset that have a timestamp that is older than the supplied purge_history_before
      timestamp are first deleted. Next the new location is added to the set of locations that remain.

      - If the set of location entries for the given asset (after any possible removals) contains a location entry
       with the same timestamp as the new location then the location of that entry is updated rather than a new
       location entry being added.

      - Note the new entry is always added or used to update an existing entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-put-openapi.md
- name: Dynamic Mapping - Delete an asset and its location data
  x-api-slug: v1collectionscollectionnameassetsassetid-delete
  description: Delete the asset specified by the collection name. Any location data
    associated with the asset are also deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-delete-openapi.md
- name: Dynamic Mapping - Return the latest location data for an asset
  x-api-slug: v1collectionscollectionnameassetsassetid-get
  description: |-
    Returns the latest location entry for the given asset. The timestamp and location data for the
    given entry is included in the response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-get-openapi.md
- name: Dynamic Mapping - Return locations for an asset by query condition for given
    customer id and collection name.
  x-api-slug: v1collectionscollectionnameassetsassetidquery-post
  description: |-
    Returns the locations for an asset by three types of query for a given customer id and collection name.
    The returned locations are in descending order of time.
    Three types of query:
    1. type=latest: The latest n locations will be returned.
    2. type=timeperiod: Locations within a time period will be returned.
    3. type=bbox: Locations within a time period and a spatial bounding box will be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetidquery-post-openapi.md
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
- name: Dynamic Mapping - Add an asset location into a collection.
  x-api-slug: v1collectionscollectionnameassetsassetid-put
  description: |-
    Insert a location entry into the named collection for the given asset identifier and timestamp. In addition to
    adding the new asset location, the request also controls the retention of the location history that is
    stored for the given asset in the given collection.

      - If the mandatory property retain_history is set to false then all existing location history for the
      given asset is removed before the new location is added.

      - If the retain_history property is set to true and the optional property purge_history_before is not set
      then the new location is added to the existing set of locations for the given asset.

      - If retain_history is set to true and the optional property purge_history_before is set then any existing
      locations for the given asset that have a timestamp that is older than the supplied purge_history_before
      timestamp are first deleted. Next the new location is added to the set of locations that remain.

      - If the set of location entries for the given asset (after any possible removals) contains a location entry
       with the same timestamp as the new location then the location of that entry is updated rather than a new
       location entry being added.

      - Note the new entry is always added or used to update an existing entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-put-openapi.md
- name: Dynamic Mapping - Delete an asset and its location data
  x-api-slug: v1collectionscollectionnameassetsassetid-delete
  description: Delete the asset specified by the collection name. Any location data
    associated with the asset are also deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-delete-openapi.md
- name: Dynamic Mapping - Return the latest location data for an asset
  x-api-slug: v1collectionscollectionnameassetsassetid-get
  description: |-
    Returns the latest location entry for the given asset. The timestamp and location data for the
    given entry is included in the response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-get-openapi.md
- name: Dynamic Mapping - Return locations for an asset by query condition for given
    customer id and collection name.
  x-api-slug: v1collectionscollectionnameassetsassetidquery-post
  description: |-
    Returns the locations for an asset by three types of query for a given customer id and collection name.
    The returned locations are in descending order of time.
    Three types of query:
    1. type=latest: The latest n locations will be returned.
    2. type=timeperiod: Locations within a time period will be returned.
    3. type=bbox: Locations within a time period and a spatial bounding box will be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetidquery-post-openapi.md
- name: Dynamic Mapping - Return locations for an asset by query condition for given
    customer id and collection name.
  x-api-slug: v1collectionscollectionnameassetsassetidquery-post
  description: |-
    Returns the locations for an asset by three types of query for a given customer id and collection name.
    The returned locations are in descending order of time.
    Three types of query:
    1. type=latest: The latest n locations will be returned.
    2. type=timeperiod: Locations within a time period will be returned.
    3. type=bbox: Locations within a time period and a spatial bounding box will be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetidquery-post-openapi.md
- name: Dynamic Mapping - Return the latest location data for an asset
  x-api-slug: v1collectionscollectionnameassetsassetid-get
  description: |-
    Returns the latest location entry for the given asset. The timestamp and location data for the
    given entry is included in the response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-get-openapi.md
- name: Dynamic Mapping - Delete an asset and its location data
  x-api-slug: v1collectionscollectionnameassetsassetid-delete
  description: Delete the asset specified by the collection name. Any location data
    associated with the asset are also deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-delete-openapi.md
- name: Dynamic Mapping - Add an asset location into a collection.
  x-api-slug: v1collectionscollectionnameassetsassetid-put
  description: |-
    Insert a location entry into the named collection for the given asset identifier and timestamp. In addition to
    adding the new asset location, the request also controls the retention of the location history that is
    stored for the given asset in the given collection.

      - If the mandatory property retain_history is set to false then all existing location history for the
      given asset is removed before the new location is added.

      - If the retain_history property is set to true and the optional property purge_history_before is not set
      then the new location is added to the existing set of locations for the given asset.

      - If retain_history is set to true and the optional property purge_history_before is set then any existing
      locations for the given asset that have a timestamp that is older than the supplied purge_history_before
      timestamp are first deleted. Next the new location is added to the set of locations that remain.

      - If the set of location entries for the given asset (after any possible removals) contains a location entry
       with the same timestamp as the new location then the location of that entry is updated rather than a new
       location entry being added.

      - Note the new entry is always added or used to update an existing entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/assets/master/_listings/predix/v1collectionscollectionnameassetsassetid-put-openapi.md
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