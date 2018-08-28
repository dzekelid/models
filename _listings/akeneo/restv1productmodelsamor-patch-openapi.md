---
swagger: "2.0"
x-collection-name: Akeneo
x-complete: 0
info:
  title: Akeneo PIM API product model (2.x only)
  description: Assuming that the given code is the code of an existing product model
  version: 1.0.0
host: example.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/v1/product-models:
    get:
      summary: product models (2.x only)
      description: Product models (2.x only).
      operationId: RestV1ProductModelsGet
      x-api-path-slug: restv1productmodels-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        2:
          description: Successful response
        200:
          description: OK
      tags:
      - Product
      - Models
      - (2
      - X
      - Only)
    patch:
      summary: product models (2.x only)
      description: Product models (2.x only).
      operationId: RestV1ProductModelsPatch
      x-api-path-slug: restv1productmodels-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Product
      - Models
      - (2
      - X
      - Only)
    post:
      summary: product model (2.x only)
      description: Product model (2.x only).
      operationId: RestV1ProductModelsPost
      x-api-path-slug: restv1productmodels-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Product
      - Model
      - (2
      - X
      - Only)
  /rest/v1/product-models/amor:
    get:
      summary: product model (2.x only)
      description: Assuming that the given code is the code of an existing product
        model
      operationId: RestV1ProductModelsAmorGet
      x-api-path-slug: restv1productmodelsamor-get
      responses:
        200:
          description: OK
      tags:
      - Product
      - Model
      - (2
      - X
      - Only)
    patch:
      summary: product model (2.x only)
      description: Assuming that the given code is the code of an existing product
        model
      operationId: RestV1ProductModelsAmorPatch
      x-api-path-slug: restv1productmodelsamor-patch
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Product
      - Model
      - (2
      - X
      - Only)
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