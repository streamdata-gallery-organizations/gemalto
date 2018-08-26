{
  "info": {
    "name": "Gemalto IoT Application Enablement Platform API Outbound Command List",
    "_postman_id": "762cd499-9ef5-4e7e-89c9-723dd56ad296",
    "description": "Outbound command list.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "91bc607c-f7e1-4a32-a017-a0f3e661345d",
          "name": "getV5.0ToolsTime",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/tools/time",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Tools time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4af0a995-73ec-4e6a-b65e-8217ed6f2a15"
            }
          ]
        }
      ]
    },
    {
      "name": "Auth",
      "item": [
        {
          "id": "86fe4f98-ce6f-4ce6-9ecf-a097db47c501",
          "name": "getV5.0AuthSign",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/auth/sign?authOrg=%7B%7D&authTime=%7B%7D&authUser=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Auth sign."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8eaf03b6-fb35-4dfe-8081-7921e1fa7d24"
            }
          ]
        }
      ]
    },
    {
      "name": "Device",
      "item": [
        {
          "id": "16eaef24-9d76-4d87-9c5c-29c71975edca",
          "name": "getV5.0DeviceGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/get.json?handle=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c930df51-1b8b-488d-927b-520fa1549fec"
            }
          ]
        },
        {
          "id": "53367b36-7d0d-4f93-b32f-c66bdb805c1b",
          "name": "getV5.0DeviceList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/list.json?deviceTypeId=%7B%7D&deviceTypeKey=%7B%7D&deviceTypeName=%7B%7D&endDateCreated=%7B%7D&groupId=%7B%7D&groupIdNot=%7B%7D&id=%7B%7D&name=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&startDateCreated=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d34811d5-fed1-4faa-a10e-ce8687384898"
            }
          ]
        },
        {
          "id": "480e9ece-e1e6-4102-81ee-86ad799dcffc",
          "name": "getV5.0DeviceCount.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/count.json",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device count."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ea2d3c2-30e4-4d6f-8900-9e0a83ac5acf"
            }
          ]
        },
        {
          "id": "25244854-035b-4c87-92d0-6079071da764",
          "name": "getV5.0DeviceCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/create.json?deviceTypeId=%7B%7D&deviceTypeKey=%7B%7D&groupId=%7B%7D&handle=%7B%7D&iccid=%7B%7D&msisdn=%7B%7D&name=%7B%7D&networkId=%7B%7D&properties=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "637dad32-0be5-4f90-8e64-097da52780c0"
            }
          ]
        },
        {
          "id": "ab18d6c3-56cf-4b9d-8916-00c46880a376",
          "name": "getV5.0DeviceUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/update.json?deviceTypeId=%7B%7D&deviceTypeKey=%7B%7D&handle=%7B%7D&iccid=%7B%7D&id=%7B%7D&msisdn=%7B%7D&name=%7B%7D&networkId=%7B%7D&properties=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d64ef5e1-c8cf-4db6-b8b5-085532ac92da"
            }
          ]
        },
        {
          "id": "ad829881-cb6d-4540-8cc6-6daec4515342",
          "name": "getV5.0DeviceDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/delete.json?handle=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12a75faf-a841-4470-8634-7f9008c2fbdb"
            }
          ]
        },
        {
          "id": "cceea285-97e0-4322-80a1-61307044e934",
          "name": "getV5.0DeviceListbyproperty.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/listByProperty.json?name=%7B%7D&value=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device list by property."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "918f42a1-fc85-40b9-adea-1ca9b91e61b3"
            }
          ]
        },
        {
          "id": "b1ffb52f-0bfb-4d01-8c17-164b82cbfab3",
          "name": "getV5.0DeviceListbypropertyset.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/listByPropertySet.json?name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device list by property set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6329dc4b-e908-4031-bb52-613b70c5756d"
            }
          ]
        },
        {
          "id": "a6054e52-f0cd-4293-9923-58e185dc5198",
          "name": "getV5.0DeviceListbypropertynotset.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/device/listByPropertyNotSet.json?name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device list by property not set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6f04bbd-8811-4bc3-b9a1-2736a0eae74f"
            }
          ]
        },
        {
          "id": "5e03e72e-cfb1-44a5-b776-446dc2de5682",
          "name": "getV5.0DevicestateGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceState/get.json?deviceHandle=%7B%7D&deviceId=%7B%7D&featureId=%7B%7D&fieldNames=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device state get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d56e54e6-abb2-4f48-a487-145ba796a07e"
            }
          ]
        },
        {
          "id": "57bd168d-3170-4b18-8329-427a5cc875f0",
          "name": "getV5.0DevicestateList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceState/list.json?deviceGroupId=%7B%7D&field.<field-name>.<qualifier>=%7B%7D&fieldNames=%7B%7D&isInAlarm=%7B%7D&notReportedSince=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device state list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "20efee76-2a05-40cd-b5f2-3d3442f75d00"
            }
          ]
        },
        {
          "id": "76f7eeb8-c20f-4318-8a66-b66eb4494256",
          "name": "getV5.0DevicefeatureList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceFeature/list.json?deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&deviceTypeId=%7B%7D&deviceTypeKey=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&profileId=%7B%7D&showActive=%7B%7D&showAlarmConditionFields=%7B%7D&showDetails=%7B%7D&showEventReports=%7B%7D&showLastReportPropertyValues=%7B%7D&showLocationReports=%7B%7D&showMetaData=%7B%7D&showNotActive=%7B%7D&showNotVisible=%7B%7D&showStatusReports=%7B%7D&showVirtualCommands=%7B%7D&showVisible=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device feature list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78c56bb8-a3f4-46df-a48b-65900ba00936"
            }
          ]
        },
        {
          "id": "a92c5790-10ea-462d-8df8-f24dd7af53fa",
          "name": "getV5.0DevicefeatureGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceFeature/get.json?deviceHandle=%7B%7D&deviceId=%7B%7D&id=%7B%7D&profileId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device feature get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22c16d79-239e-4a52-b99b-a7fac38e938d"
            }
          ]
        },
        {
          "id": "60107b97-23d6-44ee-a968-1cab850c7ee7",
          "name": "getV5.0DevicegroupCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceGroup/create.json?name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device group create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11d8e2cb-7c31-49b4-a21d-1c76e96b8fce"
            }
          ]
        },
        {
          "id": "81806f4f-ea15-42a7-b8d3-0da2b7bd4874",
          "name": "getV5.0DevicegroupGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceGroup/get.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device group get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "503980c6-538e-4ab6-954a-12bdac90546e"
            }
          ]
        },
        {
          "id": "e1b97771-6960-4111-ab31-36eab2dbbdbf",
          "name": "getV5.0DevicegroupList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceGroup/list.json?id=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device group list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47de5296-04b8-4269-ba36-d3b4b333126b"
            }
          ]
        },
        {
          "id": "76399a59-b281-44b9-a662-8d6b212ea00a",
          "name": "getV5.0DevicegroupUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceGroup/update.json?id=%7B%7D&name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device group update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "849c6bad-623e-4b8d-a00a-bafafa7c0f20"
            }
          ]
        },
        {
          "id": "5bc0a084-2f23-4d45-a5a0-a490c9a7a6d6",
          "name": "getV5.0DevicegroupDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceGroup/delete.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Device group delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc7cdd5a-f944-4468-9076-76c9c8fb033e"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "fa226e30-96f0-4ffc-b029-49caf8f8247c",
          "name": "getV5.0EventreportList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/eventReport/list.json?ack=%7B%7D&atLeastLatest=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&eventType=%7B%7D&fromDate=%7B%7D&latestOnly=%7B%7D&maxAge=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&propertyName=%7B%7D&toDate=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Event report list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "929c6a6f-f260-46e6-9b51-609896e6828f"
            }
          ]
        },
        {
          "id": "5de6fa4b-367e-40b6-8fbf-79efe0201c93",
          "name": "getV5.0EventreportSetack.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/eventReport/setAck.json?ack=%7B%7D&reportIds=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Event report set ack."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff6a1633-d2d3-4917-80d1-a08ce71169f8"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "9d936e64-b655-4dd3-9ba6-c6e377a23918",
          "name": "getV5.0StatusreportList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/statusReport/list.json?atLeastLatest=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&fromDate=%7B%7D&latestOnly=%7B%7D&maxAge=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&propertyName=%7B%7D&toDate=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Status report list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0928dbb0-3250-432a-a822-5bc773a796df"
            }
          ]
        }
      ]
    },
    {
      "name": "Campaign",
      "item": [
        {
          "id": "e9cb20ef-9444-401e-b1b0-374830777052",
          "name": "getV5.0CampaignGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/get.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ecfe7ddd-84a7-4a6a-9d31-a23b0d8dede4"
            }
          ]
        },
        {
          "id": "5ee3e22d-98e9-40e3-a3e1-bb5aa0f0e814",
          "name": "getV5.0CampaignList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/list.json?name=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&status=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff4f2ea9-84db-4556-9916-b1b80285efb6"
            }
          ]
        },
        {
          "id": "f676bbcf-45af-48fe-a04c-2b7f15b98012",
          "name": "getV5.0CampaignCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/create.json?name=%7B%7D&virtualCommandKey=%7B%7D&virtualCommandParams=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "781a8138-5821-40d2-be59-78eb1d39196b"
            }
          ]
        },
        {
          "id": "9640c66f-dbf6-4d25-9f5d-cd7d3654ce57",
          "name": "getV5.0CampaignUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/update.json?id=%7B%7D&name=%7B%7D&virtualCommandKey=%7B%7D&virtualCommandParams=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a072e685-7af7-41bb-bc5a-c86a950c4ed6"
            }
          ]
        },
        {
          "id": "46c93b65-fe6d-4de1-a1e7-089ae3c42ab0",
          "name": "getV5.0CampaignSchedule.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/schedule.json?deliveryMethod=%7B%7D&id=%7B%7D&startTime=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign schedule."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b465f2a5-c1e7-473c-bc70-964ce8bbf304"
            }
          ]
        },
        {
          "id": "450f4659-bd1b-455f-85c5-0fc276b78f92",
          "name": "getV5.0CampaignCancel.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/cancel.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign cancel."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f37a9c01-7ce2-41f1-8f71-9336ad0cb3a2"
            }
          ]
        },
        {
          "id": "f0bf466c-bc22-438b-b045-706d954bcc18",
          "name": "getV5.0CampaignDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaign/delete.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Campaign delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a74f0a7-c02a-4dd6-bee5-a05524725799"
            }
          ]
        }
      ]
    },
    {
      "name": "Sub",
      "item": [
        {
          "id": "4c54f87f-4ff4-44ee-838e-7b64c32e0a08",
          "name": "getV5.0SuborganizationCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/subOrganization/create.json?name=%7B%7D&secret=%7B%7D&userName=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sub organization create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "887ad71a-99dd-4567-a963-11865897a4f3"
            }
          ]
        },
        {
          "id": "e55dc780-ffa1-4475-914a-22a7f17da1e3",
          "name": "getV5.0SuborganizationUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/subOrganization/update.json?key=%7B%7D&name=%7B%7D&secret=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sub organization update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99499f61-51b9-4c3e-aa6c-d82728c26c36"
            }
          ]
        },
        {
          "id": "03e57ede-d93b-439d-92c0-5e04e58fb872",
          "name": "getV5.0SuborganizationShowhierarchy.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/subOrganization/showHierarchy.json?id=%7B%7D&key=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sub organization show hierarchy."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31160cf8-eb53-4f97-b605-8919023ee9bb"
            }
          ]
        },
        {
          "id": "f7f0eb0f-4751-488e-acc9-4d3b97ddcaa3",
          "name": "getV5.0SuborganizationRetire.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/subOrganization/retire.json?id=%7B%7D&key=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Sub organization retire."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30457ed2-7665-40ca-ab88-cb2dec6d0c42"
            }
          ]
        }
      ]
    },
    {
      "name": "Geofence",
      "item": [
        {
          "id": "804e7dc2-edee-41cb-815c-7d627b8a85f6",
          "name": "getV5.0GeofenceCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofence/create.json?groupId=%7B%7D&name=%7B%7D&points=%7B%7D&properties=%7B%7D&radius=%7B%7D&type=%7B%7D&width=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "956ffea6-65ec-4175-a523-cfdaff44c80d"
            }
          ]
        },
        {
          "id": "2acd89ef-2888-47b9-9f39-30bf42369072",
          "name": "getV5.0GeofenceGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofence/get.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e509c81f-693d-4997-949e-e0fc503b350d"
            }
          ]
        },
        {
          "id": "cdf8be8a-e0d5-40c2-9ae5-74f4ab0abd80",
          "name": "getV5.0GeofenceList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofence/list.json?groupId=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "917f5767-842a-409d-8cf1-5255f8a04ce2"
            }
          ]
        },
        {
          "id": "46ccfac7-4a17-41ac-be4d-3f54e8828c10",
          "name": "getV5.0GeofenceUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofence/update.json?id=%7B%7D&points=%7B%7D&properties=%7B%7D&radius=%7B%7D&width=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0e2b901e-d6f8-44a5-a9f5-887cffc83638"
            }
          ]
        },
        {
          "id": "504835c1-8615-43db-93f0-100981871d40",
          "name": "getV5.0GeofenceDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofence/delete.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b5f6388-1d61-40e2-922f-476b6856f9dd"
            }
          ]
        },
        {
          "id": "1ecdf595-8b23-47b1-a5c7-ee76367de4c1",
          "name": "getV5.0GeofencegroupCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceGroup/create.json?name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence group create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4cfe14e-28ec-427e-87b6-73a05b5870c6"
            }
          ]
        },
        {
          "id": "1b3bbdab-4f19-4417-a357-3c508c96853f",
          "name": "getV5.0GeofencegroupGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceGroup/get.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence group get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "009c6b1e-0104-4fae-a605-461e8493266f"
            }
          ]
        },
        {
          "id": "087eead4-c83a-4f64-9f65-1e309fcb420d",
          "name": "getV5.0GeofencegroupList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceGroup/list.json?id=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence group list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c64d8f29-4b4a-48b0-8c27-8f361d4869a2"
            }
          ]
        },
        {
          "id": "c37161fc-4531-4489-958b-40e4791be388",
          "name": "getV5.0GeofencegroupUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceGroup/update.json?id=%7B%7D&name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence group update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d78a66f7-4be7-490a-a472-479a9f8040b1"
            }
          ]
        },
        {
          "id": "0fa4554c-79fa-4858-a05b-482cfb605828",
          "name": "getV5.0GeofencegroupDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceGroup/delete.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence group delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0029890d-99bc-48f8-8d9e-f9ad8052e723"
            }
          ]
        },
        {
          "id": "ca330ad8-5d62-4389-af11-4c4ba31efbc9",
          "name": "getV5.0GeofenceconditionList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceCondition/list.json?deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&geofenceId=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence condition list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81a128a0-ec7a-4ba1-8777-aaf8aa4e7fb8"
            }
          ]
        },
        {
          "id": "b6ab2cce-8d0e-4a31-be04-c9b8cfcd496f",
          "name": "getV5.0GeofenceconditionGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceCondition/get.json?id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence condition get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f723b51-71f9-45e8-8ab4-45b469a18850"
            }
          ]
        },
        {
          "id": "6ed7e313-2d26-4342-864b-e6a5c9ab037c",
          "name": "getV5.0GeofenceconditionCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceCondition/create.json?deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&endTime=%7B%7D&firstOnly=%7B%7D&geofenceId=%7B%7D&groupId=%7B%7D&isInside=%7B%7D&isOutside=%7B%7D&justCrossed=%7B%7D&name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence condition create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f22a0f5d-73f7-4028-a754-56614981970d"
            }
          ]
        },
        {
          "id": "896783c1-c295-4974-9e35-5d63ec8b179b",
          "name": "getV5.0GeofenceconditionUpdate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceCondition/update.json?deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&endTime=%7B%7D&firstOnly=%7B%7D&geofenceId=%7B%7D&groupId=%7B%7D&id=%7B%7D&isInside=%7B%7D&isOutside=%7B%7D&justCrossed=%7B%7D&name=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence condition update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "340cff6f-0169-4828-9416-f58f5a017bbe"
            }
          ]
        },
        {
          "id": "6f45ec5e-08f6-498b-b3cd-a47fcfe11a32",
          "name": "getV5.0GeofenceconditionDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceCondition/delete.json?deviceHandle=%7B%7D&deviceId=%7B%7D&geofenceId=%7B%7D&id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Geofence condition delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdbd3fe1-39fe-494e-9a12-f67df806e7cb"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "088e293a-eb2d-41b4-9000-73f6dadd0863",
          "name": "getV5.0NetworkprovisioningGetdeviceinfo.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/networkProvisioning/getDeviceInfo.json?deviceHandle=%7B%7D&deviceId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Network provisioning get device info."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8ee4451-6a21-45db-ad0d-2acec481d7cb"
            }
          ]
        },
        {
          "id": "a5c1a286-e4d3-438e-82b3-d413b845ff14",
          "name": "getV5.0NetworkprovisioningGetactivationcodes.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/networkProvisioning/getActivationCodes.json",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Network provisioning get activation codes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb74266b-eb06-44d2-ae23-1f81dd31b501"
            }
          ]
        },
        {
          "id": "348e7dbf-b91a-4c9e-bca8-ce2b39f33104",
          "name": "getV5.0NetworkprovisioningActivate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/networkProvisioning/activate.json?activationCode=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Network provisioning activate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53120b43-97a4-4878-86b0-30ad8172b6fd"
            }
          ]
        },
        {
          "id": "199655ab-728e-48f6-95b2-50ab56b43fc1",
          "name": "getV5.0NetworkprovisioningDeactivate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/networkProvisioning/deactivate.json?deviceHandle=%7B%7D&deviceId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Network provisioning deactivate."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0ad3338f-9ec8-431a-91c8-a4dc57e6a4d0"
            }
          ]
        },
        {
          "id": "f05d5018-ad2a-417a-8562-78f0dd7ebcbc",
          "name": "getV5.0NetworkList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/network/list.json?pageNumber=%7B%7D&pageSize=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Network list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da56823b-275d-457d-84cf-180a9618323e"
            }
          ]
        },
        {
          "id": "9607079c-84ab-4e31-aed4-89ed4d1ecc42",
          "name": "getV5.0NetworkGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/network/get.json?id=%7B%7D&key=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Network get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cbf86022-fc79-4261-ae5d-3ae8696b7c89"
            }
          ]
        }
      ]
    },
    {
      "name": "Outbound",
      "item": [
        {
          "id": "d2170022-f337-4ade-875b-11186e5659ca",
          "name": "getV5.0OutboundcommandList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/outboundCommand/list.json?atLeastLatest=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&fromDate=%7B%7D&latestOnly=%7B%7D&maxAge=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&toDate=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Outbound command list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8ff49e9-a03e-4027-85cf-4ef898eeeb68"
            }
          ]
        }
      ]
    }
  ]
}