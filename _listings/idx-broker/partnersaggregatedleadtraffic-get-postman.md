{
  "info": {
    "name": "IDX Broker Get Partners Aggregated Lead Traffic",
    "_postman_id": "881be661-8708-49db-a42b-60bc055fc9ce",
    "description": "Get a list of all leads traffic history.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Partners",
      "item": [
        {
          "id": "ae15f32c-e133-48aa-98c3-402138fcffaf",
          "name": "PartnersAggregatedagentsGet",
          "request": {
            "url": "http://example.com/partners/aggregatedagents",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all agents for your clients."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb3e2203-8ce5-4b05-b7b7-e72e00b08076"
            }
          ]
        },
        {
          "id": "51235d24-448b-4c5a-be70-1838846eb534",
          "name": "PartnersAggregatedfeaturedGet",
          "request": {
            "url": "http://example.com/partners/aggregatedfeatured",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of featured MLS properties."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8471edd-b6f1-439f-bfa4-93e30addfbea"
            }
          ]
        },
        {
          "id": "9ad897ae-4f1d-43da-909e-512bf5792641",
          "name": "PartnersAggregatedleadsGet",
          "request": {
            "url": "http://example.com/partners/aggregatedleads",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all leads."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d3bf68a-f94e-40b5-8e71-91afc134abe6"
            }
          ]
        },
        {
          "id": "eba60f71-1548-4254-ba8f-62fe3afc5fdd",
          "name": "PartnersAggregatedleadtrafficGet",
          "request": {
            "url": "http://example.com/partners/aggregatedleadtraffic",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all leads traffic history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ca14ef7-783d-4aeb-a253-fa501b7215a9"
            }
          ]
        },
        {
          "id": "90e1241f-f5e6-42e2-b504-f1c719f3e2a1",
          "name": "PartnersAggregatedlistingstatusGet",
          "request": {
            "url": "http://example.com/partners/aggregatedlistingstatus",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This method gives the status for all MLS listings (not supplemental) broken down by client account ID. This includes sold/pending listings with an unknown status which are not usually returned by sold/pending api methods. This is helpful if you need to know when previously gathered featured properties have left the market."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de0eb5b1-a2cc-4b92-9dcd-425765531ca0"
            }
          ]
        },
        {
          "id": "89da1237-4437-45c4-8c51-d94db562b085",
          "name": "PartnersAggregatedpropertiesGet",
          "request": {
            "url": "http://example.com/partners/aggregatedproperties",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all lead saved properties."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ffe2949-7885-455f-a72c-1b23cb31dfcf"
            }
          ]
        },
        {
          "id": "6c8b94b4-85c2-4566-a6cf-ec5a4af8e107",
          "name": "PartnersAggregatedsearchesGet",
          "request": {
            "url": "http://example.com/partners/aggregatedsearches",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of all lead saved searches."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b0de654c-907b-4d4e-aee7-2500c8866a8d"
            }
          ]
        },
        {
          "id": "2b23e69e-182d-4c8e-b61c-7a3e8917e487",
          "name": "PartnersAggregatedsoldpendingGet",
          "request": {
            "url": "http://example.com/partners/aggregatedsoldpending",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of sold/pending MLS properties."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54023937-8a71-494e-97e3-4189a6ff0343"
            }
          ]
        },
        {
          "id": "54bbf08d-5578-4cdb-9fae-a1891ebe82e1",
          "name": "PartnersAggregatedsupplementalGet",
          "request": {
            "url": "http://example.com/partners/aggregatedsupplemental",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of supplemental (non-MLS) properties."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0821a676-88a6-433f-ba60-9dbd60ffcc11"
            }
          ]
        }
      ]
    }
  ]
}