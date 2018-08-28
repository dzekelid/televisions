{
  "info": {
    "name": "Entertainment Express ",
    "_postman_id": "ed709784-5d59-4e14-abac-c906c8bb4602",
    "description": "Retrieve listings for a given TeamID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Metacritic",
      "item": [
        {
          "id": "37d081f0-508c-4e81-99ff-b43b4cc73da3",
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
              "id": "6f9d63b6-0bbe-4404-a291-d49ae36031a3"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "8a48b08c-c06a-4cab-8c16-af13af1d40e1",
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
              "id": "8d8150ff-2983-410d-8b70-de0afbb9ef63"
            }
          ]
        },
        {
          "id": "8a32f28d-5cd5-4838-b858-59ec0883bcdf",
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
              "id": "0a671cc0-d1a3-4e89-b5c9-116f9a9b6d87"
            }
          ]
        },
        {
          "id": "9d451896-3329-47e8-8430-5a7d84b3e3b2",
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
              "id": "b98de003-30f4-4c1d-b160-d0acea29e2c0"
            }
          ]
        },
        {
          "id": "8ec70ddc-a11c-418c-86e4-c3230bc7f346",
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
              "id": "17d5d582-1697-45f8-932b-385564f6ce49"
            }
          ]
        },
        {
          "id": "97129bc3-d73b-4ed5-b699-98855c7b2bc2",
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
              "id": "7a836897-699e-4a9f-a7e6-fdcc87ab2628"
            }
          ]
        },
        {
          "id": "570e386d-345f-44d3-b5de-98cda8593491",
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
              "id": "aba3fd8b-c854-4ae2-be91-359ae404ed70"
            }
          ]
        },
        {
          "id": "73165bb3-4356-4600-8650-0972c881badf",
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
              "id": "da552af0-6df7-44d1-9cfc-2ff9ac6d42a3"
            }
          ]
        },
        {
          "id": "98ac3d6f-fa7b-430b-ba59-c0e1ea99a7ea",
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
              "id": "22559d05-8ecc-43a1-bd98-280b3575225c"
            }
          ]
        },
        {
          "id": "5ef7df53-3dbd-437b-a78c-ef64a540a9f1",
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
              "id": "60422974-0b8c-4896-a708-48d6da504fb1"
            }
          ]
        },
        {
          "id": "c23331ee-8bbe-4953-b6ca-42bd97d416a7",
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
              "id": "3aa9248a-890a-4678-8d54-31d5ecea8347"
            }
          ]
        },
        {
          "id": "8c33a201-4daa-4bfa-934d-cb488193ef6a",
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
              "id": "c8f40ea3-07f8-4892-9844-cd1c373f495c"
            }
          ]
        },
        {
          "id": "6120d378-ce85-48c2-a590-2ccbac4d526e",
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
              "id": "1a45131b-778a-4139-915f-e557ad5500e5"
            }
          ]
        },
        {
          "id": "c216d4e0-a5e9-4275-ab19-91d2d465964c",
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
              "id": "4db562cd-adb2-422e-a968-2f0559729961"
            }
          ]
        },
        {
          "id": "16d55f48-ece6-480d-833c-881a8189b186",
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
              "id": "e4ef864b-4c58-4276-ae49-155f3779f086"
            }
          ]
        },
        {
          "id": "7edfce79-79f0-4da3-8454-69a65f628e5e",
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
              "id": "0ec289f7-f397-4d0b-b242-cdc17b75ac6e"
            }
          ]
        },
        {
          "id": "a2f5c8ae-613d-4d52-a1bf-1a83f93d7ffb",
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
              "id": "77ab002b-3fd1-4c4e-a309-fadea9a1390b"
            }
          ]
        },
        {
          "id": "872e8651-490c-44e7-8ef0-45bc68d209c5",
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
              "id": "91334b35-d0c8-44e7-85fa-87ef75d6cc3d"
            }
          ]
        },
        {
          "id": "6201c06b-34a2-43a1-a359-a8f6461dc059",
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
              "id": "ed1b4586-8388-4a5a-bd6a-9901321f8844"
            }
          ]
        },
        {
          "id": "52f71fc6-cc5f-4566-8acb-3d77d648b4a2",
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
              "id": "cbed153c-a72d-4c0f-856b-6609b2d5691c"
            }
          ]
        },
        {
          "id": "6319f552-0b86-444a-aa5c-a8ab87b9e055",
          "name": "GetTvMediaTeamById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/teams/:TeamID"
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
                  "id": "TeamID",
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
            "description": "Gets details for a specific team."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92f68611-6d4d-4420-bc9d-490e6df3eb01"
            }
          ]
        },
        {
          "id": "f48d1dee-ba43-4b64-a5df-ecf55602c2bd",
          "name": "GetTvMediaTeamListings",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "TvMedia/teams/:TeamID/listings"
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
                  "id": "TeamID",
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
            "description": "Retrieve listings for a given TeamID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dfd231f7-2a86-4383-84fb-466c97a933e5"
            }
          ]
        }
      ]
    }
  ]
}