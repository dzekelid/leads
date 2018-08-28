---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM DELETE for Lead
  description: Delete lead information
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /lead:
    get:
      summary: GET for Lead
      description: Returns all leads from the system
      operationId: getLeadCollection
      x-api-path-slug: lead-get
      parameters:
      - in: query
        name: filter
        description: Filter
      - in: query
        name: limit
        description: 'Amount of results (default: 25)'
      - in: query
        name: offset
        description: 'Start from record (default: 0)'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-DATA-ENABLE
        description: Data Enable
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Leads
    post:
      summary: POST for Lead
      description: Add lead into the system
      operationId: createLeadEntity
      x-api-path-slug: lead-post
      parameters:
      - in: body
        name: body
        description: Add lead into the system
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Leads
  /lead/count:
    get:
      summary: COUNT for Lead
      description: Count all leads from the system
      operationId: getLeadCountCollection
      x-api-path-slug: leadcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Count
  /lead/describe:
    get:
      summary: DESCRIBE for Lead
      description: Returns describe for leads
      operationId: getLeadDescribe
      x-api-path-slug: leaddescribe-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Describe
  /lead/{lead_id}:
    delete:
      summary: DELETE for Lead
      description: Delete lead information
      operationId: deleteLeadEntity
      x-api-path-slug: leadlead-id-delete
      parameters:
      - in: path
        name: lead_id
        description: Lead Identifier
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Leads
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