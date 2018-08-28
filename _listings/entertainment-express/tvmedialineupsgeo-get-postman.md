{
  "info": {
    "name": "Entertainment Express ",
    "_postman_id": "acbd81b4-19f7-45fa-ae9b-bd87620ce3bc",
    "description": "Get lineups by latitude and longitude.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Metacritic",
      "item": [
        {
          "id": "3db8c410-5664-4b82-b22c-6b2d27f48de3",
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
              "id": "3aa1cfe6-9a94-4fa6-8723-3a5e5dff01e7"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "26e57e43-efb3-4f1f-9340-c5ac62a9ce2d",
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
              "id": "d04404f3-3d71-405f-845e-61702d20bf0e"
            }
          ]
        },
        {
          "id": "16fa2683-c29a-4716-95a6-d6560a3e45dc",
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
              "id": "f995f0ab-b8cd-4b6a-85a5-33307bfe3b7b"
            }
          ]
        },
        {
          "id": "2e4ab718-e6d9-4d4a-a281-c5c3f39fbf3a",
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
              "id": "42373b41-c37c-4412-9b06-a4bfa2c93ee1"
            }
          ]
        },
        {
          "id": "b8f22a27-ad40-4741-9d0a-61f9475e575d",
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
              "id": "22ad8af7-dfee-45b5-86ad-6e3e74caa2fe"
            }
          ]
        },
        {
          "id": "bbd930d4-e3f6-4987-a1c8-848cebcf80ac",
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
              "id": "bf97a06c-2490-4f27-a291-31e5c18c3179"
            }
          ]
        },
        {
          "id": "5b1705a8-4aee-4ecd-ab7b-17ade780b70f",
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
              "id": "5ddb162d-c772-4164-8db7-faf8596c6747"
            }
          ]
        },
        {
          "id": "4e111279-4ba2-47ec-98f4-2b1ac95b7f7f",
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
              "id": "f7b28dea-33c7-432b-b297-42c1c66176f9"
            }
          ]
        },
        {
          "id": "6fe48668-20ef-4e8f-9f01-7065be8be298",
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
              "id": "816a954f-abc0-4bc4-944c-0ec4b87babc1"
            }
          ]
        },
        {
          "id": "ce610e5f-d6ed-4730-8ea6-1464798f3cf3",
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
              "id": "2e6ef41e-b6fc-4c5c-afa1-b986ee614a9d"
            }
          ]
        },
        {
          "id": "c6be0f78-2f61-40fb-9d45-7a39cc7c48e0",
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
              "id": "fc7f81d0-3e73-47e2-8ba4-4def8c0684f4"
            }
          ]
        },
        {
          "id": "2fff2028-f7cb-4039-9ae1-38bf0f6b283c",
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
              "id": "d3375916-4b1d-4fb4-9cb8-28860651acf9"
            }
          ]
        },
        {
          "id": "7c52ba6d-72de-474d-8b01-1d32908b84df",
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
              "id": "e36f7392-6d31-4809-aa5a-ccb1fb50a1dc"
            }
          ]
        }
      ]
    }
  ]
}