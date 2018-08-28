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
created: "2018-08-28"
modified: "2018-08-28"
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
- name: The TVDB API v2 - Post Login
  x-api-slug: login-post
  description: Returns a session token to be included in the rest of the requests.
    Note that API key authentication is required for all subsequent requests and user
    auth is required for routes in the `User` section
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/login-post-openapi.md
- name: The TVDB API v2 - Get Refresh Token
  x-api-slug: refresh-token-get
  description: Refreshes your current, valid JWT token and returns a new token. Hit
    this route so that you do not have to post to `/login` with your API key and credentials
    once you have already been authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/refresh-token-get-openapi.md
- name: The TVDB API v2 - Get Search Series
  x-api-slug: searchseries-get
  description: Allows the user to search for a series based on the following parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/searchseries-get-openapi.md
- name: The TVDB API v2 - Get Search Series Params
  x-api-slug: searchseriesparams-get
  description: Returns an array of parameters to query by in the `/search/series`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/searchseriesparams-get-openapi.md
- name: The TVDB API v2 - Get Series
  x-api-slug: seriesid-get
  description: Returns a series records that contains all information known about
    a particular series id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesid-get-openapi.md
- name: The TVDB API v2 - Head Series
  x-api-slug: seriesid-head
  description: Returns header information only about the given series ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesid-head-openapi.md
- name: The TVDB API v2 - Get Series Actors
  x-api-slug: seriesidactors-get
  description: Returns actors for the given series id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidactors-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes
  x-api-slug: seriesidepisodes-get
  description: All episodes for a given series. Paginated with 100 results per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodes-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Query
  x-api-slug: seriesidepisodesquery-get
  description: This route allows the user to query against episodes for the given
    series. The response is a paginated array of episode records that have been filtered
    down to basic information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodesquery-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Query Params
  x-api-slug: seriesidepisodesqueryparams-get
  description: Returns the allowed query keys for the `/series/{id}/episodes/query`
    route
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodesqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Summary
  x-api-slug: seriesidepisodessummary-get
  description: |-
    Returns a summary of the episodes and seasons available for the series.

    __Note__: Season "0" is for all episodes that are considered to be specials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodessummary-get-openapi.md
- name: The TVDB API v2 - Get Series Filter
  x-api-slug: seriesidfilter-get
  description: Returns a series records, filtered by the supplied comma-separated
    list of keys. Query keys can be found at the `/series/{id}/filter/params` route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidfilter-get-openapi.md
- name: The TVDB API v2 - Get Series Filter Params
  x-api-slug: seriesidfilterparams-get
  description: Returns the list of keys available for the `/series/{id}/filter` route
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidfilterparams-get-openapi.md
- name: The TVDB API v2 - Get Series Images
  x-api-slug: seriesidimages-get
  description: Returns a summary of the images for a particular series
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimages-get-openapi.md
- name: The TVDB API v2 - Get Series Images Query
  x-api-slug: seriesidimagesquery-get
  description: Query images for the given series ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimagesquery-get-openapi.md
- name: The TVDB API v2 - Get Series Images Query Params
  x-api-slug: seriesidimagesqueryparams-get
  description: Returns the allowed query keys for the `/series/{id}/images/query`
    route. Contains a parameter record for each unique `keyType`, listing values that
    will return results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimagesqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Updated Query
  x-api-slug: updatedquery-get
  description: |-
    Returns an array of series that have changed in a maximum of one week blocks since the provided `fromTime`.


    The user may specify a `toTime` to grab results for less than a week. Any timespan larger than a week will be reduced down to one week automatically.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/updatedquery-get-openapi.md
- name: The TVDB API v2 - Get Updated Query Params
  x-api-slug: updatedqueryparams-get
  description: Returns an array of valid query keys for the `/updated/query/params`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/updatedqueryparams-get-openapi.md
- name: The TVDB API v2 - Get User
  x-api-slug: user-get
  description: Returns basic information about the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/user-get-openapi.md
- name: The TVDB API v2 - Get User Favorites
  x-api-slug: userfavorites-get
  description: Returns an array of favorite series for a given user, will be a blank
    array if no favorites exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavorites-get-openapi.md
- name: The TVDB API v2 - Delete User Favorites
  x-api-slug: userfavoritesid-delete
  description: Deletes the given series ID from the user???s favorite???s list and
    returns the updated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavoritesid-delete-openapi.md
- name: The TVDB API v2 - Put User Favorites
  x-api-slug: userfavoritesid-put
  description: Adds the supplied series ID to the user???s favorite???s list and returns
    the updated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavoritesid-put-openapi.md
- name: The TVDB API v2 - Get User Ratings
  x-api-slug: userratings-get
  description: Returns an array of ratings for the given user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratings-get-openapi.md
- name: The TVDB API v2 - Get User Ratings Query
  x-api-slug: userratingsquery-get
  description: Returns an array of ratings for a given user that match the query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsquery-get-openapi.md
- name: The TVDB API v2 - Get User Ratings Query Params
  x-api-slug: userratingsqueryparams-get
  description: Returns a list of query params for use in the `/user/ratings/query`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsqueryparams-get-openapi.md
- name: The TVDB API v2 - Delete User Ratings Itemtype Itemid
  x-api-slug: userratingsitemtypeitemid-delete
  description: This route deletes a given rating of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsitemtypeitemid-delete-openapi.md
- name: The TVDB API v2 - Put User Ratings Itemtype Itemid Itemrating
  x-api-slug: userratingsitemtypeitemiditemrating-put
  description: This route updates a given rating of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsitemtypeitemiditemrating-put-openapi.md
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
- name: The TVDB API v2 - Post Login
  x-api-slug: login-post
  description: Returns a session token to be included in the rest of the requests.
    Note that API key authentication is required for all subsequent requests and user
    auth is required for routes in the `User` section
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/login-post-openapi.md
- name: The TVDB API v2 - Get Refresh Token
  x-api-slug: refresh-token-get
  description: Refreshes your current, valid JWT token and returns a new token. Hit
    this route so that you do not have to post to `/login` with your API key and credentials
    once you have already been authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/refresh-token-get-openapi.md
- name: The TVDB API v2 - Get Search Series
  x-api-slug: searchseries-get
  description: Allows the user to search for a series based on the following parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/searchseries-get-openapi.md
- name: The TVDB API v2 - Get Search Series Params
  x-api-slug: searchseriesparams-get
  description: Returns an array of parameters to query by in the `/search/series`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/searchseriesparams-get-openapi.md
- name: The TVDB API v2 - Get Series
  x-api-slug: seriesid-get
  description: Returns a series records that contains all information known about
    a particular series id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesid-get-openapi.md
- name: The TVDB API v2 - Head Series
  x-api-slug: seriesid-head
  description: Returns header information only about the given series ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesid-head-openapi.md
- name: The TVDB API v2 - Get Series Actors
  x-api-slug: seriesidactors-get
  description: Returns actors for the given series id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidactors-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes
  x-api-slug: seriesidepisodes-get
  description: All episodes for a given series. Paginated with 100 results per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodes-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Query
  x-api-slug: seriesidepisodesquery-get
  description: This route allows the user to query against episodes for the given
    series. The response is a paginated array of episode records that have been filtered
    down to basic information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodesquery-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Query Params
  x-api-slug: seriesidepisodesqueryparams-get
  description: Returns the allowed query keys for the `/series/{id}/episodes/query`
    route
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodesqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Summary
  x-api-slug: seriesidepisodessummary-get
  description: |-
    Returns a summary of the episodes and seasons available for the series.

    __Note__: Season "0" is for all episodes that are considered to be specials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodessummary-get-openapi.md
- name: The TVDB API v2 - Get Series Filter
  x-api-slug: seriesidfilter-get
  description: Returns a series records, filtered by the supplied comma-separated
    list of keys. Query keys can be found at the `/series/{id}/filter/params` route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidfilter-get-openapi.md
- name: The TVDB API v2 - Get Series Filter Params
  x-api-slug: seriesidfilterparams-get
  description: Returns the list of keys available for the `/series/{id}/filter` route
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidfilterparams-get-openapi.md
- name: The TVDB API v2 - Get Series Images
  x-api-slug: seriesidimages-get
  description: Returns a summary of the images for a particular series
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimages-get-openapi.md
- name: The TVDB API v2 - Get Series Images Query
  x-api-slug: seriesidimagesquery-get
  description: Query images for the given series ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimagesquery-get-openapi.md
- name: The TVDB API v2 - Get Series Images Query Params
  x-api-slug: seriesidimagesqueryparams-get
  description: Returns the allowed query keys for the `/series/{id}/images/query`
    route. Contains a parameter record for each unique `keyType`, listing values that
    will return results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimagesqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Updated Query
  x-api-slug: updatedquery-get
  description: |-
    Returns an array of series that have changed in a maximum of one week blocks since the provided `fromTime`.


    The user may specify a `toTime` to grab results for less than a week. Any timespan larger than a week will be reduced down to one week automatically.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/updatedquery-get-openapi.md
- name: The TVDB API v2 - Get Updated Query Params
  x-api-slug: updatedqueryparams-get
  description: Returns an array of valid query keys for the `/updated/query/params`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/updatedqueryparams-get-openapi.md
- name: The TVDB API v2 - Get User
  x-api-slug: user-get
  description: Returns basic information about the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/user-get-openapi.md
- name: The TVDB API v2 - Get User Favorites
  x-api-slug: userfavorites-get
  description: Returns an array of favorite series for a given user, will be a blank
    array if no favorites exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavorites-get-openapi.md
- name: The TVDB API v2 - Delete User Favorites
  x-api-slug: userfavoritesid-delete
  description: Deletes the given series ID from the user???s favorite???s list and
    returns the updated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavoritesid-delete-openapi.md
- name: The TVDB API v2 - Put User Favorites
  x-api-slug: userfavoritesid-put
  description: Adds the supplied series ID to the user???s favorite???s list and returns
    the updated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavoritesid-put-openapi.md
- name: The TVDB API v2 - Get User Ratings
  x-api-slug: userratings-get
  description: Returns an array of ratings for the given user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratings-get-openapi.md
- name: The TVDB API v2 - Get User Ratings Query
  x-api-slug: userratingsquery-get
  description: Returns an array of ratings for a given user that match the query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsquery-get-openapi.md
- name: The TVDB API v2 - Get User Ratings Query Params
  x-api-slug: userratingsqueryparams-get
  description: Returns a list of query params for use in the `/user/ratings/query`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsqueryparams-get-openapi.md
- name: The TVDB API v2 - Delete User Ratings Itemtype Itemid
  x-api-slug: userratingsitemtypeitemid-delete
  description: This route deletes a given rating of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsitemtypeitemid-delete-openapi.md
- name: The TVDB API v2 - Put User Ratings Itemtype Itemid Itemrating
  x-api-slug: userratingsitemtypeitemiditemrating-put
  description: This route updates a given rating of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsitemtypeitemiditemrating-put-openapi.md
- name: The TVDB API v2 - Put User Ratings Itemtype Itemid Itemrating
  x-api-slug: userratingsitemtypeitemiditemrating-put
  description: This route updates a given rating of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsitemtypeitemiditemrating-put-openapi.md
- name: The TVDB API v2 - Delete User Ratings Itemtype Itemid
  x-api-slug: userratingsitemtypeitemid-delete
  description: This route deletes a given rating of a given type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsitemtypeitemid-delete-openapi.md
- name: The TVDB API v2 - Get User Ratings Query Params
  x-api-slug: userratingsqueryparams-get
  description: Returns a list of query params for use in the `/user/ratings/query`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsqueryparams-get-openapi.md
- name: The TVDB API v2 - Get User Ratings Query
  x-api-slug: userratingsquery-get
  description: Returns an array of ratings for a given user that match the query.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratingsquery-get-openapi.md
- name: The TVDB API v2 - Get User Ratings
  x-api-slug: userratings-get
  description: Returns an array of ratings for the given user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userratings-get-openapi.md
- name: The TVDB API v2 - Put User Favorites
  x-api-slug: userfavoritesid-put
  description: Adds the supplied series ID to the user???s favorite???s list and returns
    the updated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavoritesid-put-openapi.md
- name: The TVDB API v2 - Delete User Favorites
  x-api-slug: userfavoritesid-delete
  description: Deletes the given series ID from the user???s favorite???s list and
    returns the updated list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavoritesid-delete-openapi.md
- name: The TVDB API v2 - Get User Favorites
  x-api-slug: userfavorites-get
  description: Returns an array of favorite series for a given user, will be a blank
    array if no favorites exist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/userfavorites-get-openapi.md
- name: The TVDB API v2 - Get User
  x-api-slug: user-get
  description: Returns basic information about the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/user-get-openapi.md
- name: The TVDB API v2 - Get Updated Query Params
  x-api-slug: updatedqueryparams-get
  description: Returns an array of valid query keys for the `/updated/query/params`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/updatedqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Updated Query
  x-api-slug: updatedquery-get
  description: |-
    Returns an array of series that have changed in a maximum of one week blocks since the provided `fromTime`.


    The user may specify a `toTime` to grab results for less than a week. Any timespan larger than a week will be reduced down to one week automatically.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/updatedquery-get-openapi.md
- name: The TVDB API v2 - Get Series Images Query Params
  x-api-slug: seriesidimagesqueryparams-get
  description: Returns the allowed query keys for the `/series/{id}/images/query`
    route. Contains a parameter record for each unique `keyType`, listing values that
    will return results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimagesqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Series Images Query
  x-api-slug: seriesidimagesquery-get
  description: Query images for the given series ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimagesquery-get-openapi.md
- name: The TVDB API v2 - Get Series Images
  x-api-slug: seriesidimages-get
  description: Returns a summary of the images for a particular series
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidimages-get-openapi.md
- name: The TVDB API v2 - Get Series Filter Params
  x-api-slug: seriesidfilterparams-get
  description: Returns the list of keys available for the `/series/{id}/filter` route
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidfilterparams-get-openapi.md
- name: The TVDB API v2 - Get Series Filter
  x-api-slug: seriesidfilter-get
  description: Returns a series records, filtered by the supplied comma-separated
    list of keys. Query keys can be found at the `/series/{id}/filter/params` route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidfilter-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Summary
  x-api-slug: seriesidepisodessummary-get
  description: |-
    Returns a summary of the episodes and seasons available for the series.

    __Note__: Season "0" is for all episodes that are considered to be specials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodessummary-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Query Params
  x-api-slug: seriesidepisodesqueryparams-get
  description: Returns the allowed query keys for the `/series/{id}/episodes/query`
    route
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodesqueryparams-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes Query
  x-api-slug: seriesidepisodesquery-get
  description: This route allows the user to query against episodes for the given
    series. The response is a paginated array of episode records that have been filtered
    down to basic information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodesquery-get-openapi.md
- name: The TVDB API v2 - Get Series Episodes
  x-api-slug: seriesidepisodes-get
  description: All episodes for a given series. Paginated with 100 results per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidepisodes-get-openapi.md
- name: The TVDB API v2 - Get Series Actors
  x-api-slug: seriesidactors-get
  description: Returns actors for the given series id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesidactors-get-openapi.md
- name: The TVDB API v2 - Head Series
  x-api-slug: seriesid-head
  description: Returns header information only about the given series ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesid-head-openapi.md
- name: The TVDB API v2 - Get Series
  x-api-slug: seriesid-get
  description: Returns a series records that contains all information known about
    a particular series id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/seriesid-get-openapi.md
- name: The TVDB API v2 - Get Search Series Params
  x-api-slug: searchseriesparams-get
  description: Returns an array of parameters to query by in the `/search/series`
    route.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/searchseriesparams-get-openapi.md
- name: The TVDB API v2 - Get Search Series
  x-api-slug: searchseries-get
  description: Allows the user to search for a series based on the following parameters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/searchseries-get-openapi.md
- name: The TVDB API v2 - Get Refresh Token
  x-api-slug: refresh-token-get
  description: Refreshes your current, valid JWT token and returns a new token. Hit
    this route so that you do not have to post to `/login` with your API key and credentials
    once you have already been authenticated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/refresh-token-get-openapi.md
- name: The TVDB API v2 - Post Login
  x-api-slug: login-post
  description: Returns a session token to be included in the rest of the requests.
    Note that API key authentication is required for all subsequent requests and user
    auth is required for routes in the `User` section
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/televisions/master/_listings/the-tvdb/login-post-openapi.md
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