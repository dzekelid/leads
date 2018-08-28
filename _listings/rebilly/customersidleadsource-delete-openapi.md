---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Delete a Lead Source for a customer
  description: Delete a Lead Source that belongs to a certain customer
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customers/{id}/lead-source:
    delete:
      summary: Delete a Lead Source for a customer
      description: Delete a Lead Source that belongs to a certain customer
      operationId: customers.id.lead_source.delete
      x-api-path-slug: customersidleadsource-delete
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcea
      - Customer
    get:
      summary: Retrieve a customer's Lead Source
      description: Retrieve a Lead Source of given customer
      operationId: customers.id.lead_source.get
      x-api-path-slug: customersidleadsource-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Customers
      - Lead
      - Source
    put:
      summary: Create a Lead Source for a customer
      description: Create a Lead Source for a customer
      operationId: customers.id.lead_source.put
      x-api-path-slug: customersidleadsource-put
      parameters:
      - in: body
        name: body
        description: Lead Source resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcea
      - Customer
  /invoices/{id}/lead-source:
    delete:
      summary: Delete a Lead Source for an invoice
      description: Delete a Lead Source that belongs to a certain invoice
      operationId: invoices.id.lead_source.delete
      x-api-path-slug: invoicesidleadsource-delete
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcean
      - Invoice
    get:
      summary: Retrieve an invoice's Lead Source
      description: Retrieve a Lead Source of given invoice
      operationId: invoices.id.lead_source.get
      x-api-path-slug: invoicesidleadsource-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Invoices
      - Lead
      - Source
    put:
      summary: Create a Lead Source for an invoice
      description: Create a Lead Source for an invoice
      operationId: invoices.id.lead_source.put
      x-api-path-slug: invoicesidleadsource-put
      parameters:
      - in: body
        name: body
        description: Lead Source resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcean
      - Invoice
  /subscriptions/{id}/lead-source:
    delete:
      summary: Delete a Lead Source for a Subscription
      description: Delete a Lead Source that belongs to a certain Subscription
      operationId: subscriptions.id.lead_source.delete
      x-api-path-slug: subscriptionsidleadsource-delete
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcea
      - Subscription
    get:
      summary: Retrieve a subscription's Lead Source
      description: Retrieve a Lead Source of given subscription
      operationId: subscriptions.id.lead_source.get
      x-api-path-slug: subscriptionsidleadsource-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Subscriptions
      - Lead
      - Source
    put:
      summary: Create a Lead Source for a Subscription
      description: Create a Lead Source for a Subscription
      operationId: subscriptions.id.lead_source.put
      x-api-path-slug: subscriptionsidleadsource-put
      parameters:
      - in: body
        name: body
        description: Lead Source resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcea
      - Subscription
  /transactions/{id}/lead-source:
    delete:
      summary: Delete a Lead Source for a transaction
      description: Delete a Lead Source that belongs to a certain transaction
      operationId: transactions.id.lead_source.delete
      x-api-path-slug: transactionsidleadsource-delete
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcea
      - Transaction
    get:
      summary: Retrieve a transaction's Lead Source
      description: Retrieve a Lead Source of given transaction
      operationId: transactions.id.lead_source.get
      x-api-path-slug: transactionsidleadsource-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Transactions
      - Lead
      - Source
    put:
      summary: Create a Lead Source for a transaction
      description: Create a Lead Source for a transaction
      operationId: transactions.id.lead_source.put
      x-api-path-slug: transactionsidleadsource-put
      parameters:
      - in: body
        name: body
        description: Lead Source resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Lead
      - Sourcea
      - Transaction
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