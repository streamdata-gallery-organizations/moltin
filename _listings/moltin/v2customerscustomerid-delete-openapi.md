---
swagger: "2.0"
x-collection-name: moltin
x-complete: 0
info:
  title: Moltin API Delete a Customer
  description: Deletes a customer.
  version: 1.0.0
host: api.moltin.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/customers/{customerID}/addresses/{addressID}:
    get:
      summary: Get an Address
      description: Get an address.
      operationId: V2CustomersAddressesByCustomerIDAndAddressIDGet
      x-api-path-slug: v2customerscustomeridaddressesaddressid-get
      parameters:
      - in: header
        name: Accept
      - in: path
        name: addressID
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      responses:
        200:
          description: Successful response
      tags:
      - Addresses
    put:
      summary: Update an Address
      description: Update an address.
      operationId: V2CustomersAddressesByCustomerIDAndAddressIDPut
      x-api-path-slug: v2customerscustomeridaddressesaddressid-put
      parameters:
      - in: header
        name: Accept
      - in: path
        name: addressID
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      responses:
        200:
          description: Successful response
      tags:
      - Addresses
    delete:
      summary: Delete an Address
      description: Delete an address.
      operationId: V2CustomersAddressesByCustomerIDAndAddressIDDelete
      x-api-path-slug: v2customerscustomeridaddressesaddressid-delete
      parameters:
      - in: header
        name: Accept
      - in: path
        name: addressID
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      responses:
        200:
          description: Successful response
      tags:
      - Addresses
  /v2/promotions/{promotionID}/codes:
    get:
      summary: Get a list of promotion codes
      description: Get a list of promotion codes.
      operationId: V2PromotionsCodesByPromotionIDGet
      x-api-path-slug: v2promotionspromotionidcodes-get
      parameters:
      - in: header
        name: Content-Type
      - in: path
        name: promotionID
      responses:
        200:
          description: Successful response
      tags:
      - Promotion
      - Codes
    post:
      summary: Create promotion codes
      description: Create promotion codes.
      operationId: V2PromotionsCodesByPromotionIDPost
      x-api-path-slug: v2promotionspromotionidcodes-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: promotionID
      responses:
        200:
          description: Successful response
      tags:
      - Promotion
      - Codes
  /v2/customers/{customerID}/addresses:
    get:
      summary: Get an list of Addresses
      description: Get an list of addresses.
      operationId: V2CustomersAddressesByCustomerIDGet2
      x-api-path-slug: v2customerscustomeridaddresses-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      responses:
        200:
          description: Successful response
      tags:
      - Addresseses
    post:
      summary: Create an Address
      description: Create an address.
      operationId: V2CustomersAddressesByCustomerIDPost
      x-api-path-slug: v2customerscustomeridaddresses-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
        description: Change default locale
      - in: path
        name: customerID
      - in: header
        name: X-Moltin-Customer-Token
        description: Change from default currency
      responses:
        200:
          description: Successful response
      tags:
      - Addresses
  /v2/integrations/{integrationID}:
    get:
      summary: Get an Integration
      description: Get an integration.
      operationId: V2IntegrationsByIntegrationIDGet
      x-api-path-slug: v2integrationsintegrationid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: integrationID
      responses:
        200:
          description: Successful response
      tags:
      - Integration
    put:
      summary: Update an Integration
      description: Update an integration.
      operationId: V2IntegrationsByIntegrationIDPut
      x-api-path-slug: v2integrationsintegrationid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: integrationID
      responses:
        200:
          description: Successful response
      tags:
      - Integration
    delete:
      summary: Delete an Integration
      description: Delete an integration.
      operationId: V2IntegrationsByIntegrationIDDelete
      x-api-path-slug: v2integrationsintegrationid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: integrationID
      responses:
        200:
          description: Successful response
      tags:
      - Integration
  /v2/brands/{brandID}:
    get:
      summary: Get a Brand
      description: Get a brand.
      operationId: V2BrandsByBrandIDGet
      x-api-path-slug: v2brandsbrandid-get
      parameters:
      - in: header
        name: Accept
      - in: path
        name: brandID
      - in: header
        name: Content-Type
      - in: query
        name: include
      responses:
        200:
          description: Successful response
      tags:
      - Brands
    put:
      summary: Update a Brand
      description: Update a brand.
      operationId: V2BrandsByBrandIDPut
      x-api-path-slug: v2brandsbrandid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: brandID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Brands
    delete:
      summary: Delete a Brand
      description: Delete a brand.
      operationId: V2BrandsByBrandIDDelete
      x-api-path-slug: v2brandsbrandid-delete
      parameters:
      - in: header
        name: Accept
      - in: path
        name: brandID
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Brands
  /v2/flows:
    get:
      summary: Get all flows
      description: Get all flows.
      operationId: V2FlowsGet2
      x-api-path-slug: v2flows-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Flows
    post:
      summary: Create a flow
      description: Create a flow.
      operationId: V2FlowsPost
      x-api-path-slug: v2flows-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: Successful response
      tags:
      - Flow
  /v2/customers/{customerID}:
    get:
      summary: Get a Customer
      description: Get a customer.
      operationId: V2CustomersByCustomerIDGet
      x-api-path-slug: v2customerscustomerid-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      - in: header
        name: X-Moltin-Customer-Token
        description: A customer token
      responses:
        200:
          description: Successful response
      tags:
      - Customer
    put:
      summary: Update a Customer
      description: Update a customer.
      operationId: V2CustomersByCustomerIDPut
      x-api-path-slug: v2customerscustomerid-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      - in: header
        name: X-Moltin-Customer-Token
      responses:
        200:
          description: Successful response
      tags:
      - Customer
    delete:
      summary: Delete a Customer
      description: Deletes a customer.
      operationId: V2CustomersByCustomerIDDelete
      x-api-path-slug: v2customerscustomerid-delete
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: path
        name: customerID
      - in: header
        name: X-Moltin-Customer-Token
      responses:
        200:
          description: Successful response
      tags:
      - Customer
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