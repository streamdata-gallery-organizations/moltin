{
  "info": {
    "name": "Moltin API Delete an Address",
    "_postman_id": "9c305bdc-d870-4e6c-9942-a44df8e6cac4",
    "description": "Delete an address.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Addresses",
      "item": [
        {
          "id": "5faa9b16-a429-44e9-980b-6bdaa34283be",
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
              "id": "b3ffd0f9-830d-4a5e-a546-468f666a98ac"
            }
          ]
        },
        {
          "id": "33d55c55-cae8-4138-8d27-0ff4971875ec",
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
              "id": "58025954-5869-40a3-8878-1d004619e6fa"
            }
          ]
        },
        {
          "id": "3e71d9f1-0e46-4325-aa38-1c3ab2f8d37c",
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
              "id": "f41891bf-f24a-477f-9750-231b8bf2d65b"
            }
          ]
        }
      ]
    }
  ]
}