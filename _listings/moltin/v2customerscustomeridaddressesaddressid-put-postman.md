{
  "info": {
    "name": "Moltin API Update an Address",
    "_postman_id": "47b85610-85fd-4be9-8363-7f06b65326e3",
    "description": "Update an address.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Addresses",
      "item": [
        {
          "id": "7e33a071-e0a5-42bb-a76f-9cf24e4c88ab",
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
              "id": "7c065779-169e-4091-9191-8082931551b4"
            }
          ]
        },
        {
          "id": "7c9e544b-6255-44d0-b5e4-dc1e5b1f104d",
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
              "id": "ef5e0142-895d-4711-a879-08140073b0b2"
            }
          ]
        }
      ]
    }
  ]
}