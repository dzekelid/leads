---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Assign InboundLead Todos to the predefined neg teams. e.g. Sales Valuers,
    Sales Viewings, Lettings Viewings etc etc
  version: 1.0.0
  description: Assign inboundlead todos to the predefined neg teams. e.g. sales valuers,
    sales viewings, lettings viewings etc etc.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/inboundlead/checkformatchinggroups:
    get:
      summary: Check for Matching groups for the given leads based on contact item
        values i.e. Emails and Phones.
      description: Check for matching groups for the given leads based on contact
        item values i.e. emails and phones..
      operationId: InboundLead_CheckForMatchingGroupsByleadIdBypageSizeBypageNumber
      x-api-path-slug: apiinboundleadcheckformatchinggroups-get
      parameters:
      - in: query
        name: leadId
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - CheckMatching
      - Groupsthe
      - Given
      - Leads
      - Based
      - "On"
      - Contact
      - Item
      - Values
      - I
      - E
      - ""
      - Emails
      - Phones
  /api/inboundlead/outstanding:
    get:
      summary: Gets all leads that are awaiting to be processed
      description: Gets all leads that are awaiting to be processed.
      operationId: InboundLead_GetOutstandingLeads
      x-api-path-slug: apiinboundleadoutstanding-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Leads
      - That
      - Are
      - Awaiting
      - To
      - Be
      - Processed
  /api/todo/canceltask:
    put:
      summary: Cancel the Task. Used for cancelling the Lead Requests.
      description: Cancel the task. used for cancelling the lead requests..
      operationId: DefaultToDo_CancelTaskBycancelTask
      x-api-path-slug: apitodocanceltask-put
      parameters:
      - in: body
        name: cancelTask
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Task
      - ""
      - Usedcancelling
      - Lead
      - Requests
  /api/todo/cancelleadandtask:
    put:
      summary: Cancel the Task. Used for cancelling the Lead Requests.
      description: Cancel the task. used for cancelling the lead requests..
      operationId: DefaultToDo_CancelLeadAndTaskBycancelLead
      x-api-path-slug: apitodocancelleadandtask-put
      parameters:
      - in: body
        name: cancelLead
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Task
      - ""
      - Usedcancelling
      - Lead
      - Requests
  /api/inboundlead/discardthelead:
    put:
      summary: Discard the Lead.
      description: Discard the lead..
      operationId: InboundLead_DiscardTheLeadByleadId
      x-api-path-slug: apiinboundleaddiscardthelead-put
      parameters:
      - in: query
        name: leadId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Discard
      - Lead
  /api/inboundlead/{todoTaskLeadId}/setleadgroup/{groupId}:
    put:
      summary: Endpoint to update group on inbound lead task
      description: Endpoint to update group on inbound lead task.
      operationId: InboundLead_SetLeadGroupBytodoTaskLeadIdBygroupId
      x-api-path-slug: apiinboundleadtodotaskleadidsetleadgroupgroupid-put
      parameters:
      - in: path
        name: groupId
        description: Group Id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: todoTaskLeadId
        description: Todos Task Id
      responses:
        200:
          description: OK
      tags:
      - Endpoint
      - To
      - Update
      - Group
      - "On"
      - Inbound
      - Lead
      - Task
  /api/inboundlead/create:
    post:
      summary: Creates a lead in the system, optinally assigning the lead to a negotiator
      description: Creates a lead in the system, optinally assigning the lead to a
        negotiator.
      operationId: InboundLead_CreateLeadBydataContractByassignToNegId
      x-api-path-slug: apiinboundleadcreate-post
      parameters:
      - in: query
        name: assignToNegId
        description: Negotiator Id to assign lead too
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Lead
      - In
      - System
      - ""
      - Optinally
      - Assigning
      - Lead
      - To
      - Negotiator
  /api/todo/assignleadsforspecifiednegs:
    put:
      summary: Assign InboundLead Todos to all the specified Negs using round-robin
        assignement.
      description: Assign inboundlead todos to all the specified negs using round-robin
        assignement..
      operationId: DefaultToDo_AssignLeadsForSpecifiedNegsByassignPropertyLeadsCommandDataContract
      x-api-path-slug: apitodoassignleadsforspecifiednegs-put
      parameters:
      - in: body
        name: assignPropertyLeadsCommandDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Assign
      - InboundLead
      - Todos
      - To
      - ""
      - Specified
      - Negs
      - Using
      - Round-robin
      - Assignement
  /api/todo/assignleadstoowningnegotiators:
    put:
      summary: Assign InboundLead Todos to the owning Negotiators of the property.
      description: Assign inboundlead todos to the owning negotiators of the property..
      operationId: DefaultToDo_AssignLeadsToOwningNegotiatorsBytoDoId
      x-api-path-slug: apitodoassignleadstoowningnegotiators-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: toDoId
      responses:
        200:
          description: OK
      tags:
      - Assign
      - InboundLead
      - Todos
      - To
      - Owning
      - Negotiators
      - Of
      - Property
  /api/todo/assignleadstopredefinedteams:
    put:
      summary: Assign InboundLead Todos to the predefined neg teams. e.g. Sales Valuers,
        Sales Viewings, Lettings Viewings etc etc
      description: Assign inboundlead todos to the predefined neg teams. e.g. sales
        valuers, sales viewings, lettings viewings etc etc.
      operationId: DefaultToDo_AssignLeadsToPredefinedTeamsBytoDoId
      x-api-path-slug: apitodoassignleadstopredefinedteams-put
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: toDoId
      responses:
        200:
          description: OK
      tags:
      - Assign
      - InboundLead
      - Todos
      - To
      - Predefined
      - Neg
      - Teams
      - ""
      - E
      - G
      - ""
      - Sales
      - Valuers
      - ""
      - Sales
      - Viewings
      - ""
      - Lettings
      - Viewings
      - Etc
      - Etc
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