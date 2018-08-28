---
name: Predix
x-slug: predix
description: Predix (IoT PaaS) helps you develop apps that connect people with industrial
  machines through analytics and data for better business outcomes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
x-kinRank: "7"
x-alexaRank: "264121"
tags: Models
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apis.md
specificationVersion: "0.14"
apis:
- name: Analytics Framework - Get all model entries.
  x-api-slug: apiv2configorchestrationsmodels-get
  description: Returns all model entries as specified by page and sort criteria. By
    default, retrieves all models for tenant. If additional query params specified,
    then results will be filtered
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-get-openapi.md
- name: Analytics Framework - Upload a model.
  x-api-slug: apiv2configorchestrationsmodels-post
  description: Upload a model in a multipart MIME structure. The multipart MIME structure
    must have the modelKey  tagged as 'modelKey',  the modelName  tagged as 'modelName',  the
    modelVersion  tagged as 'modelVersion',  the file contents tagged as 'file',  a
    description (under 1024 characters) tagged as 'description'. (See the documentation
    for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-post-openapi.md
- name: Analytics Framework - Update model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-put
  description: Update a model with attributes of the supplied multipart MIME structure.
    The multipart MIME structure must have the modelKey  tagged as 'modelKey',  the
    modelName  tagged as 'modelName',  the modelVersion  tagged as 'modelVersion',  the
    file contents tagged as 'file',  a description (under 1024 characters) tagged
    as 'description'. (See the documentation for more information regarding these
    files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-put-openapi.md
- name: Analytics Framework - Delete a model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-delete
  description: Delete a model by model id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-delete-openapi.md
- name: Analytics Framework - Download a model file by id.
  x-api-slug: apiv2configorchestrationsmodelsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsidfile-get-openapi.md
- name: Analytics Framework - Download a model file by id.
  x-api-slug: apiv2configorchestrationsmodelsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsidfile-get-openapi.md
- name: Analytics Framework - Delete a model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-delete
  description: Delete a model by model id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-delete-openapi.md
- name: Analytics Framework - Update model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-put
  description: Update a model with attributes of the supplied multipart MIME structure.
    The multipart MIME structure must have the modelKey  tagged as 'modelKey',  the
    modelName  tagged as 'modelName',  the modelVersion  tagged as 'modelVersion',  the
    file contents tagged as 'file',  a description (under 1024 characters) tagged
    as 'description'. (See the documentation for more information regarding these
    files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-put-openapi.md
- name: Analytics Framework - Upload a model.
  x-api-slug: apiv2configorchestrationsmodels-post
  description: Upload a model in a multipart MIME structure. The multipart MIME structure
    must have the modelKey  tagged as 'modelKey',  the modelName  tagged as 'modelName',  the
    modelVersion  tagged as 'modelVersion',  the file contents tagged as 'file',  a
    description (under 1024 characters) tagged as 'description'. (See the documentation
    for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-post-openapi.md
- name: Analytics Framework - Get all model entries.
  x-api-slug: apiv2configorchestrationsmodels-get
  description: Returns all model entries as specified by page and sort criteria. By
    default, retrieves all models for tenant. If additional query params specified,
    then results will be filtered
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-get-openapi.md
- name: Analytics Runtime - Get all model entries.
  x-api-slug: apiv2configorchestrationsmodels-get
  description: Returns all model entries as specified by page and sort criteria. By
    default, retrieves all models for tenant. If additional query params specified,
    then results will be filtered
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-get-openapi.md
- name: Analytics Runtime - Upload a model.
  x-api-slug: apiv2configorchestrationsmodels-post
  description: Upload a model in a multipart MIME structure. The multipart MIME structure
    must have the modelKey  tagged as 'modelKey',  the modelName  tagged as 'modelName',  the
    modelVersion  tagged as 'modelVersion',  the file contents tagged as 'file',  a
    description (under 1024 characters) tagged as 'description'. (See the documentation
    for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-post-openapi.md
- name: Analytics Runtime - Update model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-put
  description: Update a model with attributes of the supplied multipart MIME structure.
    The multipart MIME structure must have the modelKey  tagged as 'modelKey',  the
    modelName  tagged as 'modelName',  the modelVersion  tagged as 'modelVersion',  the
    file contents tagged as 'file',  a description (under 1024 characters) tagged
    as 'description'. (See the documentation for more information regarding these
    files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-put-openapi.md
- name: Analytics Runtime - Delete a model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-delete
  description: Delete a model by model id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-delete-openapi.md
- name: Analytics Runtime - Download a model file by id.
  x-api-slug: apiv2configorchestrationsmodelsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsidfile-get-openapi.md
- name: Analytics Runtime - Download a model file by id.
  x-api-slug: apiv2configorchestrationsmodelsidfile-get
  description: The file is downloaded as an octet-stream.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsidfile-get-openapi.md
- name: Analytics Runtime - Delete a model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-delete
  description: Delete a model by model id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-delete-openapi.md
- name: Analytics Runtime - Update model by id.
  x-api-slug: apiv2configorchestrationsmodelsid-put
  description: Update a model with attributes of the supplied multipart MIME structure.
    The multipart MIME structure must have the modelKey  tagged as 'modelKey',  the
    modelName  tagged as 'modelName',  the modelVersion  tagged as 'modelVersion',  the
    file contents tagged as 'file',  a description (under 1024 characters) tagged
    as 'description'. (See the documentation for more information regarding these
    files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodelsid-put-openapi.md
- name: Analytics Runtime - Upload a model.
  x-api-slug: apiv2configorchestrationsmodels-post
  description: Upload a model in a multipart MIME structure. The multipart MIME structure
    must have the modelKey  tagged as 'modelKey',  the modelName  tagged as 'modelName',  the
    modelVersion  tagged as 'modelVersion',  the file contents tagged as 'file',  a
    description (under 1024 characters) tagged as 'description'. (See the documentation
    for more information regarding these files.)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-post-openapi.md
- name: Analytics Runtime - Get all model entries.
  x-api-slug: apiv2configorchestrationsmodels-get
  description: Returns all model entries as specified by page and sort criteria. By
    default, retrieves all models for tenant. If additional query params specified,
    then results will be filtered
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/predix-vector-logo.png
  humanURL: https://www.predix.io
  baseURL: https:////
  tags: SaaS, Technology, Enterprise, Internet of Things, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/predix/apiv2configorchestrationsmodels-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://predicthq.api.gallery.streamdata.io
- type: x-api-stack
  url: http://predix.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/predix
- type: x-documentation
  url: https://docs.predix.io/en-US/platform
- type: x-twitter
  url: https://twitter.com/Predix
- type: x-website
  url: https://www.predix.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---