{
  "info": {
    "name": "Entertainment Express ",
    "_postman_id": "85c0e415-eb40-485b-b99b-7d3af471f4d1",
    "description": "Gets list of sports leagues.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Metacritic",
      "item": [
        {
          "id": "2db90864-a9f4-40db-8aaa-311436d89a6e",
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
              "id": "435c2afe-8414-4d3d-b66e-073d8e1208fb"
            }
          ]
        }
      ]
    },
    {
      "name": "TvMedia",
      "item": [
        {
          "id": "981d2fef-80a9-41b0-81c9-68b06a2e2dfa",
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
              "id": "4c817679-bd42-4c0d-a710-5306290f4a9e"
            }
          ]
        },
        {
          "id": "13f9477a-7173-45e7-a915-ec8f985027bd",
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
              "id": "97eae7d4-c2e3-4359-9025-7006915a6791"
            }
          ]
        },
        {
          "id": "0b08f31b-29b7-43f2-ab98-21eca31fc137",
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
              "id": "87f06265-2879-4cf2-9d04-cb86761edfe8"
            }
          ]
        },
        {
          "id": "aec4d9df-d32a-4aca-9012-afc2662e1716",
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
              "id": "50c2d11b-df72-4da3-8919-cd8af161987f"
            }
          ]
        }
      ]
    }
  ]
}