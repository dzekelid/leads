{
  "info": {
    "name": "IDX Broker Get Leads List Components",
    "_postman_id": "473e0279-499a-413c-8291-bfe0d567fb24",
    "description": "This is a simple, access anywhere, method for getting a list of all API components available.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Mls",
      "item": [
        {
          "id": "673e2c91-79a0-4f9b-9a9a-72b217f8e539",
          "name": "MlsListcomponentsGet",
          "request": {
            "url": "http://example.com/mls/listcomponents",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
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
            "description": "This is a simple, access anywhere, method for getting a list of all API components available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cf787b1-d9ff-406c-aacb-b4cbdaac238a"
            }
          ]
        }
      ]
    },
    {
      "name": "Leads",
      "item": [
        {
          "id": "f4b42046-638d-4120-9245-3ddfed1eb8df",
          "name": "LeadsListcomponentsGet",
          "request": {
            "url": "http://example.com/leads/listcomponents",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
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
            "description": "This is a simple, access anywhere, method for getting a list of all API components available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd900774-53a6-450c-a6fa-ffce9ef3f5b3"
            }
          ]
        }
      ]
    }
  ]
}