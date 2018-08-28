{
  "info": {
    "name": "TVmaze user Get User Episodes",
    "_postman_id": "e2765175-15e5-4a4e-adf4-df8d9fa466cb",
    "description": "Get user episodes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "7de0de6d-46e7-40f5-ac77-0ab129f42aa9",
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
              "id": "4da4f763-db87-42a5-b000-39c81ec508bb"
            }
          ]
        }
      ]
    }
  ]
}