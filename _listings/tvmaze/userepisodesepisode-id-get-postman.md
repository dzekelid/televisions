{
  "info": {
    "name": "TVmaze user Get User Episodes",
    "_postman_id": "fcb368e1-c657-4d90-8a24-b9611a6ffb74",
    "description": "Get user episodes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Television",
      "item": [
        {
          "id": "6d486ee0-d9f5-4545-a11b-b79f09b35bd7",
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
              "id": "eff71e3e-90ab-47df-ad0b-1a19d5b4df09"
            }
          ]
        },
        {
          "id": "c3a29d23-b607-4768-8403-73b1a0302590",
          "name": "getUserEpisodesEpisode",
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
              "id": "0aa405f8-b435-4e06-8e5d-644a10774477"
            }
          ]
        },
        {
          "id": "f2d99eb8-28c8-46c3-987d-536b2f3997db",
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
              "id": "c4941841-d636-4bab-8502-229afa34d0da"
            }
          ]
        }
      ]
    }
  ]
}