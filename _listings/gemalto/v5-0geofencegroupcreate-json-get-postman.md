{
  "info": {
    "name": "Gemalto IoT Application Enablement Platform API Geofence Group Create",
    "_postman_id": "b0a6d001-eab9-4ef0-85d7-3850e1551b29",
    "description": "Geofence group create.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "c552dc45-6744-4ce9-9935-02956e23b2a2",
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
              "id": "5afc5002-1e00-4158-ad10-1aa7e45cd59f"
            }
          ]
        }
      ]
    },
    {
      "name": "Auth",
      "item": [
        {
          "id": "72ba2d68-23e5-4842-8a41-330c9d346244",
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
              "id": "68d9e828-5501-4ec9-9743-d977562b5b2f"
            }
          ]
        }
      ]
    },
    {
      "name": "Device",
      "item": [
        {
          "id": "0fc6faa9-8bf8-45c2-a2e8-bf50d1072f22",
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
              "id": "7046eada-f3cf-413c-9e6b-f2192fbbaded"
            }
          ]
        },
        {
          "id": "02a71cf6-3d70-4873-adb1-32a2fde6ef29",
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
              "id": "80db9195-8275-4291-92a9-14e98dccf87e"
            }
          ]
        },
        {
          "id": "80a72465-f6aa-441d-85f4-e18968cfb07a",
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
              "id": "7c6dd903-2b3a-4c30-a43e-d2b41823fdf0"
            }
          ]
        },
        {
          "id": "d7b22583-e718-495e-b20b-dde6c1f6be09",
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
              "id": "9613b55a-b06f-43f1-8316-cd9a7914f7d3"
            }
          ]
        },
        {
          "id": "211434ac-7095-417d-b424-e01efc14ae0d",
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
              "id": "4e4fcbbe-ca43-48af-936a-d4efd3adb78e"
            }
          ]
        },
        {
          "id": "eda3c269-f368-488c-912f-440f85611f52",
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
              "id": "2a89b5df-e912-4449-83b5-18e6d41f1766"
            }
          ]
        },
        {
          "id": "eaf3e313-81df-42ba-bcae-949660702502",
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
              "id": "840cfd2a-e5c4-4f8f-b60b-ca34ec80841e"
            }
          ]
        },
        {
          "id": "91d4b6bb-40bc-4d12-8f6a-e46476e57f3a",
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
              "id": "df194fda-6a88-44f9-8bcd-d3098ea3a03f"
            }
          ]
        },
        {
          "id": "96ae4698-bc51-4a98-91a6-eb3f22b02085",
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
              "id": "48566918-766c-443d-b477-6ac4cbd4685e"
            }
          ]
        },
        {
          "id": "bb32d96e-f089-4c25-a6d0-ba9f4cd572ff",
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
              "id": "b12c854d-2ce4-47eb-95c0-ca5a46f87951"
            }
          ]
        },
        {
          "id": "a1760df6-2d96-4212-833c-f15e42f9c63c",
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
              "id": "506c722f-af0a-40a9-abcb-6c150448f540"
            }
          ]
        },
        {
          "id": "9b897782-1797-411a-a4fb-82534bda4d8f",
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
              "id": "80009dc1-40ef-4540-a9ed-36a4dfc58c6f"
            }
          ]
        },
        {
          "id": "d3376ee6-f1be-4a27-b356-b2a2939b1ba1",
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
              "id": "f66c3dad-1dc2-45f0-8446-5671a37ddfa6"
            }
          ]
        },
        {
          "id": "94b9712a-ce81-4cc0-b8b0-8d41875d8350",
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
              "id": "cf2c41db-32d4-4b59-baaa-1b837a41a9ac"
            }
          ]
        },
        {
          "id": "e1b16012-ae1f-4c8e-bcc8-716f180c408e",
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
              "id": "ad0d23aa-6d98-4bc0-89c6-d4f5d1a8f9aa"
            }
          ]
        },
        {
          "id": "79282219-1022-463c-96a5-604ea62e836a",
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
              "id": "1e06cc89-e2b3-42fe-a86a-abad1723f7be"
            }
          ]
        },
        {
          "id": "c2fbaa55-4b58-45a4-ba42-345be3278132",
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
              "id": "593d44a0-cd39-420e-9b53-9649c90e28e7"
            }
          ]
        },
        {
          "id": "1fe89276-db0a-4604-973e-0420dea6b287",
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
              "id": "6ce641bc-bf23-4313-a43d-cbc93a403c0a"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "861164a5-fc7c-4e44-8acb-04da0daa3724",
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
              "id": "a0d7b3b6-ca39-42a9-9b94-e9450d7f07d3"
            }
          ]
        },
        {
          "id": "c204be1d-2759-4241-a295-e8dfc8b8c211",
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
              "id": "20f00fc7-7261-484c-a024-d6a22cc1a3c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "7e55532e-051d-4730-8f59-6ff65318aa6c",
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
              "id": "7d2d1b69-7a96-4f1a-9fe9-12675fa41082"
            }
          ]
        }
      ]
    },
    {
      "name": "Campaign",
      "item": [
        {
          "id": "a3356837-bd75-4340-b46f-dc7c746667dc",
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
              "id": "fab33f14-90ce-43d3-8c32-dd3a464056ec"
            }
          ]
        },
        {
          "id": "cf54b751-0555-4678-a9cf-42fce3dec76b",
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
              "id": "228d59b5-9da4-4045-8374-59b85574d688"
            }
          ]
        },
        {
          "id": "dc924b3b-8a1f-465c-a42c-da89b78a550b",
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
              "id": "1bb23910-9d8e-43b6-933b-d22c7781f74a"
            }
          ]
        },
        {
          "id": "836ac8f4-bea6-40d5-b88a-7582a605b303",
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
              "id": "47d7ccd8-992b-4f8b-8c75-aa85c8a4030c"
            }
          ]
        },
        {
          "id": "d585fdf9-7a9f-4ca2-95b2-e312070677c5",
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
              "id": "f16451a3-ddef-40a1-a96e-d97ebe88c6d4"
            }
          ]
        },
        {
          "id": "9a213513-d77e-443f-bb62-b416b636c9ee",
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
              "id": "831e060e-27f0-4dcb-9664-32ec3fb4b987"
            }
          ]
        },
        {
          "id": "31a2ee04-e585-425e-8628-56253b97bcb5",
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
              "id": "75bc050c-7e49-4657-9b8d-5640f7ebb1d0"
            }
          ]
        }
      ]
    },
    {
      "name": "Sub",
      "item": [
        {
          "id": "e5f303ff-b229-4bbd-8456-d85069025050",
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
              "id": "f9048af8-910a-4cdc-a2d5-e63156c5152a"
            }
          ]
        },
        {
          "id": "7f6597f3-4d6c-49eb-997c-6b5686fb4b26",
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
              "id": "08f027f6-7874-4bf0-8217-159a79cfe429"
            }
          ]
        },
        {
          "id": "87559740-9797-44fe-b2ee-ef1d587ffb7d",
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
              "id": "db38e015-bbd9-4b2b-9921-c366014d8aa6"
            }
          ]
        },
        {
          "id": "f6048792-8684-4767-b86c-24c9c1a91cd2",
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
              "id": "5784f3b1-68eb-44b0-8e40-3664ea6a8e77"
            }
          ]
        }
      ]
    },
    {
      "name": "Geofence",
      "item": [
        {
          "id": "65968d8e-662e-45bc-9c7d-879cd7a9e2c0",
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
              "id": "c41c33fa-f6b2-474c-a4d2-7f68ba5d0e5d"
            }
          ]
        },
        {
          "id": "17b077bc-31b3-4e12-b5a5-dd76816d1273",
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
              "id": "065a6d9f-afa4-4146-b9ba-b3e83a1a6010"
            }
          ]
        },
        {
          "id": "a3b674df-86c0-4fe7-9cd3-0ab9029134f2",
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
              "id": "cab1838d-b532-4dec-9a0f-5d138b64c9fb"
            }
          ]
        },
        {
          "id": "220a3af7-6c3b-4265-a3b7-cc6973feb82c",
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
              "id": "0d1e3ec2-8e73-4842-8634-271674c46622"
            }
          ]
        },
        {
          "id": "4f4b1fed-aa43-4546-8558-3826751f39b9",
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
              "id": "90dd1fec-7158-4946-b971-d5d40da80bf5"
            }
          ]
        },
        {
          "id": "f7f5694e-5d47-47aa-ba9b-772f5a874566",
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
              "id": "9e5df97a-9dea-4c92-b6e2-38ca92466d36"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "58ea0756-e9a5-4946-8230-afbf0f26a01d",
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
              "id": "25d507df-3295-45c7-bd37-c51c4cd5f935"
            }
          ]
        },
        {
          "id": "a2ac402e-9839-4040-863e-be872a557188",
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
              "id": "d22ccf3f-e226-4848-a80e-3a08852bbc07"
            }
          ]
        },
        {
          "id": "a1dc9a2f-d340-4bc5-8115-73950fb7a2be",
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
              "id": "3d837ff6-ab1b-4244-bd0a-dc0969a11600"
            }
          ]
        },
        {
          "id": "f63ca5de-6f45-4273-b6f7-57d77054c920",
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
              "id": "1a58c2e3-fdc9-4d90-95f2-5149b3acd5f7"
            }
          ]
        },
        {
          "id": "3aa09ce6-3441-4ca7-9f12-862019011598",
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
              "id": "d4bd09e8-937e-47a6-9433-79a0c6e70251"
            }
          ]
        },
        {
          "id": "bc647590-5535-4641-9e44-d13d6a4e82a6",
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
              "id": "ccab7489-a4e0-4f03-9c93-572001beed60"
            }
          ]
        }
      ]
    }
  ]
}