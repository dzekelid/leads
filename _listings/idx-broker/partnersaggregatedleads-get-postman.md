{
  "info": {
    "name": "IDX Broker Get Partners Aggregated Leads",
    "_postman_id": "6b59d506-c17d-45e1-ad2a-a2aa950da105",
    "description": "Get a list of all leads.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Partners",
      "item": [
        {
          "id": "a106c250-758f-4a51-8b3a-d3f000d37133",
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
              "id": "b6d44296-4ae0-4cb6-838e-bc638b286863"
            }
          ]
        },
        {
          "id": "ee3db456-667f-436a-a82e-0085e91f65c0",
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
              "id": "1156d8ab-8902-41aa-8ad4-b3d86bccf146"
            }
          ]
        },
        {
          "id": "e90086fd-7845-4e4b-bdba-0b3934c00270",
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
              "id": "da595d45-803b-449c-9e3a-687e39017a65"
            }
          ]
        },
        {
          "id": "9aac67fb-bca1-46f1-8945-742565d94efe",
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
              "id": "ab63bb65-9535-4328-afd3-e6e4e5c6f3b0"
            }
          ]
        },
        {
          "id": "35463c82-59a3-4e72-a35a-aa1f4ad504d1",
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
              "id": "0ba05759-5da1-4f53-9a3b-8d396ed00c2c"
            }
          ]
        },
        {
          "id": "41d0c952-32c3-4c2a-876b-36dd1582f748",
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
              "id": "f19b1a98-d25e-4f8d-8009-48b17d7c652e"
            }
          ]
        },
        {
          "id": "008d46c7-7196-4e51-b3f6-b9867c268da9",
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
              "id": "7969e33b-a0c4-47ff-a085-01f630ac381e"
            }
          ]
        },
        {
          "id": "b91adc55-13ea-4f9c-9d4d-f6947e469d4c",
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
              "id": "919dfaf9-af97-4064-b70b-7f7f4e7f1d6e"
            }
          ]
        },
        {
          "id": "7d6d6967-dd6a-419b-b4ae-df3510949a18",
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
              "id": "47866574-0019-420d-9517-b3443abc3235"
            }
          ]
        }
      ]
    }
  ]
}