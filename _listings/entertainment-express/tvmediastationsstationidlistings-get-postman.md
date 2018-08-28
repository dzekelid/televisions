{
  "info": {
    "name": "Entertainment Express Stations are not tied to lineups, therefore no channel numbers will be present in the response, unlike most other listing operations.",
    "_postman_id": "469155cc-c2d6-44c4-97f6-40b3e03489a9",
    "description": "Get listings for a given station.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Metacritic",
      "item": [
        {
          "id": "fe1078dc-fe97-4076-9e59-bff818d023f8",
          "name": "GetMetacriticTv",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "Metacritic/TV/:Id"
              ],
              "query": [
                {
                  "key": "SeasonNumber",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "Id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns Metacritic TV information by Entertainment Show ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1aeb2179-aad2-4112-bc05-820ad7cbb713"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "fbe1a3ea-e4da-4a67-9998-c52a301be82d",
          "name": "GetTvMediaMovieGenres",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/genres/movies?TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets list of movie genres."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebbda7a9-ba8c-4c4e-8cb4-8243d768f529"
            }
          ]
        },
        {
          "id": "ed449f15-bf19-4f45-bc81-f76f1c22e221",
          "name": "GetTvMediaShowGenres",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/genres/shows?TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets list of show genres."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6bb4344-1c25-4aa5-872d-ec21325c550d"
            }
          ]
        },
        {
          "id": "cfd9d53f-ed04-4b1b-ae6f-8aa3d7fc05f0",
          "name": "GetTvMediaSportGenres",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/genres/sports?TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets list of sports genres."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76ed87fb-6b05-499a-8315-ff3ee8021967"
            }
          ]
        },
        {
          "id": "2a4dd89f-4dc7-41f0-aa4f-a2e03cf20bf7",
          "name": "GetTvMediaLeagues",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/leagues?TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets list of sports leagues."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31e798ca-6769-4d55-8821-f904376f31c2"
            }
          ]
        },
        {
          "id": "a44e0278-1480-46dc-936c-3394b9d6f578",
          "name": "GetTvMediaLeagueListings",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/leagues/:LeagueID/listings"
              ],
              "query": [
                {
                  "key": "AdultContent",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Channel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DescriptiveVideoOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DisplayArtwork",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "End",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "EndChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeStation",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "League",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LineupID",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LiveOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NewShowsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NotYetStarted",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Search",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportEventsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "StartChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Station",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Team",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TimeZone",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "LeagueID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve listings for a given leagueID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a3c3458-7566-4a84-809d-6733e6fb8534"
            }
          ]
        },
        {
          "id": "d3eb4595-1055-400d-bfc3-7ee17d9c28b1",
          "name": "GetTvMediaTeams",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/leagues/:LeagueID/teams"
              ],
              "query": [
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "LeagueID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets list of teams in a league."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58270d4c-32c1-4e70-8cf6-4b06dcaf4884"
            }
          ]
        },
        {
          "id": "487114fe-fbb3-49dc-a15c-6a1cf90b1949",
          "name": "GetTvMediaLineupsByPostalCode",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/lineups?Detail=%7B%7D&LineupType=%7B%7D&PostalCode=%7B%7D&ProviderId=%7B%7D&TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get lineups by postal code."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85362412-a07a-4063-aff6-aca093ff36c4"
            }
          ]
        },
        {
          "id": "3998e4e0-bd40-4b93-8ed9-74c95e726667",
          "name": "GetTvMediaCountries",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/lineups/browse?TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Starting point for lineup browser, returns available countries."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c18e31ec-f60b-41b1-9973-16e16557edbe"
            }
          ]
        },
        {
          "id": "4fa5d8f2-7c1e-479a-8336-2c9faaff46ef",
          "name": "GetTvMediaRegions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/browse/:CountryID"
              ],
              "query": [
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "CountryID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Browse regions by country."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec07f2b8-1053-4f1a-a298-74b2698f3079"
            }
          ]
        },
        {
          "id": "5316b4c8-fb55-4717-ba06-d3d4d77f1f28",
          "name": "GetTvMediaServiceAreas",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/browse/:CountryID/:RegionID"
              ],
              "query": [
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "CountryID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "RegionID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get service areas for a specific country and region."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6b4180a-2544-47cc-8925-3328afb876b6"
            }
          ]
        },
        {
          "id": "2f2e8062-3ab8-4333-99e5-619b11fe3855",
          "name": "GetTvMediaLineupsByAreaID",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/browse/:CountryID/:RegionID/:AreaID"
              ],
              "query": [
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LineupType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ProviderId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "AreaID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "CountryID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "RegionID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get lineups by AreaID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "070ec07d-3d4f-440a-b179-69a4f61d0850"
            }
          ]
        },
        {
          "id": "11946dc8-215f-4982-bd2b-0001fbcf7212",
          "name": "GetTvMediaLineupsByLatitudeLongitude",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/lineups/geo?Detail=%7B%7D&Latitude=%7B%7D&LineupType=%7B%7D&Longitude=%7B%7D&ProviderId=%7B%7D&TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get lineups by latitude and longitude."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f47ef809-9dab-44b3-9a8a-0e1f0421c432"
            }
          ]
        },
        {
          "id": "4f05c475-4681-4b5e-9d8f-474ad702e500",
          "name": "GetTvMediaLineupByID",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/:LineupID"
              ],
              "query": [
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "LineupID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get lineups by specific LineupID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29f54a4c-d45a-43c8-bd39-a005cd3b133a"
            }
          ]
        },
        {
          "id": "f9bb0ecc-7fc4-4197-940c-7f3fa4c02e9e",
          "name": "GetTvMediaLineupListings",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/:LineupID/listings"
              ],
              "query": [
                {
                  "key": "AdultContent",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Channel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DescriptiveVideoOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DisplayArtwork",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "End",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "EndChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeStation",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "League",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LiveOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NewShowsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NotYetStarted",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Search",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportEventsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "StartChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Station",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Team",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TimeZone",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "LineupID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve individual listings for a given lineup ordered by start time (listDateTime) and channel number; unless using the search parameter, in which case they will be ordered by search term relevance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8abff3b3-afc9-4c76-a581-ed7e887d194f"
            }
          ]
        },
        {
          "id": "36754227-661e-4d10-8b0e-b9981305a863",
          "name": "GetTvMediaLineupListingsGrid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/:LineupID/listings/grid"
              ],
              "query": [
                {
                  "key": "AdultContent",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Channel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DescriptiveVideoOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DisplayArtwork",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "End",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "EndChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeStation",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "League",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LiveOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NewShowsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NotYetStarted",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Search",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportEventsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "StartChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Station",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Team",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TimeZone",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "LineupID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "A collection of listings grouped by channel and ordered by listDateTime. The grid dimensions ( time x channels ) can be modified by using the start, end, startchan and maxchan parameters. Channels without any listings will be returned with an empty listings collection."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b67eac6-d8b6-4017-a6aa-6561f7db5e4d"
            }
          ]
        },
        {
          "id": "b69f95f9-163f-4124-810d-dd1da3d50919",
          "name": "GetTvMediaLineupListingsHighlights",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/lineups/:LineupID/listings/highlights"
              ],
              "query": [
                {
                  "key": "AdultContent",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Channel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DescriptiveVideoOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DisplayArtwork",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "End",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "EndChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeStation",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "League",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LiveOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NewShowsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NotYetStarted",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Search",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportEventsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "StartChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Station",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Team",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TimeZone",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "LineupID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves featured listings. setting a start and/or end time for every request is a highly recommended."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b56752ab-1b5c-4167-b466-05d748a06b25"
            }
          ]
        },
        {
          "id": "f7a54667-1198-4e6b-bae7-797f1af9d7d9",
          "name": "GetTvMediaGenericLineups",
          "request": {
            "url": "http://ee.iva-api.com/TvMedia/reference/lineups?Detail=%7B%7D&TvMediaApiKey=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get list of generic lineup IDs that can be used.  A 'generic' lineup is not a real lineup, but a collection of stations defined by TV Media.  Any listing retrieved using a generic lineup will not return any channel number information, as it is irrelevant."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a397bddb-2823-48d6-8963-bdef9277201d"
            }
          ]
        },
        {
          "id": "4d967cc0-0080-4d0f-a5e5-26d7e7cf808e",
          "name": "GetTvMediaStation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/stations/:StationID"
              ],
              "query": [
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "StationID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets station details by ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f25299c-3d72-481f-a072-72e2373024ff"
            }
          ]
        },
        {
          "id": "843c845a-dc8d-40d9-9b5a-4f9800567a0e",
          "name": "GetTvMediaListingsByStation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/stations/:StationID/listings"
              ],
              "query": [
                {
                  "key": "AdultContent",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Channel",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DescriptiveVideoOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Detail",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "DisplayArtwork",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "End",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "EndChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ExcludeStation",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Id",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "League",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "LiveOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NewShowsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "NotYetStarted",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Search",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "ShowType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportEventsOnly",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "SportType",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Start",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "StartChan",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Station",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "Team",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TimeZone",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "TvMediaApiKey",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "StationID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get listings for a given station."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "623acd66-43f1-4c53-8846-6bab5c412836"
            }
          ]
        }
      ]
    }
  ]
}