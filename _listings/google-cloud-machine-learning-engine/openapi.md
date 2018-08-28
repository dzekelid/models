swagger: "2.0"
x-collection-name: Google Cloud Machine Learning Engine
x-complete: 1
info:
  title: Google Cloud Machine Learning Engine
  description: an-api-to-enable-creating-and-using-machine-learning-models-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: ml.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{parent}/models:
    get:
      summary: List Models
      description: |-
        Lists the models in a project.

        Each project can contain multiple models, and each model can have multiple
        versions.
      operationId: ml.projects.models.list
      x-api-path-slug: v1parentmodels-get
      parameters:
      - in: query
        name: pageSize
        description: Optional
      - in: query
        name: pageToken
        description: Optional
      - in: path
        name: parent
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Model
    post:
      summary: Create Models
      description: |-
        Creates a model which will later contain one or more versions.

        You must add at least one version before you can request predictions from
        the model. Add versions by calling
        [projects.models.versions.create](/ml/reference/rest/v1/projects.models.versions/create).
      operationId: ml.projects.models.create
      x-api-path-slug: v1parentmodels-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: parent
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Model