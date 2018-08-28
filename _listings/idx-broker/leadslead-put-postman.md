{
  "info": {
    "name": "IDX Broker Put Leads Lead",
    "_postman_id": "3251d983-f886-4598-8de8-0680a509625c",
    "description": "Get information for one or multiple leads.\n\nExample Request: https://api.idxbroker.com/leads/lead?interval=24&startDatetime=2016-01-01+23:59:59&dateType=subscribeDate\n\nFor Data on a specific lead add/LEAD_ID_HERE\n\nExample: https://api.idxbroker.com/leads/lead/123",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Leads",
      "item": [
        {
          "id": "dc395a89-f1a5-4b53-9ecc-8609734b6ba0",
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
              "id": "0752ae6a-fa79-4435-ac99-a81de0f63a2a"
            }
          ]
        },
        {
          "id": "96670ac3-2d1e-46ad-9e63-42579b1c3a1a",
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
              "id": "193ef2bd-556a-478c-9b30-c3f56aaa808b"
            }
          ]
        },
        {
          "id": "87d6d4bc-7c8e-40a9-a57a-d26ad7ac5850",
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
              "id": "74416e38-0277-452a-a8e0-85a28b017391"
            }
          ]
        },
        {
          "id": "05e59727-a987-4453-bfd4-22f21eee8871",
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
              "id": "6cb3bdf3-2043-4788-8fc5-7212c922aecb"
            }
          ]
        },
        {
          "id": "9ec70f4e-69a6-49c0-a728-0bdea0d8a761",
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
              "id": "3bae181c-6290-4fc4-ac47-15cdba093fd5"
            }
          ]
        },
        {
          "id": "aaa6429d-8663-4a0e-9ab7-b7728bf48ffe",
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
              "id": "2aa3a9e9-99aa-4a87-bb0a-304fd87dbeac"
            }
          ]
        },
        {
          "id": "3e9313a6-d9da-4830-b859-2da763409cf9",
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
              "id": "3cb19e8a-c9da-4347-8fdb-07fe9169ac37"
            }
          ]
        },
        {
          "id": "e7c966f8-83d9-4b1f-9fa4-86de8e51cb95",
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
              "id": "4bb5b81b-170d-4718-9f7b-2004072c819c"
            }
          ]
        },
        {
          "id": "95714864-28bf-483d-8d03-bf9c99689df8",
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
              "id": "ab99266b-ef35-4f29-82d8-0451bedc7118"
            }
          ]
        },
        {
          "id": "535c0a10-b6ae-4e30-af0c-ef68d962ce72",
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
              "id": "b2cbf1ab-ad60-489e-9c3b-3856971e797e"
            }
          ]
        },
        {
          "id": "8a9336f2-9015-46c7-92c0-d1bbf066c55e",
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
              "id": "93bcb39d-e02d-44a2-be77-790ff49b591b"
            }
          ]
        },
        {
          "id": "8fe2e8e5-0500-482c-a834-c0cc9456f0d3",
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
              "id": "ce54ceaa-c163-4083-8fee-64fc3d9775da"
            }
          ]
        },
        {
          "id": "fd660557-faa2-477b-bb3b-e7581be42a77",
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
              "id": "357bca68-e472-4aa8-8606-1cccccda14af"
            }
          ]
        },
        {
          "id": "5f4d4099-90b0-4893-a03f-f2df2f6564f4",
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
              "id": "563d971a-31c6-4878-a8b2-5f00a453518c"
            }
          ]
        },
        {
          "id": "356ed6cd-1c9a-4f68-a5c6-abfa549a554d",
          "name": "LeadsSearchByLeadIdAndSearchIdPost",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/search/:leadId/:searchId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "searchId",
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
            "description": "Update search information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b257b22-22da-4ab6-97bb-d9e257654af1"
            }
          ]
        },
        {
          "id": "2cb13234-85ae-407d-af83-79b8de0661ca",
          "name": "LeadsSearchByLeadIdAndSearchIdDelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/search/:leadId/:searchId"
              ],
              "variable": [
                {
                  "id": "leadId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "searchId",
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
            "description": "Delete search information for a lead."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88544683-5b1f-48a5-ad95-fa8208cc3c76"
            }
          ]
        },
        {
          "id": "243f6762-dda6-4c7b-88c8-a914ce4a7c65",
          "name": "LeadsLeadtrafficByLeadIdGet",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "leads/leadtraffic/:leadId"
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
            "description": "Get information on a lead's traffic history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1248b49d-13bb-4650-ac5d-9d910b506e19"
            }
          ]
        },
        {
          "id": "a793d215-5b19-4d1b-90f2-96bd8786cca6",
          "name": "LeadsListcomponentsGet",
          "request": {
            "url": "http://example.com/leads/listcomponents",
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
            "description": "This is a simple, access anywhere, method for getting a list of all API components available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb518b28-2dfb-4f1e-8985-b826c73eabe4"
            }
          ]
        },
        {
          "id": "4b6fcd80-3084-4d13-bdb1-ad3357cb1eb9",
          "name": "LeadsListmethodsGet",
          "request": {
            "url": "http://example.com/leads/listmethods",
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
            "description": "A simple method for listing all available methods in the current API component."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01accb18-e234-498f-9593-95dd85959b16"
            }
          ]
        }
      ]
    },
    {
      "name": "Partners",
      "item": [
        {
          "id": "738e188c-3bfa-4b9b-8b74-9144b9657a7f",
          "name": "PartnersAggregatedleadsGet",
          "request": {
            "url": "http://example.com/partners/aggregatedleads",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
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
            "description": "Get a list of all leads."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98f33cda-88eb-4e30-84c0-0f6dbedfdd6c"
            }
          ]
        },
        {
          "id": "bc269790-0e12-4e48-bb94-271d3734356a",
          "name": "PartnersAggregatedleadtrafficGet",
          "request": {
            "url": "http://example.com/partners/aggregatedleadtraffic",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
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
            "description": "Get a list of all leads traffic history."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41d57cec-8cdd-4e0f-b5d0-876e6c270aa4"
            }
          ]
        }
      ]
    }
  ]
}