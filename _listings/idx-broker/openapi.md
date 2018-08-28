swagger: "2.0"
x-collection-name: IDX Broker
x-complete: 1
info:
  title: IDX API 1.4.0 Test Runner
  description: idx-broker-api-calls-in-version-1-4-0required-environment-variable-url-environment-variable-for-request-headers-environment-variable-partner-key-client-account-with-at-least-one-featured-listingtests-are-in-this-order-as-variables-such-as-listing-id-and-approved-mls-are-passed-to-subsequent-api-calls-
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
  /leads/note/{noteId}:
    get:
      summary: Get Leads Not
      description: Get note information for a lead.
      operationId: LeadsNoteByNoteIdGet
      x-api-path-slug: leadsnotenoteid-get
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
        name: noteId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Not
  /leads/note/{leadId}/{noteId}:
    post:
      summary: Post Leads Note
      description: Post new note information for a lead.
      operationId: LeadsNoteByLeadIdAndNoteIdPost
      x-api-path-slug: leadsnoteleadidnoteid-post
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
      - in: path
        name: noteId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Note
    delete:
      summary: Delete Leads Note
      description: Delete note information for a lead.
      operationId: LeadsNoteByLeadIdAndNoteIdDelete
      x-api-path-slug: leadsnoteleadidnoteid-delete
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
      - in: path
        name: noteId
      - in: header
        name: outputtype
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Note
  /leads/property/{leadId}:
    get:
      summary: Get Leads Property
      description: Get a property information for a lead.
      operationId: LeadsPropertyByLeadIdGet
      x-api-path-slug: leadspropertyleadid-get
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
      - Property
    put:
      summary: Put Leads Property
      description: Add new property information for a lead.
      operationId: LeadsPropertyByLeadIdPut
      x-api-path-slug: leadspropertyleadid-put
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
      - in: formData
        name: propertyName
      - in: formData
        name: property[idxID]
      - in: formData
        name: property[listingID]
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Property
  /leads/property/{leadId}/{propId}:
    post:
      summary: Post Leads Property
      description: Update a property information for a lead.
      operationId: LeadsPropertyByLeadIdAndPropIdPost
      x-api-path-slug: leadspropertyleadidpropid-post
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
      - in: formData
        name: propertyName
      - in: formData
        name: property[idxID]
      - in: formData
        name: property[listingID]
      - in: path
        name: propId
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Property
    delete:
      summary: Delete Leads Property
      description: Delete a property information for a lead.
      operationId: LeadsPropertyByLeadIdAndPropIdDelete
      x-api-path-slug: leadspropertyleadidpropid-delete
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
      - in: path
        name: propId
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Property
  /leads/search/{leadId}:
    get:
      summary: Get Leads Search
      description: Get saved search information for a lead.
      operationId: LeadsSearchByLeadIdGet
      x-api-path-slug: leadssearchleadid-get
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
      - Search
    put:
      summary: Put Leads Search
      description: New search information for a lead.
      operationId: LeadsSearchByLeadIdPut
      x-api-path-slug: leadssearchleadid-put
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
      - in: formData
        name: searchName
      - in: formData
        name: search[hp]
      - in: formData
        name: search[idxID]
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Search
  /leads/search/{leadId}/{searchId}:
    post:
      summary: Post Leads Search
      description: Update search information for a lead.
      operationId: LeadsSearchByLeadIdAndSearchIdPost
      x-api-path-slug: leadssearchleadidsearchid-post
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
      - in: path
        name: searchId
      - in: formData
        name: searchName
      - in: formData
        name: search[hp]
      - in: formData
        name: search[idxID]
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Search
    delete:
      summary: Delete Leads Search
      description: Delete search information for a lead.
      operationId: LeadsSearchByLeadIdAndSearchIdDelete
      x-api-path-slug: leadssearchleadidsearchid-delete
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
      - in: path
        name: searchId
      responses:
        200:
          description: OK
      tags:
      - Leads
      - Search
  /leads/leadtraffic/{leadId}:
    get:
      summary: Get Leads Lead Traffic
      description: Get information on a lead's traffic history.
      operationId: LeadsLeadtrafficByLeadIdGet
      x-api-path-slug: leadsleadtrafficleadid-get
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
      - Traffic
  /leads/listcomponents:
    get:
      summary: Get Leads List Components
      description: This is a simple, access anywhere, method for getting a list of
        all API components available.
      operationId: LeadsListcomponentsGet
      x-api-path-slug: leadslistcomponents-get
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
      - List
      - Components
  /leads/listmethods:
    get:
      summary: Get Leads List Methods
      description: A simple method for listing all available methods in the current
        API component.
      operationId: LeadsListmethodsGet
      x-api-path-slug: leadslistmethods-get
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
      - List
      - Methods
  /partners/aggregatedleads:
    get:
      summary: Get Partners Aggregated Leads
      description: Get a list of all leads.
      operationId: PartnersAggregatedleadsGet
      x-api-path-slug: partnersaggregatedleads-get
      parameters:
      - in: header
        name: accesskey
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
      - Partners
      - Aggregated
      - Leads
  /partners/aggregatedleadtraffic:
    get:
      summary: Get Partners Aggregated Lead Traffic
      description: Get a list of all leads traffic history.
      operationId: PartnersAggregatedleadtrafficGet
      x-api-path-slug: partnersaggregatedleadtraffic-get
      parameters:
      - in: header
        name: accesskey
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
      - Partners
      - Aggregated
      - Lead
      - Traffic