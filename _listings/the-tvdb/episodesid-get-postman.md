{
  "info": {
    "name": "The TVDB Get Episodes",
    "_postman_id": "932e273e-d55e-442a-a42a-42fb6caa370f",
    "description": "Returns the full information for a given episode id. __Deprecation Warning:__ The _director_ key will be deprecated in favor of the new _directors_ key in a future release.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "a4c1ba8f-88f5-4e47-bb9d-30c6ad8f69e3",
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
              "id": "c4f3fac1-5098-468f-ab97-a6ade296ca9a"
            }
          ]
        }
      ]
    }
  ]
}