{
  "info": {
    "name": "The TVDB Get Languages",
    "_postman_id": "838cb653-bb68-4576-a5c4-ad084cb1a340",
    "description": "All available languages. These language abbreviations can be used in the `Accept-Language` header for routes that return translation records.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "35923b81-ce93-4559-a3c7-c12f37238c6b",
          "name": "episodes.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api-dev.thetvdb.com",
              "path": [
                "episodes/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
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
            "description": "Returns the full information for a given episode id. __Deprecation Warning:__ The _director_ key will be deprecated in favor of the new _directors_ key in a future release."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2678d0d6-e660-41dc-aee7-c90fad5258dd"
            }
          ]
        },
        {
          "id": "b61db038-7a19-45a7-8e69-40f4b10bfb06",
          "name": "languages.get",
          "request": {
            "url": "http://api-dev.thetvdb.com/languages",
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
            "description": "All available languages. These language abbreviations can be used in the `Accept-Language` header for routes that return translation records."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0563c4b-2883-4bb5-8606-cc6e00a371a2"
            }
          ]
        }
      ]
    }
  ]
}