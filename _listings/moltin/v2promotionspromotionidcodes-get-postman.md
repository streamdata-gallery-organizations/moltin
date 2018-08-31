{
  "info": {
    "name": "Moltin API Get a list of promotion codes",
    "_postman_id": "149efb61-01a0-4e50-a781-b8e1e39d3178",
    "description": "Get a list of promotion codes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Addresses",
      "item": [
        {
          "id": "e93b2dc8-9356-45b9-ad9b-70a3785d12dd",
          "name": "V2CustomersAddressesByCustomerIDAndAddressIDGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.moltin.com",
              "path": [
                "v2/customers/:customerID/addresses/:addressID"
              ],
              "variable": [
                {
                  "id": "addressID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get an address."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "6e5705c6-e2f6-4e15-9706-8b6900719544"
            }
          ]
        },
        {
          "id": "ed97b05c-c816-4bed-bfdd-e9369ca337d7",
          "name": "V2CustomersAddressesByCustomerIDAndAddressIDPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.moltin.com",
              "path": [
                "v2/customers/:customerID/addresses/:addressID"
              ],
              "variable": [
                {
                  "id": "addressID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Update an address."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "4a634e2c-70bc-43b8-ba65-56ab90cfd16d"
            }
          ]
        },
        {
          "id": "a36cbe55-5548-4ee4-8490-23d78ced34be",
          "name": "V2CustomersAddressesByCustomerIDAndAddressIDDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.moltin.com",
              "path": [
                "v2/customers/:customerID/addresses/:addressID"
              ],
              "variable": [
                {
                  "id": "addressID",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "customerID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Delete an address."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "b000a505-1f4d-4a7d-a0d1-05ecc24c963e"
            }
          ]
        }
      ]
    },
    {
      "name": "Promotion",
      "item": [
        {
          "id": "8c1b78e5-1c84-4deb-92f7-c464521a971b",
          "name": "V2PromotionsCodesByPromotionIDGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.moltin.com",
              "path": [
                "v2/promotions/:promotionID/codes"
              ],
              "variable": [
                {
                  "id": "promotionID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
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
            "description": "Get a list of promotion codes."
          },
          "response": [
            {
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "18e77197-9609-40f1-b0e4-8f0a0547bc9f"
            }
          ]
        }
      ]
    }
  ]
}