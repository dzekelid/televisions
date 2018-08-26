---
name: The TVDB
x-slug: the-tvdb
description: TheTVDB.com is a community driven database of television shows. All content
  and images on the site have been contributed by the sites users; the site uses moderated
  editing to maintain its own standards. The database schema and website are open
  source under the GNU General Public License.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
x-kinRank: "7"
x-alexaRank: "0"
tags: Televisions
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/apis.md
specificationVersion: "0.14"
apis:
- name: The TVDB API v2 - Get Episodes
  x-api-slug: episodesid-get
  description: Returns the full information for a given episode id. __Deprecation
    Warning:__ The _director_ key will be deprecated in favor of the new _directors_
    key in a future release.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/episodesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/episodesid-get-openapi.md
- name: The TVDB API v2 - Get Languages
  x-api-slug: languages-get
  description: All available languages. These language abbreviations can be used in
    the `Accept-Language` header for routes that return translation records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languages-get-openapi.md
- name: The TVDB API v2 - Get Languages
  x-api-slug: languagesid-get
  description: Information about a particular language, given the language ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languagesid-get-openapi.md
- name: The TVDB API v2 - Get Episodes
  x-api-slug: episodesid-get
  description: Returns the full information for a given episode id. __Deprecation
    Warning:__ The _director_ key will be deprecated in favor of the new _directors_
    key in a future release.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/episodesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/episodesid-get-openapi.md
- name: The TVDB API v2 - Get Languages
  x-api-slug: languages-get
  description: All available languages. These language abbreviations can be used in
    the `Accept-Language` header for routes that return translation records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languages-get-openapi.md
- name: The TVDB API v2 - Get Languages
  x-api-slug: languagesid-get
  description: Information about a particular language, given the language ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/languagesid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://the.open.movie.database.api.gallery.streamdata.io
- type: x-api-stack
  url: http://the.tvdb.stack.network
- type: x-documentation
  url: https://api.thetvdb.com/swagger
- type: x-website
  url: http://thetvdb.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---