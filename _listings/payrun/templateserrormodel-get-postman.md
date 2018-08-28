{
  "info": {
    "name": "Pay Run.IO Gets the error model template",
    "_postman_id": "d2083d7c-3464-460c-891f-7750ff7cbeaa",
    "description": "Return the error model data object template",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Error",
      "item": [
        {
          "id": "2d3277fb-7763-4848-aff7-b5183eca9d4d",
          "name": "GetErrorModelTemplate",
          "request": {
            "url": "http://api.test.payrun.io/Templates/errormodel",
            "method": "GET",
            "header": [
              {
                "key": "Api-Version",
                "value": "{}",
                "description": "The version of the api to target",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "{}",
                "description": "The OAuth 1 authorization header",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Return the error model data object template"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1aef0203-60d5-4b46-8698-42dabbb29cd2"
            }
          ]
        }
      ]
    }
  ]
}