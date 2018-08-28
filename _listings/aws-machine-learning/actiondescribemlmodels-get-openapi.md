---
swagger: "2.0"
x-collection-name: AWS Machine Learning
x-complete: 0
info:
  title: AWS Machine Learning API Describe M L Models
  version: 1.0.0
  description: Returns a list of MLModel that match the search criteria in the request.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateMLModel:
    get:
      summary: Create M L Model
      description: |-
        Creates a new MLModel using the DataSource and the recipe as
                    information sources.
      operationId: createMLModel
      x-api-path-slug: actioncreatemlmodel-get
      parameters:
      - in: query
        name: MLModelId
        description: A user-supplied ID that uniquely identifies the MLModel
        type: string
      - in: query
        name: MLModelName
        description: A user-supplied name or description of the MLModel
        type: string
      - in: query
        name: MLModelType
        description: The category of supervised learning that this MLModel will address
        type: string
      - in: query
        name: Parameters
        description: A list of the training parameters in the MLModel
        type: string
      - in: query
        name: Recipe
        description: The data recipe for creating the MLModel
        type: string
      - in: query
        name: RecipeUri
        description: The Amazon Simple Storage Service (Amazon S3) location and file
          name that contains the MLModel recipe
        type: string
      - in: query
        name: TrainingDataSourceId
        description: The DataSource that points to the training data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Models
  /?Action=DeleteMLModel:
    get:
      summary: Delete M L Model
      description: Assigns the DELETED status to an MLModel, rendering it unusable.
      operationId: deleteMLModel
      x-api-path-slug: actiondeletemlmodel-get
      parameters:
      - in: query
        name: MLModelId
        description: A user-supplied ID that uniquely identifies the MLModel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Models
  /?Action=DescribeMLModels:
    get:
      summary: Describe M L Models
      description: Returns a list of MLModel that match the search criteria in the
        request.
      operationId: describeMLModels
      x-api-path-slug: actiondescribemlmodels-get
      parameters:
      - in: query
        name: EQ
        description: The equal to operator
        type: string
      - in: query
        name: FilterVariable
        description: 'Use one of the following variables to filter a list of MLModel:'
        type: string
      - in: query
        name: GE
        description: The greater than or equal to operator
        type: string
      - in: query
        name: GT
        description: The greater than operator
        type: string
      - in: query
        name: LE
        description: The less than or equal to operator
        type: string
      - in: query
        name: Limit
        description: The number of pages of information to include in the result
        type: string
      - in: query
        name: LT
        description: The less than operator
        type: string
      - in: query
        name: NE
        description: The not equal to operator
        type: string
      - in: query
        name: NextToken
        description: The ID of the page in the paginated results
        type: string
      - in: query
        name: Prefix
        description: A string that is found at the beginning of a variable, such as
          Name or Id
        type: string
      - in: query
        name: SortOrder
        description: A two-value parameter that determines the sequence of the resulting
          list of MLModel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Models
  /?Action=GetMLModel:
    get:
      summary: Get M L Model
      description: Returns an MLModel that includes detailed metadata, data source
        information, and the current status of the MLModel.
      operationId: getMLModel
      x-api-path-slug: actiongetmlmodel-get
      parameters:
      - in: query
        name: MLModelId
        description: The ID assigned to the MLModel at creation
        type: string
      - in: query
        name: Verbose
        description: Specifies whether the GetMLModel operation should return Recipe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Models
  /?Action=UpdateMLModel:
    get:
      summary: Update M L Model
      description: Updates the MLModelName and the ScoreThreshold of an MLModel.
      operationId: updateMLModel
      x-api-path-slug: actionupdatemlmodel-get
      parameters:
      - in: query
        name: MLModelId
        description: The ID assigned to the MLModel during creation
        type: string
      - in: query
        name: MLModelName
        description: A user-supplied name or description of the MLModel
        type: string
      - in: query
        name: ScoreThreshold
        description: The ScoreThreshold used in binary classification MLModel that
          marks the boundary between a positive prediction and a negative prediction
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Models
  /?Action=CreateEvaluation:
    get:
      summary: Create Evaluation
      description: Creates a new Evaluation of an MLModel.
      operationId: createEvaluation
      x-api-path-slug: actioncreateevaluation-get
      parameters:
      - in: query
        name: EvaluationDataSourceId
        description: The ID of the DataSource for the evaluation
        type: string
      - in: query
        name: EvaluationId
        description: A user-supplied ID that uniquely identifies the Evaluation
        type: string
      - in: query
        name: EvaluationName
        description: A user-supplied name or description of the Evaluation
        type: string
      - in: query
        name: MLModelId
        description: The ID of the MLModel to evaluate
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Evaluations
  /?Action=CreateRealtimeEndpoint:
    get:
      summary: Create Realtime Endpoint
      description: Creates a real-time endpoint for the MLModel.
      operationId: createRealtimeEndpoint
      x-api-path-slug: actioncreaterealtimeendpoint-get
      parameters:
      - in: query
        name: MLModelId
        description: The ID assigned to the MLModel during creation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Real Time
  /?Action=DeleteRealtimeEndpoint:
    get:
      summary: Delete Realtime Endpoint
      description: Deletes a real time endpoint of an MLModel.
      operationId: deleteRealtimeEndpoint
      x-api-path-slug: actiondeleterealtimeendpoint-get
      parameters:
      - in: query
        name: MLModelId
        description: The ID assigned to the MLModel during creation
        type: string
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Real Time
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---