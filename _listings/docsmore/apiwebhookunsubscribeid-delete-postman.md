{
  "info": {
    "name": "Docsmore Unsubscribe Webhook",
    "_postman_id": "738b5952-14f2-4313-98d8-52d496016d56",
    "description": "It is important that you call this event to unsubscribe otherwise it will automatically be removed in 10 minutes. If not unsubscribed manually, it can also lead to the problem of duplication and create further issues.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Unsubscribe",
      "item": [
        {
          "id": "bc72eec7-2dbc-4326-8d3c-466c3b7e8bda",
          "name": "ApiWebhookUnsubscribeByIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.docsmore.com",
              "path": [
                "api/webhook/unsubscribe/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Content-Type",
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
            "description": "It is important that you call this event to unsubscribe otherwise it will automatically be removed in 10 minutes. If not unsubscribed manually, it can also lead to the problem of duplication and create further issues."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b409903-127b-4397-b8de-fe74a2fb3624"
            }
          ]
        }
      ]
    }
  ]
}