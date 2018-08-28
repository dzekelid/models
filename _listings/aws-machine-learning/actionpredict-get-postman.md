{
  "info": {
    "name": "AWS Machine Learning API Predict",
    "_postman_id": "3e3c5119-ccd1-4cf8-837b-8999ed45630c",
    "description": "Generates a prediction for the observation using the specified ML Model.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tags",
      "item": [
        {
          "id": "9002315b-1a67-4f1c-973f-a4457c7d752f",
          "name": "addTags",
          "request": {
            "url": "http://example.com/api/?Action=AddTags?ResourceId=ResourceId&ResourceType=ResourceType&Tags=Tags",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds one or more tags to an object, up to a limit of 10."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "190267c6-5467-45d8-add0-5afcae808587"
            }
          ]
        },
        {
          "id": "0fc65c68-c53f-4a82-a578-177829c35be7",
          "name": "deleteTags",
          "request": {
            "url": "http://example.com/api/?Action=DeleteTags?ResourceId=ResourceId&ResourceType=ResourceType&TagKeys=TagKeys",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified tags associated with an ML object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2809925-1ed7-408e-8881-8f55aa4ead11"
            }
          ]
        }
      ]
    },
    {
      "name": "Batches",
      "item": [
        {
          "id": "d5f86f33-a31b-4c51-97f4-5adb80948e55",
          "name": "createBatchPrediction",
          "request": {
            "url": "http://example.com/api/?Action=CreateBatchPrediction?BatchPredictionDataSourceId=BatchPredictionDataSourceId&BatchPredictionId=BatchPredictionId&BatchPredictionName=BatchPredictionName&MLModelId=MLModelId&OutputUri=OutputUri",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates predictions for a group of observations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "475f245e-f371-4dc1-a42c-9d0681d4fc79"
            }
          ]
        },
        {
          "id": "68612d46-0cb3-4534-b115-ccfa749dd430",
          "name": "deleteBatchPrediction",
          "request": {
            "url": "http://example.com/api/?Action=DeleteBatchPrediction?BatchPredictionId=BatchPredictionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns the DELETED status to a BatchPrediction, rendering it unusable."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9566aa4c-814c-4f55-9eee-59a5b764b4fc"
            }
          ]
        },
        {
          "id": "bbcf8bb5-d03b-40b2-94a0-ec1d4bc3a8ee",
          "name": "describeBatchPredictions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeBatchPredictions?EQ=EQ&FilterVariable=FilterVariable&GE=GE&GT=GT&LE=LE&Limit=Limit&LT=LT&NE=NE&NextToken=NextToken&Prefix=Prefix&SortOrder=SortOrder",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of BatchPrediction operations that match the search criteria in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd1ccad3-ef10-4f54-aa46-821c02ae1ef9"
            }
          ]
        },
        {
          "id": "a3d24b31-bc05-4011-be2a-259368f367fa",
          "name": "getBatchPrediction",
          "request": {
            "url": "http://example.com/api/?Action=GetBatchPrediction?BatchPredictionId=BatchPredictionId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a BatchPrediction that includes detailed metadata, status, and data file information for a\n            Batch Prediction request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b6265e4-153b-43f9-8e28-d7165f683ddb"
            }
          ]
        }
      ]
    },
    {
      "name": "Data Sources",
      "item": [
        {
          "id": "565d53a1-0bb1-4839-846a-0f368b45786e",
          "name": "createDataSourceFromRDS",
          "request": {
            "url": "http://example.com/api/?Action=CreateDataSourceFromRDS?ComputeStatistics=ComputeStatistics&DataSourceId=DataSourceId&DataSourceName=DataSourceName&RDSData=RDSData&RoleARN=RoleARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a DataSource object from an."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34fd1951-a2ff-4b3a-af64-00d6d326ab71"
            }
          ]
        },
        {
          "id": "c8c0a3ed-5cba-4888-978f-5e511b84dfe9",
          "name": "createDataSourceFromRedshift",
          "request": {
            "url": "http://example.com/api/?Action=CreateDataSourceFromRedshift?ComputeStatistics=ComputeStatistics&DataSourceId=DataSourceId&DataSourceName=DataSourceName&DataSpec=DataSpec&RoleARN=RoleARN",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a DataSource from a database hosted on an Amazon Redshift cluster."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e6171d7-44f4-44a9-8335-a03d5d77f16f"
            }
          ]
        },
        {
          "id": "90670409-5c0c-4ec7-b198-22bb33434618",
          "name": "createDataSourceFromS3",
          "request": {
            "url": "http://example.com/api/?Action=CreateDataSourceFromS3?ComputeStatistics=ComputeStatistics&DataSourceId=DataSourceId&DataSourceName=DataSourceName&DataSpec=DataSpec",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a DataSource object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83514d50-7081-491c-a4a4-af1be6183f3f"
            }
          ]
        },
        {
          "id": "c75acad0-3755-4fea-b55b-e1ee1f79884f",
          "name": "deleteDataSource",
          "request": {
            "url": "http://example.com/api/?Action=DeleteDataSource?DataSourceId=DataSourceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns the DELETED status to a DataSource, rendering it unusable."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29a92059-2878-4624-837c-a111588ffdc7"
            }
          ]
        },
        {
          "id": "31f17e66-e41f-4ee3-bae2-a450918ceb1b",
          "name": "describeDataSources",
          "request": {
            "url": "http://example.com/api/?Action=DescribeDataSources?EQ=EQ&FilterVariable=FilterVariable&GE=GE&GT=GT&LE=LE&Limit=Limit&LT=LT&NE=NE&NextToken=NextToken&Prefix=Prefix&SortOrder=SortOrder",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of DataSource that match the search criteria in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "394e1b84-9502-4d63-aa2f-f7e1bf11fdd4"
            }
          ]
        },
        {
          "id": "72a10b33-68ca-41b2-81b2-36e2ee9935fd",
          "name": "getDataSource",
          "request": {
            "url": "http://example.com/api/?Action=GetDataSource?DataSourceId=DataSourceId&Verbose=Verbose",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a DataSource that includes metadata and data file information, as well as the current status of the DataSource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84ed1b65-d507-4f2d-818c-c2d79577ad32"
            }
          ]
        }
      ]
    },
    {
      "name": "Evaluations",
      "item": [
        {
          "id": "3be280ea-5b53-43f9-8cd2-32df12706837",
          "name": "createEvaluation",
          "request": {
            "url": "http://example.com/api/?Action=CreateEvaluation?EvaluationDataSourceId=EvaluationDataSourceId&EvaluationId=EvaluationId&EvaluationName=EvaluationName&MLModelId=MLModelId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new Evaluation of an MLModel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45bacd46-7afd-487f-88b2-ce2f6a3a223a"
            }
          ]
        },
        {
          "id": "619a4c84-4b1f-4539-abd8-e14587e6e7fa",
          "name": "deleteEvaluation",
          "request": {
            "url": "http://example.com/api/?Action=DeleteEvaluation?EvaluationId=EvaluationId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns the DELETED status to an Evaluation, rendering it unusable."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e6ce1e0-44df-4a4e-bd8c-f908df355ffe"
            }
          ]
        },
        {
          "id": "54038bf2-1409-481b-b83a-64ee7302435d",
          "name": "describeEvaluations",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEvaluations?EQ=EQ&FilterVariable=FilterVariable&GE=GE&GT=GT&LE=LE&Limit=Limit&LT=LT&NE=NE&NextToken=NextToken&Prefix=Prefix&SortOrder=SortOrder",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of DescribeEvaluations that match the search criteria in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93a17935-fe8a-4801-ab5a-e9dffb63ba74"
            }
          ]
        },
        {
          "id": "be2e7511-315d-427c-8aa4-78825f8dc49d",
          "name": "getEvaluation",
          "request": {
            "url": "http://example.com/api/?Action=GetEvaluation?EvaluationId=EvaluationId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an Evaluation that includes metadata as well as the current status of the Evaluation."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d19ab617-c467-457e-a7a8-01e93c659b95"
            }
          ]
        }
      ]
    },
    {
      "name": "Models",
      "item": [
        {
          "id": "bd835a4a-f224-4f19-b310-f3fa9880a95a",
          "name": "createMLModel",
          "request": {
            "url": "http://example.com/api/?Action=CreateMLModel?MLModelId=MLModelId&MLModelName=MLModelName&MLModelType=MLModelType&Parameters=Parameters&Recipe=Recipe&RecipeUri=RecipeUri&TrainingDataSourceId=TrainingDataSourceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new MLModel using the DataSource and the recipe as\n            information sources."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6797cd53-247f-4008-be22-c07f411c8326"
            }
          ]
        },
        {
          "id": "b2773ba7-edf5-4265-85e8-7092e8d69311",
          "name": "deleteMLModel",
          "request": {
            "url": "http://example.com/api/?Action=DeleteMLModel?MLModelId=MLModelId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Assigns the DELETED status to an MLModel, rendering it unusable."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4d7208e6-226f-4437-b6e5-04514505a62e"
            }
          ]
        },
        {
          "id": "1d16d0c6-88c2-490d-9d9f-5ecb914da54c",
          "name": "describeMLModels",
          "request": {
            "url": "http://example.com/api/?Action=DescribeMLModels?EQ=EQ&FilterVariable=FilterVariable&GE=GE&GT=GT&LE=LE&Limit=Limit&LT=LT&NE=NE&NextToken=NextToken&Prefix=Prefix&SortOrder=SortOrder",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of MLModel that match the search criteria in the request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08ea193a-0ed3-4fc9-b7b8-85df5e2d7df2"
            }
          ]
        },
        {
          "id": "12641a64-8308-4902-ad9e-9ad30c47cc39",
          "name": "getMLModel",
          "request": {
            "url": "http://example.com/api/?Action=GetMLModel?MLModelId=MLModelId&Verbose=Verbose",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an MLModel that includes detailed metadata, data source information, and the current status of the MLModel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de90a913-13a0-42c8-8f9a-434f56b4f965"
            }
          ]
        }
      ]
    },
    {
      "name": "Real Time",
      "item": [
        {
          "id": "0ec43f81-7a9c-40c2-b1e5-a097603bd9bd",
          "name": "createRealtimeEndpoint",
          "request": {
            "url": "http://example.com/api/?Action=CreateRealtimeEndpoint?MLModelId=MLModelId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a real-time endpoint for the MLModel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66808107-9959-4258-97d2-257e315d54c9"
            }
          ]
        },
        {
          "id": "cfdfe1b9-cc72-4039-a645-52852e025516",
          "name": "deleteRealtimeEndpoint",
          "request": {
            "url": "http://example.com/api/?Action=DeleteRealtimeEndpoint?MLModelId=MLModelId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a real time endpoint of an MLModel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99e80b87-6abd-413e-83ba-97e1dad8bd03"
            }
          ]
        },
        {
          "id": "c12ed2a4-5634-41ab-97fe-fba7eefe7241",
          "name": "describeTags",
          "request": {
            "url": "http://example.com/api/?Action=DescribeTags?ResourceId=ResourceId&ResourceType=ResourceType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes one or more of the tags for your Amazon ML object."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc118c87-4da5-4660-bae1-b637585ee621"
            }
          ]
        }
      ]
    },
    {
      "name": "Predict",
      "item": [
        {
          "id": "beb2f210-d3cb-443c-a00d-0939552be60f",
          "name": "predict",
          "request": {
            "url": "http://example.com/api/?Action=Predict?MLModelId=MLModelId&PredictEndpoint=PredictEndpoint&Record=Record",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates a prediction for the observation using the specified ML Model."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a0366067-b500-492c-b872-eb611114d6b0"
            }
          ]
        }
      ]
    }
  ]
}