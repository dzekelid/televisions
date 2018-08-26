{
  "info": {
    "name": "Entertainment Express ",
    "_postman_id": "8c051d6b-fa81-4d12-8f83-882fc96e8f37",
    "description": "Gets details for a specific team.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Metacritic",
      "item": [
        {
          "id": "23399893-7871-4ef3-9b8b-142ed6e08625",
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
              "id": "09ae57ec-bf78-4478-ac4f-abf34e71092c"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "fd33bed1-654c-4305-91aa-bee2869906f9",
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
              "id": "53690a95-5c2e-4a09-985a-5c9791e67f39"
            }
          ]
        },
        {
          "id": "e12349ef-8ba3-4220-a820-7b01d85849d2",
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
              "id": "9950008b-b71b-4b2a-8b9f-c5d4d330dfeb"
            }
          ]
        },
        {
          "id": "64b6e567-aadd-455e-8f64-8248a073bb05",
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
              "id": "42a67ebd-378f-40b6-b082-db73c9cfe77e"
            }
          ]
        },
        {
          "id": "96b0157d-b935-48c0-a827-04df24303a98",
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
              "id": "60aef96b-8fdf-46ba-8ab4-1fb31163eb3c"
            }
          ]
        },
        {
          "id": "68e6f78d-0453-4bf5-aea3-97730d78904a",
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
              "id": "a279a471-2475-4b8a-914a-f8464c2e6a5e"
            }
          ]
        },
        {
          "id": "3dd81b94-dce7-47c9-baf4-de30838b8e51",
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
              "id": "998b676b-7dc6-490f-ba52-c274f311e649"
            }
          ]
        },
        {
          "id": "4db4e9b0-1736-4e4d-9149-423bdb6f8e76",
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
              "id": "d2d8a271-1851-47e6-951b-86c469a18cca"
            }
          ]
        },
        {
          "id": "6b7fcb5c-c457-4f8a-a0ef-0992699300bf",
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
              "id": "00959397-4950-40ec-a386-b39ba4cba895"
            }
          ]
        },
        {
          "id": "e7e87632-66d1-4f84-9a27-519a7cd4979b",
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
              "id": "8647127d-6445-480b-9741-93f472332dcc"
            }
          ]
        },
        {
          "id": "404da245-1282-4b2f-95e5-ff31819f2234",
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
              "id": "863eaf01-5dfb-4d43-ab78-a5dba99345e1"
            }
          ]
        },
        {
          "id": "101fa6c3-74f5-4f27-b1fc-70c6df8ce6f0",
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
              "id": "98af597f-7c59-4638-951b-d27fb8fb2387"
            }
          ]
        },
        {
          "id": "a67da816-5356-4137-ae67-389778c32286",
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
              "id": "99408983-0d93-45bb-b5ec-c496f24be916"
            }
          ]
        },
        {
          "id": "24d6796b-3f3a-472d-8975-35c7e5868f1c",
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
              "id": "082b847a-5532-4416-b756-38a80f313d2d"
            }
          ]
        },
        {
          "id": "84d30425-51d2-485a-a521-2544be32279d",
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
              "id": "752d727f-8ebb-4ee9-865d-cca397c6f02f"
            }
          ]
        },
        {
          "id": "433f9ed2-80a2-472e-b942-f7c095033370",
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
              "id": "95e49c4b-a4a2-4543-8c32-bd572dc4fe85"
            }
          ]
        },
        {
          "id": "42158f35-868e-43bb-bfe4-34e0701a9bd0",
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
              "id": "dad7311c-531b-424c-9028-3318b6f5757e"
            }
          ]
        },
        {
          "id": "dd12c3ce-da55-4052-86ca-9aa74636bcb1",
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
              "id": "9bcef3a8-8c03-4790-a6dd-dea6ffa9bc17"
            }
          ]
        },
        {
          "id": "ee87af9f-a227-4095-a254-c9981712b461",
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
              "id": "cff69300-a39b-4274-ae76-848998eaee9e"
            }
          ]
        },
        {
          "id": "3dcc33f0-fc6c-4209-9266-7d60baa69d65",
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
              "id": "46911a87-fcf6-47cd-b2bb-69d7be89a3ac"
            }
          ]
        },
        {
          "id": "cb6fce47-9f31-417a-8ad5-5fb601a704ab",
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
              "id": "b8a92028-5468-41f6-b694-39a0df19b3ca"
            }
          ]
        }
      ]
    }
  ]
}