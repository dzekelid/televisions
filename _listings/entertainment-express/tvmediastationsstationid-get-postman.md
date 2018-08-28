{
  "info": {
    "name": "Entertainment Express ",
    "_postman_id": "c3146085-71d5-4b0a-9329-f956b0d6c8a8",
    "description": "Gets station details by ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Metacritic",
      "item": [
        {
          "id": "c37913b4-a4f2-42c4-88c9-65919e0605ab",
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
              "id": "b02af8bc-2cc0-45c1-b500-8864c7feacda"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "044fa5f2-7938-4ecd-9419-58df06c228c7",
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
              "id": "6a7a3b3b-49ad-4f65-a876-c8f9233636a5"
            }
          ]
        },
        {
          "id": "9d6fd0fa-4dec-4650-81f4-00af60fb13b2",
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
              "id": "fe04b490-0c78-4484-b316-3e1554bdb5d2"
            }
          ]
        },
        {
          "id": "2325a6e0-e5b0-4e20-a59f-6c9fb78e1d69",
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
              "id": "f69d31ee-e75c-4860-8719-e8a7f7b25bbb"
            }
          ]
        },
        {
          "id": "e3889c73-8965-4b00-90f3-45bc5bc7af45",
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
              "id": "ed9d8894-ce06-4271-83a4-34057581cc55"
            }
          ]
        },
        {
          "id": "38039e9e-30ff-421f-b62d-ce8cbca63795",
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
              "id": "81e13f00-7695-4118-837d-51e39643f88d"
            }
          ]
        },
        {
          "id": "711daee1-311c-4091-863f-13851d7054b2",
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
              "id": "df6ca6a0-05c3-415e-bfe2-e1aba74de5b8"
            }
          ]
        },
        {
          "id": "c6387aaa-18ec-4a86-91c7-e43532a8c33c",
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
              "id": "f4b974ed-d863-476f-8614-4c6af007668e"
            }
          ]
        },
        {
          "id": "6ae5731b-46a9-4f29-ad2c-53bd80c3f4be",
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
              "id": "5373fb83-a43f-4852-9238-2e92f884c306"
            }
          ]
        },
        {
          "id": "6faa0f09-8330-4268-9988-eb637bdc01e2",
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
              "id": "7f89445e-0970-4972-aac2-a4a45eb51ed5"
            }
          ]
        },
        {
          "id": "599324b8-4c5c-46be-9346-999ba9627649",
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
              "id": "91b2b6af-344d-4685-83f5-6a1df8b96f3e"
            }
          ]
        },
        {
          "id": "03f6d8ef-8bde-4e67-b614-4611ee5d64a2",
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
              "id": "63bc98b2-d198-4ab6-8a20-ec745443457e"
            }
          ]
        },
        {
          "id": "08d00bed-49d9-4ca6-aaa4-8b2a4bdefe06",
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
              "id": "6ad188b0-e469-4e42-8dd6-c37b9629c644"
            }
          ]
        },
        {
          "id": "469d6823-e91d-4b95-94ca-52b370036eaa",
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
              "id": "eba7ba3b-5361-4fab-967e-30267a255761"
            }
          ]
        },
        {
          "id": "cad6e781-5dc7-4b7d-b165-d8becd6b848f",
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
              "id": "f99c03d4-6f42-430b-92ac-f7749534e185"
            }
          ]
        },
        {
          "id": "57c6d00b-247d-417a-a0a4-4c7a5c077500",
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
              "id": "b54d0f3d-4185-4516-be94-1acc41aa9833"
            }
          ]
        },
        {
          "id": "470b9882-42b4-4839-8a5e-f37c8dd7311f",
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
              "id": "82beca5d-a80c-432f-aaa8-e0e11aa06b27"
            }
          ]
        },
        {
          "id": "5a59cffa-dee1-4c27-98a3-9648da31dc9f",
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
              "id": "ef2b5ad5-ef2e-47b3-9052-14ba81c73126"
            }
          ]
        },
        {
          "id": "06507f0f-9b75-4837-9cf6-945978f924ef",
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
              "id": "f00e8116-1e08-40ec-a183-224dce5a7e68"
            }
          ]
        }
      ]
    }
  ]
}