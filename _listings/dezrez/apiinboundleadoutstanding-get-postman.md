{
  "info": {
    "name": "Dezrez Gets all leads that are awaiting to be processed",
    "_postman_id": "69c35bff-3e57-4a21-8d65-e880218b23b0",
    "description": "Gets all leads that are awaiting to be processed.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "CheckMatching",
      "item": [
        {
          "id": "b1836897-5ee9-4af0-b225-f4f879507c4c",
          "name": "InboundLead_CheckForMatchingGroupsByleadIdBypageSizeBypageNumber",
          "request": {
            "url": "http://api.dezrez.com/api/inboundlead/checkformatchinggroups?leadId=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Check for matching groups for the given leads based on contact item values i.e. emails and phones.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9ba41a5b-2090-4518-bc9f-b60a38e23823"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "0d2fb603-5e0e-4897-8e72-3a7966f01a64",
          "name": "InboundLead_GetOutstandingLeads",
          "request": {
            "url": "http://api.dezrez.com/api/inboundlead/outstanding",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
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
            "description": "Gets all leads that are awaiting to be processed."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b4fc7c9a-a3f5-4142-80b4-ab20c2c83e8b"
            }
          ]
        }
      ]
    }
  ]
}