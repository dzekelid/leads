---
swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 0
info:
  title: IDX Broker Put Leads Note
  description: Add new note information for a lead.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /leads/lead:
    get:
      summary: Get Leads Lead
      description: |-
        Get information for one or multiple leads.

        Example Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate

        For Data on a specific lead add/LEAD_ID_HERE

        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadGet
      x-api-path-slug: leadslead-get
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
    put:
      summary: Put Leads Lead
      description: |-
        Get information for one or multiple leads.

        Example Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate

        For Data on a specific lead add/LEAD_ID_HERE

        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadPut
      x-api-path-slug: leadslead-put
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: email
      - in: formData
        name: firstName
      - in: formData
        name: lastName
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
  /leads/lead/{leadId}:
    post:
      summary: Post Leads Lead Lead
      description: |-
        Post information for a lead.


        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadByLeadIdPost
      x-api-path-slug: leadsleadleadid-post
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: formData
        name: email
      - in: formData
        name: firstName
      - in: formData
        name: lastName
      - in: path
        name: leadId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
      - Lead
    delete:
      summary: Delete Leads Lead Lead
      description: |-
        Delete Lead

        Example: https://api.idxbroker.com/leads/lead/123
      operationId: LeadsLeadByLeadIdDelete
      x-api-path-slug: leadsleadleadid-delete
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: path
        name: leadId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Lead
      - Lead
  /leads/note/{leadId}:
    put:
      summary: Put Leads Note
      description: Add new note information for a lead.
      operationId: LeadsNoteByLeadIdPut
      x-api-path-slug: leadsnoteleadid-put
      parameters:
      - in: header
        name: accesskey
      - in: header
        name: ancillarykey
      - in: header
        name: apiversion
      - in: header
        name: Content-Type
      - in: path
        name: leadId
      - in: formData
        name: note
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Note
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