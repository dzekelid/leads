{
  "info": {
    "name": "IDX Broker Put Leads Search",
    "_postman_id": "236a6f96-a6b6-4217-896e-35b236fcc02d",
    "description": "New search information for a lead.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Leads",
      "item": [
        {
          "id": "ede7f91d-4523-424f-aa9c-d40e765151d1",
          "name": "LeadsLeadGet",
          "request": {
            "url": "http://example.com/leads/lead",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
            "description": "Get information for one or multiple leads.\n\nExample Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate\n\nFor Data on a specific lead add/LEAD_ID_HERE\n\nExample: https://api.idxbroker.com/leads/lead/123"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11925535-2203-4c3a-b360-c12cf922c4d8"
            }
          ]
        },
        {
          "id": "2194c224-bded-47fc-80fa-a67dcd2f0562",
          "name": "LeadsLeadPut",
          "request": {
            "url": "http://example.com/leads/lead",
            "method": "PUT",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Get information for one or multiple leads.\n\nExample Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate\n\nFor Data on a specific lead add/LEAD_ID_HERE\n\nExample: https://api.idxbroker.com/leads/lead/123"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3fa62dae-186e-4dcc-ad1c-c783cced2fc4"
            }
          ]
        },
        {
          "id": "825533b6-f49a-4cc1-a5df-7c2b676a32d1",
          "name": "LeadsLeadByLeadIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/lead/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Post information for a lead.\n\n\nExample: https://api.idxbroker.com/leads/lead/123"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a981ffa8-9560-4a8c-a465-df72f6be990a"
            }
          ]
        },
        {
          "id": "59f9a706-1c2d-4675-a230-78b20d497a59",
          "name": "LeadsLeadByLeadIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/lead/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
            "description": "Delete Lead\n\nExample: https://api.idxbroker.com/leads/lead/123"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba76fd8d-f8a6-4393-b2e2-c29d4fe48199"
            }
          ]
        },
        {
          "id": "a6cfb182-6bdc-4cfc-a031-07da53ac2524",
          "name": "LeadsNoteByLeadIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/note/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Add new note information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30554c6e-11e5-4c38-bc38-e36f6100b565"
            }
          ]
        },
        {
          "id": "1fd4e4e0-ec7f-442d-83ca-bc7c8789320f",
          "name": "LeadsNoteByNoteIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/note/:noteId"
              ],
              "variable": [
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
            "description": "Get note information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3acd718a-c58d-40c0-9ce2-48863749bd53"
            }
          ]
        },
        {
          "id": "b33fdc1b-dcb3-4305-8838-ab95fb392cdf",
          "name": "LeadsNoteByLeadIdAndNoteIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/note/:leadId/:noteId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Post new note information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3662a2ba-448e-48a6-8e3d-85ed334139d6"
            }
          ]
        },
        {
          "id": "964b661b-06de-4521-915c-739d07b3783b",
          "name": "LeadsNoteByLeadIdAndNoteIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/note/:leadId/:noteId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "noteId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "note",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Delete note information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5b9872d-1d26-44de-9fda-069271e54456"
            }
          ]
        },
        {
          "id": "b11e8470-65ff-4475-8cfe-6d05519e9939",
          "name": "LeadsPropertyByLeadIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/property/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
            "description": "Get a property information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "902098cc-b2fe-40c3-bc5c-167e3d866651"
            }
          ]
        },
        {
          "id": "4b059027-d890-4c3d-91f2-f35246aba335",
          "name": "LeadsPropertyByLeadIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/property/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "propertyName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "property[idxID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "property[listingID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Add new property information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f89a7df-62cc-4d7c-8930-e80972ab1e8c"
            }
          ]
        },
        {
          "id": "9950e6a0-aefc-4edf-b841-7cde588e07f4",
          "name": "LeadsPropertyByLeadIdAndPropIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/property/:leadId/:propId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "propId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "propertyName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "property[idxID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "property[listingID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Update a property information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d627efe9-f8c8-4812-a71a-f253a12a02a4"
            }
          ]
        },
        {
          "id": "7fd55f79-c984-4267-bc18-60f8e97c9778",
          "name": "LeadsPropertyByLeadIdAndPropIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/property/:leadId/:propId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "propId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
            "description": "Delete a property information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba88c41f-6c96-4037-8601-e901edc2c3f4"
            }
          ]
        },
        {
          "id": "c1cbcbf9-684b-4000-9387-088552bc7014",
          "name": "LeadsSearchByLeadIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/search/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
            "description": "Get saved search information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f8ed002-4092-4ad4-8904-ff4b98d1e3aa"
            }
          ]
        },
        {
          "id": "775c2dca-c369-443e-8c85-237f4d6692ce",
          "name": "LeadsSearchByLeadIdPut",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/search/:leadId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "ancillarykey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
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
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "searchName",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "search[hp]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "search[idxID]",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "New search information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b877d09-bd8b-4678-a7ff-65cb261e6361"
            }
          ]
        }
      ]
    }
  ]
}