{
  "info": {
    "name": "Entertainment Express ",
    "_postman_id": "84bfb918-34dd-42d5-acb9-c94d44bcd1d9",
    "description": "Gets list of show genres.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Changes",
      "item": [
        {
          "id": "b090414e-878a-4024-afa1-c6e83e1722ee",
          "name": "GetShowChangeHistory",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Shows/History/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
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
            "description": "All new and updated shows from requested date and time.  When a record gets updated, use the ID to get the full show object and replace the data in your cache."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05ea944d-68ab-4bf3-9dd0-d9a0182073a7"
            }
          ]
        },
        {
          "id": "d97fec36-2a10-446b-b6d7-ba9d4c1b1102",
          "name": "GetShowChangeHistoryWithEntity",
          "request": {
            "url": "http://ee.iva-api.com/Changes/Shows/HistoryWithEntity/?Date=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
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
            "description": "Returns a list of ShowId and entity of any show that has been updated."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f37b7207-9b3d-4362-982c-20472b26c5f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Charts",
      "item": [
        {
          "id": "85cb03dd-774b-4bf6-8459-b6d52cb98668",
          "name": "GetChartShowsPopular",
          "request": {
            "url": "http://ee.iva-api.com/Charts/Shows/Popular?Skip=%7B%7D&Take=%7B%7D",
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
            "description": "Requires Skip and Take. Maximum page size is 100."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c354cb1-873e-4e67-8eaf-613eaa7420d1"
            }
          ]
        }
      ]
    },
    {
      "name": "GoWatchIt",
      "item": [
        {
          "id": "802dc8fb-fcc9-46f9-af4c-93ac2f0d32a6",
          "name": "GetGoWatchItShowAvailabilities",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "GoWatchIt/Shows/:Id/Availabilities"
              ],
              "query": [
                {
                  "key": "ApiKey",
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
            "description": "Returns GoWatchIt show availability by Entertainment Show ID.  Special permission is required to access this endpoint. Please contact [Sales](mailto:Sales@InternetVideoArchive.com) for more information."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e80be10e-7346-4f1e-bc89-73af75d3d666"
            }
          ]
        }
      ]
    },
    {
      "name": "Shows",
      "item": [
        {
          "id": "079cf257-7a55-400e-bbaa-1246cc3543bb",
          "name": "GetAllShows",
          "request": {
            "url": "http://ee.iva-api.com/Shows/All?Includes=%7B%7D&Skip=%7B%7D&Take=%7B%7D",
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
            "description": "By default the API will only return basic title information. Additional objects can be included by passing the object in the Includes parameter. \n\n\n`Subscriptions with \"Limited\" data will only be able to include basic title information, Videos, EpisodicVideos, and SeasonVideos.`"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0eae1e6-f7c2-4b77-9760-4198df823d93"
            }
          ]
        },
        {
          "id": "6dfcdcb5-a27a-409e-8939-fd5c1d73f4c5",
          "name": "GetShowAlternateIdTypes",
          "request": {
            "url": "http://ee.iva-api.com/Shows/AlternateIdTypes",
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
            "description": "Alternate Id types refer to the 3rd party ID sets IVA data has matched.  **Ex: IMDB**"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50b5b313-c54c-4f79-8010-1509b3000072"
            }
          ]
        },
        {
          "id": "6c80bc4b-9e73-4385-abe3-25c65f27e5ca",
          "name": "MatchToShow",
          "request": {
            "url": "http://ee.iva-api.com/Shows/Match/?AlternateTitles=%7B%7D&Cast=%7B%7D&Directors=%7B%7D&StringDistance=%7B%7D&Title=%7B%7D&Year=%7B%7D",
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
            "description": "Use to match IVA show data to another data source using title, director, cast, etc."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1bcddd4-6745-499a-965e-95d8be953632"
            }
          ]
        },
        {
          "id": "822e3483-976f-4f87-aec2-755e7f608b54",
          "name": "GetShowReleaseTypes",
          "request": {
            "url": "http://ee.iva-api.com/Shows/ReleaseTypes",
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
            "description": "Release types refer to the type of release and are used in the releases object for a show."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a67b475f-f2a9-404a-868a-d018531c568e"
            }
          ]
        },
        {
          "id": "f4573c69-bd93-4d4e-ac33-a3786a36ae74",
          "name": "SearchAndDiscoverShow",
          "request": {
            "url": "http://ee.iva-api.com/Shows/SearchAndDiscover?Filter=%7B%7D&IncludeTotalResultCount=%7B%7D&OrderBy=%7B%7D&SearchFields=%7B%7D&SearchMode=%7B%7D&SelectFields=%7B%7D&Skip=%7B%7D&term=%7B%7D&Top=%7B%7D",
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
            "description": "Searchable Fields: Title, AlternateTitles, Genres, Tags, Cast, Directors, Descriptions, Ratings, OriginalLanguage. [Syntax Ref](https://docs.microsoft.com/en-us/rest/api/searchservice/simple-query-syntax-in-azure-search)\n\nFilterable Fields: Id, Title, AlternateTitles, Genres, OriginalAirDate, Year, Tags, Cast, Directors, Descriptions, HasVideo, ImageFilePath, Ratings, OriginalLanguage, Created, Modified, NumberOfSeasons, NumberOfEpisodes. [Syntax Ref](https://docs.microsoft.com/en-us/rest/api/searchservice/simple-query-syntax-in-azure-search)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "979b6a82-64f6-4ada-99b1-eba7699cb0e8"
            }
          ]
        },
        {
          "id": "600ddeed-6c61-4dd6-8b66-812070dc4a5b",
          "name": "GetSeasonByNumber",
          "request": {
            "url": "http://ee.iva-api.com/Shows/Season/?Id=%7B%7D&SeasonNumber=%7B%7D",
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
            "description": "Use the IVA ShowId and a season number to get a season details and video asset data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "783515f0-28d1-46dc-9e44-c792b0ac5f1a"
            }
          ]
        },
        {
          "id": "2470ae79-50eb-46aa-95f6-2242ac2aac72",
          "name": "GetEpisodeByNumber",
          "request": {
            "url": "http://ee.iva-api.com/Shows/Seasons/Episode/?EpisodeNumber=%7B%7D&Id=%7B%7D&SeasonNumber=%7B%7D",
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
            "description": "Some use cases find it useful to be able to pass a season number and episode number of a known show to get the data for that exact episode."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "279d57d4-9615-467f-bc34-f9f4f6be10c9"
            }
          ]
        },
        {
          "id": "eb7ba082-e17e-4f6e-a299-76138ef71bb1",
          "name": "GetEpisode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "Shows/Seasons/Episodes/:Id"
              ],
              "query": [
                {
                  "key": "Includes",
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
            "description": "Returns the episode details for a specific episode ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "894706d2-f90f-4979-a017-b566d62ef35a"
            }
          ]
        },
        {
          "id": "6d68aa57-6cec-4949-b910-2ee05ad81c25",
          "name": "GetSeason",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "Shows/Seasons/:Id"
              ],
              "query": [
                {
                  "key": "Includes",
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
            "description": "Use with a SeasonId to return details for a season including any video asset data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21b1e66b-627f-4da9-89d3-fea68feea6c5"
            }
          ]
        },
        {
          "id": "0ecb3051-75bb-4720-9792-5d1f5ff2ecbb",
          "name": "GetShowCertifications",
          "request": {
            "url": "http://ee.iva-api.com/Shows/ShowCertifications",
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
            "description": "List of Show Certifications and definitions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "522aa895-bca1-47fe-b2f0-9da2c383e5ac"
            }
          ]
        },
        {
          "id": "387a4d92-3300-409f-91bc-ff2c051b77e2",
          "name": "GetShowGenres",
          "request": {
            "url": "http://ee.iva-api.com/Shows/ShowGenres",
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
            "description": "Returns a list of all the show genres used in the IVA database."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4debd57e-4d8c-4f70-a5a1-f18aaeb339de"
            }
          ]
        },
        {
          "id": "d8cb3e36-4ba4-447c-9004-ff3216df5e52",
          "name": "GetShow",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "Shows/:Id"
              ],
              "query": [
                {
                  "key": "Includes",
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
            "description": "By default the API will only return basic title information. Additional objects can be included by passing the object in the Includes parameter.  \n\n\n`Subscriptions with \"Limited\" data will only be able to include basic title information, Videos, EpisodicVideos, and SeasonVideos.`"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "515bc64f-9f95-42fc-915c-de473fdbc1d6"
            }
          ]
        },
        {
          "id": "b4b3adff-7a37-4cae-aa8c-4606efba6775",
          "name": "GetSeasonBySeasonNumber",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "Shows/:Id/Seasons/:SeasonNumber"
              ],
              "query": [
                {
                  "key": "Includes",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "Id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SeasonNumber",
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
            "description": "Depreciated. Use GetSeasonBySeasonNumber instead.  Requires a valid ShowId and Season Number."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "441a31cd-78a3-4b03-819b-381efb5bf9d7"
            }
          ]
        },
        {
          "id": "04b07f04-da59-4f92-9425-44d3f5e98ddb",
          "name": "GetEpisodeByEpisodeNumber",
          "request": {
            "url": {
              "protocol": "http",
              "host": "ee.iva-api.com",
              "path": [
                "Shows/:Id/Seasons/:SeasonNumber/Episodes/:EpisodeNumber"
              ],
              "query": [
                {
                  "key": "Includes",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "EpisodeNumber",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "Id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "SeasonNumber",
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
            "description": "Requires a valid ShowId, Season Number and Episode Number."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2dc1f549-2bf8-4efc-be8d-38921030d842"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "bbae41fe-4cfc-421e-b223-bcaee6faa7d9",
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
              "id": "a2cf5e0f-bf6d-4fc3-acd9-162d7abf6ba5"
            }
          ]
        }
      ]
    }
  ]
}