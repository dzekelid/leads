---
swagger: "2.0"
x-collection-name: Docsmore
x-complete: 0
info:
  title: Docsmore Unsubscribe Webhook
  description: It is important that you call this event to unsubscribe otherwise it
    will automatically be removed in 10 minutes. If not unsubscribed manually, it
    can also lead to the problem of duplication and create further issues.
  version: "1.0"
host: api.docsmore.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/webhook/unsubscribe/{id}:
    delete:
      summary: Unsubscribe Webhook
      description: It is important that you call this event to unsubscribe otherwise
        it will automatically be removed in 10 minutes. If not unsubscribed manually,
        it can also lead to the problem of duplication and create further issues.
      operationId: ApiWebhookUnsubscribeByIdDelete
      x-api-path-slug: apiwebhookunsubscribeid-delete
      parameters:
      - in: header
        name: Content-Type
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Unsubscribe
      - Webhook
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