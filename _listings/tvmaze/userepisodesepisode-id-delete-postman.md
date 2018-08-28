{
  "info": {
    "name": "TVmaze user Delete User Episodes",
    "_postman_id": "b24f401d-f266-4103-a541-b485ca1e20c0",
    "description": "Delete user episodes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "ff969460-e40b-4736-bb4f-0c2d5817673a",
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
              "id": "d6386ae6-b32d-46ed-b871-1d47af28653e"
            }
          ]
        },
        {
          "id": "2c529196-21c8-4d11-bb96-d67c70e12a31",
          "name": "deleteUserEpisodesEpisode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.tvmaze.com",
              "path": [
                "v1",
                "user/episodes/:episode_id"
              ],
              "variable": [
                {
                  "id": "episode_id",
                  "value": "episode_id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
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
            "description": "Delete user episodes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0429a60f-a9a2-4049-81fd-3d9f754b7937"
            }
          ]
        }
      ]
    }
  ]
}