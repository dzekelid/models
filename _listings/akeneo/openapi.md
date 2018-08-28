swagger: "2.0"
x-collection-name: Akeneo
x-complete: 1
info:
  title: Official Akeneo PIM API
  description: the-akeneo-api-brought-to-youfind-out-how-this-postman-collection-works-by-visiting-httpapi-akeneo-com
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