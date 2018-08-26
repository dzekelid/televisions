---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: Entertainment Express Get Metacritic TV information.
  description: Returns Metacritic TV information by Entertainment Show ID.
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Metacritic/TV/{Id}:
    get:
      summary: Get Metacritic TV information.
      description: Returns Metacritic TV information by Entertainment Show ID.
      operationId: GetMetacriticTv
      x-api-path-slug: metacritictvid-get
      parameters:
      - in: path
        name: Id
        description: Required ID of Entertainment Show
      - in: query
        name: SeasonNumber
        description: Number of season
      responses:
        200:
          description: OK
      tags:
      - Metacritic
      - TV
      - Id
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