---
name: Google Cloud Prediction
x-slug: google-cloud-prediction
description: Google Cloud Prediction API provides a RESTful API to build Machine Learning
  models. Predictions cloud-based machine learning tools can help analyze your data
  to add various features to your applications, such as customer sentiment analysis,
  spam detection, recommendation systems, and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Models
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/apis.md
specificationVersion: "0.14"
apis:
- name: Prediction - Predict Model
  x-api-slug: projecthostedmodelshostedmodelnamepredict-post
  description: Submit input and request an output against a hosted model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecthostedmodelshostedmodelnamepredict-post-openapi.md
- name: Prediction - Train Model
  x-api-slug: projecttrainedmodels-post
  description: Train a Prediction API model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodels-post-openapi.md
- name: Prediction - List Models
  x-api-slug: projecttrainedmodelslist-get
  description: List available models.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelslist-get-openapi.md
- name: Prediction - Delete Model
  x-api-slug: projecttrainedmodelsid-delete
  description: Delete a trained model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsid-delete-openapi.md
- name: Prediction - Model Status
  x-api-slug: projecttrainedmodelsid-get
  description: Check training status of your model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsid-get-openapi.md
- name: Prediction - Add New Data
  x-api-slug: projecttrainedmodelsid-put
  description: Add new data to a trained model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsid-put-openapi.md
- name: Prediction - Analyze
  x-api-slug: projecttrainedmodelsidanalyze-get
  description: Get analysis of the model and the data the model was trained on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-openapi.md
- name: Prediction - Predict
  x-api-slug: projecttrainedmodelsidpredict-post
  description: Submit model id and request a prediction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsidpredict-post-openapi.md
- name: Prediction - Predict
  x-api-slug: projecttrainedmodelsidpredict-post
  description: Submit model id and request a prediction.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsidpredict-post-openapi.md
- name: Prediction - Analyze
  x-api-slug: projecttrainedmodelsidanalyze-get
  description: Get analysis of the model and the data the model was trained on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-openapi.md
- name: Prediction - Add New Data
  x-api-slug: projecttrainedmodelsid-put
  description: Add new data to a trained model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsid-put-openapi.md
- name: Prediction - Model Status
  x-api-slug: projecttrainedmodelsid-get
  description: Check training status of your model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsid-get-openapi.md
- name: Prediction - Delete Model
  x-api-slug: projecttrainedmodelsid-delete
  description: Delete a trained model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelsid-delete-openapi.md
- name: Prediction - List Models
  x-api-slug: projecttrainedmodelslist-get
  description: List available models.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodelslist-get-openapi.md
- name: Prediction - Train Model
  x-api-slug: projecttrainedmodels-post
  description: Train a Prediction API model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecttrainedmodels-post-openapi.md
- name: Prediction - Predict Model
  x-api-slug: projecthostedmodelshostedmodelnamepredict-post
  description: Submit input and request an output against a hosted model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Machine Learning, Prediction, Google APIs, Stack Network, Predictions, API
    Service Provider, API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/models/master/_listings/google-cloud-prediction/projecthostedmodelshostedmodelnamepredict-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.cloud.natural.language.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.cloud.prediction.stack.network
- type: x-bugs
  url: https://cloud.google.com/prediction/docs/feedback_and_discuss
- type: x-change-log
  url: https://cloud.google.com/prediction/docs/release-notes
- type: x-code
  url: https://cloud.google.com/prediction/docs/libraries
- type: x-website
  url: https://cloud.google.com/prediction/docs/developer-guide
- type: x-documentation
  url: https://cloud.google.com/prediction/docs/
- type: x-faq
  url: https://cloud.google.com/prediction/docs/faq
- type: x-forum
  url: https://cloud.google.com/prediction/docs/general_discussion_forum
- type: x-getting-started
  url: https://cloud.google.com/prediction/docs/quickstart
- type: x-glossary
  url: https://cloud.google.com/prediction/docs/glossary
- type: x-pricing
  url: https://cloud.google.com/prediction/pricing
- type: x-sla
  url: https://cloud.google.com/prediction/sla
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---