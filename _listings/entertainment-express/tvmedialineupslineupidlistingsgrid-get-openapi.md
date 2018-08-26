---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 0
info:
  title: 'Entertainment Express '
  description: A collection of listings grouped by channel and ordered by listDateTime.
    The grid dimensions ( time x channels ) can be modified by using the start, end,
    startchan and maxchan parameters. Channels without any listings will be returned
    with an empty listings collection.
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
  /TvMedia/genres/movies:
    get:
      summary: ""
      description: Gets list of movie genres.
      operationId: GetTvMediaMovieGenres
      x-api-path-slug: tvmediagenresmovies-get
      parameters:
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Genres
      - Movies
  /TvMedia/genres/shows:
    get:
      summary: ""
      description: Gets list of show genres.
      operationId: GetTvMediaShowGenres
      x-api-path-slug: tvmediagenresshows-get
      parameters:
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Genres
      - Shows
  /TvMedia/genres/sports:
    get:
      summary: ""
      description: Gets list of sports genres.
      operationId: GetTvMediaSportGenres
      x-api-path-slug: tvmediagenressports-get
      parameters:
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Genres
      - Sports
  /TvMedia/leagues:
    get:
      summary: ""
      description: Gets list of sports leagues.
      operationId: GetTvMediaLeagues
      x-api-path-slug: tvmedialeagues-get
      parameters:
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Leagues
  /TvMedia/leagues/{LeagueID}/listings:
    get:
      summary: ""
      description: Retrieve listings for a given leagueID.
      operationId: GetTvMediaLeagueListings
      x-api-path-slug: tvmedialeaguesleagueidlistings-get
      parameters:
      - in: query
        name: AdultContent
        description: Defaults to 1 (allowed)
      - in: query
        name: Channel
        description: Include only channel(s) with this number, single or array values
          accepted
      - in: query
        name: DescriptiveVideoOnly
        description: Only displays listings which are flagged as being broadcast with
          Descriptive Video
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: DisplayArtwork
        description: Displays the Artwork information
      - in: query
        name: End
        description: UTC end time in ISO8601
      - in: query
        name: EndChan
        description: Highest channel
      - in: query
        name: ExcludeChan
        description: Exclude channels by number, single or array values accepted
      - in: query
        name: ExcludeShowType
        description: Exclude only these show type ID(s), array or single values accepted
      - in: query
        name: ExcludeStation
        description: Filter out station IDs; array or single value accepted
      - in: query
        name: Id
        description: ListingID, array or single values accepted
      - in: query
        name: League
        description: Get only sports listings in the given league ID(s)
      - in: path
        name: LeagueID
        description: League ID
      - in: query
        name: LineupID
        description: Lineup ID
      - in: query
        name: LiveOnly
        description: Only displays live listings
      - in: query
        name: NewShowsOnly
        description: Get new shows only
      - in: query
        name: NotYetStarted
        description: Only displays listings which are starting on or after the given
          start time
      - in: query
        name: Search
        description: 'search value: can be a show, episode, movie, team, league, person,
          etc'
      - in: query
        name: ShowType
        description: Include only these show type ID(s), array or single values accepted
      - in: query
        name: SportEventsOnly
        description: Get sporting events only
      - in: query
        name: SportType
        description: Get only sports listings of type sportTypeID
      - in: query
        name: Start
        description: UTC start time in ISO8601
      - in: query
        name: StartChan
        description: Lowest channel
      - in: query
        name: Station
        description: Filter by station ID
      - in: query
        name: Team
        description: Filter by teams playing by name(teams
      - in: query
        name: TimeZone
        description: Set a timezone or time offset for listing times (listDateTime
          property)
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Leagues
      - LeagueID
      - Listings
  /TvMedia/leagues/{LeagueID}/teams:
    get:
      summary: ""
      description: Gets list of teams in a league.
      operationId: GetTvMediaTeams
      x-api-path-slug: tvmedialeaguesleagueidteams-get
      parameters:
      - in: path
        name: LeagueID
        description: League ID
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Leagues
      - LeagueID
      - Teams
  /TvMedia/lineups:
    get:
      summary: ""
      description: Get lineups by postal code.
      operationId: GetTvMediaLineupsByPostalCode
      x-api-path-slug: tvmedialineups-get
      parameters:
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: LineupType
        description: Filter by lineup type, valid types are OTA, SAT, CAB, IPTV
      - in: query
        name: PostalCode
        description: Postal code
      - in: query
        name: ProviderId
        description: Filter by provider ID
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
  /TvMedia/lineups/browse:
    get:
      summary: ""
      description: Starting point for lineup browser, returns available countries.
      operationId: GetTvMediaCountries
      x-api-path-slug: tvmedialineupsbrowse-get
      parameters:
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
  /TvMedia/lineups/browse/{CountryID}:
    get:
      summary: ""
      description: Browse regions by country.
      operationId: GetTvMediaRegions
      x-api-path-slug: tvmedialineupsbrowsecountryid-get
      parameters:
      - in: path
        name: CountryID
        description: Country abbreviation
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
      - CountryID
  /TvMedia/lineups/browse/{CountryID}/{RegionID}:
    get:
      summary: ""
      description: Get service areas for a specific country and region.
      operationId: GetTvMediaServiceAreas
      x-api-path-slug: tvmedialineupsbrowsecountryidregionid-get
      parameters:
      - in: path
        name: CountryID
        description: Country abbreviation
      - in: path
        name: RegionID
        description: Region abbreviation
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
      - CountryID
      - RegionID
  /TvMedia/lineups/browse/{CountryID}/{RegionID}/{AreaID}:
    get:
      summary: ""
      description: Get lineups by AreaID.
      operationId: GetTvMediaLineupsByAreaID
      x-api-path-slug: tvmedialineupsbrowsecountryidregionidareaid-get
      parameters:
      - in: path
        name: AreaID
        description: Service area ID
      - in: path
        name: CountryID
        description: Country abbreviation
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: LineupType
        description: Filter by lineup type, valid types are OTA, SAT, CAB, IPTV
      - in: query
        name: ProviderId
        description: Filter by provider ID
      - in: path
        name: RegionID
        description: Region abbreviation
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Browse
      - CountryID
      - RegionID
      - AreaID
  /TvMedia/lineups/geo:
    get:
      summary: ""
      description: Get lineups by latitude and longitude.
      operationId: GetTvMediaLineupsByLatitudeLongitude
      x-api-path-slug: tvmedialineupsgeo-get
      parameters:
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: Latitude
        description: Latitude (geographic coordinate)
      - in: query
        name: LineupType
        description: Filter by lineup type, valid types are OTA, SAT, CAB, IPTV
      - in: query
        name: Longitude
        description: Longitude (geographic coordinate)
      - in: query
        name: ProviderId
        description: Filter by provider ID
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - Geo
  /TvMedia/lineups/{LineupID}:
    get:
      summary: ""
      description: Get lineups by specific LineupID.
      operationId: GetTvMediaLineupByID
      x-api-path-slug: tvmedialineupslineupid-get
      parameters:
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: path
        name: LineupID
        description: Lineup ID
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - LineupID
  /TvMedia/lineups/{LineupID}/listings:
    get:
      summary: ""
      description: Retrieve individual listings for a given lineup ordered by start
        time (listDateTime) and channel number; unless using the search parameter,
        in which case they will be ordered by search term relevance.
      operationId: GetTvMediaLineupListings
      x-api-path-slug: tvmedialineupslineupidlistings-get
      parameters:
      - in: query
        name: AdultContent
        description: Defaults to 1 (allowed)
      - in: query
        name: Channel
        description: Include only channel(s) with this number, single or array values
          accepted
      - in: query
        name: DescriptiveVideoOnly
        description: Only displays listings which are flagged as being broadcast with
          Descriptive Video
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: DisplayArtwork
        description: Displays the Artwork information
      - in: query
        name: End
        description: UTC end time in ISO8601
      - in: query
        name: EndChan
        description: Highest channel
      - in: query
        name: ExcludeChan
        description: Exclude channels by number, single or array values accepted
      - in: query
        name: ExcludeShowType
        description: Exclude only these show type ID(s), array or single values accepted
      - in: query
        name: ExcludeStation
        description: Filter out station IDs; array or single value accepted
      - in: query
        name: Id
        description: ListingID, array or single values accepted
      - in: query
        name: League
        description: Get only sports listings in the given league ID(s)
      - in: path
        name: LineupID
        description: Lineup ID
      - in: query
        name: LiveOnly
        description: Only displays live listings
      - in: query
        name: NewShowsOnly
        description: Get new shows only
      - in: query
        name: NotYetStarted
        description: Only displays listings which are starting on or after the given
          start time
      - in: query
        name: Search
        description: 'search value: can be a show, episode, movie, team, league, person,
          etc'
      - in: query
        name: ShowType
        description: Include only these show type ID(s), array or single values accepted
      - in: query
        name: SportEventsOnly
        description: Get sporting events only
      - in: query
        name: SportType
        description: Get only sports listings of type sportTypeID
      - in: query
        name: Start
        description: UTC start time in ISO8601
      - in: query
        name: StartChan
        description: Lowest channel
      - in: query
        name: Station
        description: Filter by station ID
      - in: query
        name: Team
        description: Filter by teams playing by name(teams
      - in: query
        name: TimeZone
        description: Set a timezone or time offset for listing times (listDateTime
          property)
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - LineupID
      - Listings
  /TvMedia/lineups/{LineupID}/listings/grid:
    get:
      summary: ""
      description: A collection of listings grouped by channel and ordered by listDateTime.
        The grid dimensions ( time x channels ) can be modified by using the start,
        end, startchan and maxchan parameters. Channels without any listings will
        be returned with an empty listings collection.
      operationId: GetTvMediaLineupListingsGrid
      x-api-path-slug: tvmedialineupslineupidlistingsgrid-get
      parameters:
      - in: query
        name: AdultContent
        description: Defaults to 1 (allowed)
      - in: query
        name: Channel
        description: Include only channel(s) with this number, single or array values
          accepted
      - in: query
        name: DescriptiveVideoOnly
        description: Only displays listings which are flagged as being broadcast with
          Descriptive Video
      - in: query
        name: Detail
        description: Set level of detail for response
      - in: query
        name: DisplayArtwork
        description: Displays the Artwork information
      - in: query
        name: End
        description: UTC end time in ISO8601
      - in: query
        name: EndChan
        description: Highest channel
      - in: query
        name: ExcludeChan
        description: Exclude channels by number, single or array values accepted
      - in: query
        name: ExcludeShowType
        description: Exclude only these show type ID(s), array or single values accepted
      - in: query
        name: ExcludeStation
        description: Filter out station IDs; array or single value accepted
      - in: query
        name: Id
        description: ListingID, array or single values accepted
      - in: query
        name: League
        description: Get only sports listings in the given league ID(s)
      - in: path
        name: LineupID
        description: Lineup ID
      - in: query
        name: LiveOnly
        description: Only displays live listings
      - in: query
        name: NewShowsOnly
        description: Get new shows only
      - in: query
        name: NotYetStarted
        description: Only displays listings which are starting on or after the given
          start time
      - in: query
        name: Search
        description: 'search value: can be a show, episode, movie, team, league, person,
          etc'
      - in: query
        name: ShowType
        description: Include only these show type ID(s), array or single values accepted
      - in: query
        name: SportEventsOnly
        description: Get sporting events only
      - in: query
        name: SportType
        description: Get only sports listings of type sportTypeID
      - in: query
        name: Start
        description: UTC start time in ISO8601
      - in: query
        name: StartChan
        description: Lowest channel
      - in: query
        name: Station
        description: Filter by station ID
      - in: query
        name: Team
        description: Filter by teams playing by name(teams
      - in: query
        name: TimeZone
        description: Set a timezone or time offset for listing times (listDateTime
          property)
      - in: query
        name: TvMediaApiKey
        description: API Key supplied by TvMedia
      responses:
        200:
          description: OK
      tags:
      - TvMedia
      - Lineups
      - LineupID
      - Listings
      - Grid
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