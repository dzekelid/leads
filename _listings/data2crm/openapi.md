---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 1
info:
  title: Data2CRM.API
  description: pmake-use-of-our-indepth-documentation-to-get-more-information-about-the-various-functions-of-the-service--those-willing-to-explore-the-mechanics-of-data2crm-api-can-test-it-in-live-regime-using-the-short-code-samples-ppselect-crm-span-iddocsselectcrm-stylefontweight-boldloading----please-waitspanpphere-are-the-api-access-keysbrbxapi2crmuserkeyb-span-iddocsuserkeye2a6379ab878ae7e58119d4ec842bf9c926e05b5spanbrbxapi2crmcrmkeyb-span-iddocscrmkey7ae5b17008fb414d84981191cf3b66a476ef8befspanpp-iddocscrmaccessthe-crm-access-details-arebrburlb-a-iddocscrmurl-hrefhttpslogin-salesforce-com-target-blankhttpslogin-salesforce-comabrbemail--usernameb-span-iddocscrmusernamedevelopers-data2crm-api1magneticone-comspanbrbpasswordb-span-iddocscrmpassworddata2crmapi123spanp
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
    get:
      summary: GET for Lead
      description: Return lead information
      operationId: getLeadEntity
      x-api-path-slug: leadlead-id-get
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
    put:
      summary: PUT for Lead
      description: Update lead information
      operationId: updateLeadEntity
      x-api-path-slug: leadlead-id-put
      parameters:
      - in: body
        name: body
        description: Update lead information
        schema:
          $ref: '#/definitions/holder'
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
---