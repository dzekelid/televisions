{
  "info": {
    "name": "TVmaze user Parameters User Episodes",
    "_postman_id": "32a66f20-4823-4939-bd67-91bbaa13e6f1",
    "description": "Parameters user episodes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "a0894591-1fe3-4461-a2d1-c919cda2f04a",
          "name": "getUserEpisodes",
          "request": {
            "url": "http://api.tvmaze.com/v1/user/episodes?show_id=%7B%7D",
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
            "description": "Get user episodes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ede3ee30-cfc4-4ba2-8b7f-46702c6b6735"
            }
          ]
        }
      ]
    }
  ]
}