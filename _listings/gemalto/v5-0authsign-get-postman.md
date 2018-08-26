{
  "info": {
    "name": "Gemalto IoT Application Enablement Platform API Auth Sign",
    "_postman_id": "9123a965-5350-4297-9dfe-16468e26c209",
    "description": "Auth sign.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "1dcc393d-8229-4fee-a984-63ff6be9728d",
          "name": "getV5.0ToolsTime",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/tools/time",
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
            "description": "Tools time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "787f5b86-c47a-4647-986c-7497f4c8a1cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Auth",
      "item": [
        {
          "id": "b3520d2c-2396-4ebc-8ce3-17e4370b86ab",
          "name": "getV5.0AuthSign",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/auth/sign?authOrg=%7B%7D&authTime=%7B%7D&authUser=%7B%7D",
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
            "description": "Auth sign."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e81ae170-55f6-4400-a68b-adedb5836695"
            }
          ]
        }
      ]
    }
  ]
}