swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 1
info:
  title: Global Change Information System API
  description: who-we-are-what-the-gcis-is-and-how-we-use-identifiers-and-semantic-information-to-provide-points-of-reference-and-traceability--examples-and-tutorials-for-using-this-system-as-a-researcher-citizen-scientist-application-developer-or-information-theorist--a-description-of-how-the-information-is-structured-including-the-overlaps-between-relational-and-semantic-representations-of-the-information--complete-documentation-for-the-api-including-methods-for-browsing-and-finding-resources-
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /model:
    get:
      summary: List models.
      description: List the models, 20 per page.
      operationId: list-the-models-20-per-page
      x-api-path-slug: model-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the models
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Models
  /model/{model_identifier}:
    get:
      summary: Get a representation of a model.
      description: Get JSON which represents the structure of a model.
      operationId: get-json-which-represents-the-structure-of-a-model
      x-api-path-slug: modelmodel-identifier-get
      parameters:
      - in: path
        name: model_identifier
        description: model_identifier description
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Model
  /model/{model_identifier}/run:
    get:
      summary: List model runs for a particular model.
      description: List the model runs for a particular model, 20 per page.
      operationId: list-the-model-runs-for-a-particular-model-20-per-page
      x-api-path-slug: modelmodel-identifierrun-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the model runs
      - in: path
        name: model_identifier
        description: model_identifier description
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Model
      - Runsa
      - Particular
      - Model
  /model_run:
    get:
      summary: List model runs.
      description: List the model runs, 20 per page.
      operationId: list-the-model-runs-20-per-page
      x-api-path-slug: model-run-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the model runs
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Model
      - Runs
  /model_run/{model_identifier}/{scenario_identifier}/{range_start}/{range_end}/{spatial_resolution}/{time_resolution}/{sequence}:
    get:
      summary: Get a representation of a model run.
      description: Get JSON which represents the structure of a model run.
      operationId: get-json-which-represents-the-structure-of-a-model-run
      x-api-path-slug: model-runmodel-identifierscenario-identifierrange-startrange-endspatial-resolutiontime-resolutionsequence-get
      parameters:
      - in: path
        name: model_identifier
        description: model_identifier description
      - in: path
        name: range_end
        description: range_end description
      - in: path
        name: range_start
        description: range_start description
      - in: path
        name: scenario_identifier
        description: scenario_identifier description
      - in: path
        name: sequence
        description: sequence description
      - in: path
        name: spatial_resolution
        description: spatial_resolution description
      - in: path
        name: time_resolution
        description: time_resolution description
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Model
      - Run
  /model_run/{model_run_identifier}:
    get:
      summary: Get a representation of a model run.
      description: Get JSON which represents the structure of a model run.
      operationId: get-json-which-represents-the-structure-of-a-model-run
      x-api-path-slug: model-runmodel-run-identifier-get
      parameters:
      - in: path
        name: model_run_identifier
        description: model_run_identifier description
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Model
      - Run
  /scenario/{scenario_identifier}/run:
    get:
      summary: List model runs for a particular scenario.
      description: List the model runs for a particular scenario, 20 per page.
      operationId: list-the-model-runs-for-a-particular-scenario-20-per-page
      x-api-path-slug: scenarioscenario-identifierrun-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the model runs
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: scenario_identifier
        description: scenario_identifier description
      responses:
        200:
          description: OK
      tags:
      - Model
      - Runsa
      - Particular
      - Scenario