{
  "info": {
    "name": "The TVDB Get Languages",
    "_postman_id": "7cc44637-8403-4736-ad7e-93b80221a361",
    "description": "Information about a particular language, given the language ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "b961ebf1-55b2-4707-81e5-db653d61bf44",
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
              "id": "f01b9d6d-c627-4533-82aa-8aaeca4af882"
            }
          ]
        },
        {
          "id": "71bf906e-0a98-4fba-982f-f11562fbb57e",
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
              "id": "48271ae4-3c87-44ea-9c24-c89b1123e963"
            }
          ]
        },
        {
          "id": "df090505-076a-47d5-9816-080c775e742a",
          "name": "languages.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api-dev.thetvdb.com",
              "path": [
                "languages/:id"
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
            "description": "Information about a particular language, given the language ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c3fc210-a815-4fd2-b9d5-d0041ea3fda0"
            }
          ]
        }
      ]
    }
  ]
}