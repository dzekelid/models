{
  "info": {
    "name": "Prediction",
    "_postman_id": "60c4e1b3-1eb0-44bb-a318-068d3c3a604f",
    "description": "Lets you access a cloud hosted machine learning service that makes it easy to build smart apps",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "model",
      "item": [
        {
          "id": "1c608f70-9c06-4a62-8635-913bb196a760",
          "name": "prediction.trainedmodels.analyze",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "prediction",
                "v1.6",
                "projects",
                ":project/trainedmodels/:id/analyze"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "project",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get analysis of the model and the data the model was trained on"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "956b3099-bcbc-4166-b725-93b7f52bf5d0"
            }
          ]
        }
      ]
    }
  ]
}