{
  "info": {
    "name": "Moltin API Get an Address",
    "_postman_id": "3f00d552-9c8e-4b1f-b96a-0254262ca5e7",
    "description": "Get an address.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Addresses",
      "item": [
        {
          "id": "9b36f4e4-c5fe-4727-a85b-92cefbe8a4d4",
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
              "id": "82b76754-57b8-4be7-b50a-ff5d6fa6ea54"
            }
          ]
        }
      ]
    }
  ]
}