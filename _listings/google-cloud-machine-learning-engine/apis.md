---
name: Google Cloud Machine Learning Engine
x-slug: google-cloud-machine-learning-engine
description: Google Cloud Machine Learning Engine is a managed service that enables
  you to easily build machine learning models, that work on any type of data, of any
  size. Create your model with the powerful TensorFlow framework that powers many
  Google products, from Google Photos to Google Cloud Speech. Build models of any
  size with our managed scalable infrastructure. Your trained model is immediately
  available for use with our global prediction platform that can support thousands
  of users and TBs of data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Models
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-machine-learning-engine/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Machine Learning Engine - List Models
  x-api-slug: v1parentmodels-get
  description: |-
    Lists the models in a project.

    Each project can contain multiple models, and each model can have multiple
    versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-machine-learning-engine/v1parentmodels-get-openapi.md
- name: Google Cloud Machine Learning Engine - Create Models
  x-api-slug: v1parentmodels-post
  description: |-
    Creates a model which will later contain one or more versions.

    You must add at least one version before you can request predictions from
    the model. Add versions by calling
    [projects.models.versions.create](/ml/reference/rest/v1/projects.models.versions/create).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-machine-learning-engine/v1parentmodels-post-openapi.md
- name: Google Cloud Machine Learning Engine - Create Models
  x-api-slug: v1parentmodels-post
  description: |-
    Creates a model which will later contain one or more versions.

    You must add at least one version before you can request predictions from
    the model. Add versions by calling
    [projects.models.versions.create](/ml/reference/rest/v1/projects.models.versions/create).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-machine-learning-engine/v1parentmodels-post-openapi.md
- name: Google Cloud Machine Learning Engine - List Models
  x-api-slug: v1parentmodels-get
  description: |-
    Lists the models in a project.

    Each project can contain multiple models, and each model can have multiple
    versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-cloud-ml.png
  humanURL: https://cloud.google.com/ml-engine/
  baseURL: ://ml.googleapis.com//
  tags: Machine Learning, Google APIs, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-machine-learning-engine/v1parentmodels-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.key.management.service.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.machine.learning.engine.stack.network
- type: x-change-log
  url: https://cloud.google.com/ml-engine/docs/resources/release-notes
- type: x-command-line-interface
  url: https://cloud.google.com/sdk/gcloud/reference/ml-engine/
- type: x-concepts
  url: https://cloud.google.com/ml-engine/docs/concepts/
- type: x-documentation
  url: https://cloud.google.com/ml-engine/docs/
- type: x-getting-started
  url: https://cloud.google.com/ml-engine/docs/quickstarts/
- type: x-pricing
  url: https://cloud.google.com/ml-engine/pricing
- type: x-rate-limits
  url: https://cloud.google.com/ml-engine/quotas
- type: x-service-level-agreements
  url: https://cloud.google.com/ml-engine/sla
- type: x-support
  url: https://cloud.google.com/ml-engine/docs/resources/support
- type: x-terms-of-service
  url: https://cloud.google.com/terms/
- type: x-tutorials
  url: https://cloud.google.com/ml-engine/docs/tutorials/
- type: x-versioning
  url: https://cloud.google.com/ml-engine/docs/concepts/versioning
- type: x-website
  url: https://cloud.google.com/ml-engine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---