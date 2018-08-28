---
swagger: "2.0"
x-collection-name: AWS API Gateway
x-complete: 0
info:
  title: AWS API Gateway API Restapi Models
  version: 1.0.0
  description: Gets an API&#39;s model collection represented by a Models instance.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapis/uojnr9hd57/models:
    post:
      summary: Model Create
      description: Creates a new Model for this API.
      operationId: modelCreate
      x-api-path-slug: restapisuojnr9hd57models-post
      parameters:
      - in: header
        name: '&quot;contentType&quot;'
        type: string
      - in: header
        name: '&quot;description&quot;'
        type: string
      - in: header
        name: '&quot;name&quot;'
        type: string
      - in: header
        name: Authorization
        type: string
      - in: header
        name: Content-Type
        type: string
      - in: header
        name: Host
        type: string
      - in: header
        name: X-Amz-Date
        type: string
      responses:
        200:
          description: OK
      tags:
      - Models
  /restapis/l9kujxkzq2/models:
    get:
      summary: Restapi Models
      description: Gets an API&#39;s model collection represented by a Models instance.
      operationId: restapiModels
      x-api-path-slug: restapisl9kujxkzq2models-get
      parameters:
      - in: header
        name: Authorization
        type: string
      - in: header
        name: Content-Length
        type: string
      - in: header
        name: Content-Type
        type: string
      - in: header
        name: Host
        type: string
      - in: header
        name: X-Amz-Date
        type: string
      responses:
        200:
          description: OK
      tags:
      - Models
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