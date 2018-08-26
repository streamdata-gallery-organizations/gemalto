{
  "info": {
    "name": "Gemalto IoT Application Enablement Platform API Notification Subscription Delete",
    "_postman_id": "1e79ac89-fe23-4110-8d5e-481437f51b62",
    "description": "Notification subscription delete.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "19c4d037-7847-4d35-a341-3c9cc7e7f72d",
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
              "id": "e494c339-0a88-4f22-b995-60ba82c2233c"
            }
          ]
        }
      ]
    },
    {
      "name": "Auth",
      "item": [
        {
          "id": "03d2bdb9-c18e-4ee1-98b7-b81cad5fc30f",
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
              "id": "5dff92e3-204e-4a86-b7c6-1f76f242c375"
            }
          ]
        }
      ]
    },
    {
      "name": "Device",
      "item": [
        {
          "id": "a6aee1b2-cecd-4432-8da7-f8e51314f61c",
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
              "id": "070cf1dd-adbd-4946-9fb6-2f2e64ac5d4c"
            }
          ]
        },
        {
          "id": "7a4ac65c-4896-4e06-a818-322a178c646b",
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
              "id": "1d9bf7b8-9941-48bd-887e-cce4d7e40465"
            }
          ]
        },
        {
          "id": "5035f2bf-2b1b-4ea7-a3f0-0a20bc62bef7",
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
              "id": "72e53a14-69f0-41a4-a750-cf8501d13dcc"
            }
          ]
        },
        {
          "id": "a75790a2-c1f9-4aa5-bea0-89f3402c7df8",
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
              "id": "e8163c8c-1a1b-4d26-b593-61f1845537ef"
            }
          ]
        },
        {
          "id": "be890a6e-8761-4d1c-8c23-988e1a605a48",
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
              "id": "9c292e09-b57d-4c90-aa44-12920c4d2e97"
            }
          ]
        },
        {
          "id": "3065bfbc-a061-421b-8c9f-a8b428678402",
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
              "id": "2269a776-0326-4e40-a55b-60a7c9d42f2d"
            }
          ]
        },
        {
          "id": "059f3195-6c09-4da0-9d83-ef1ac07d1847",
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
              "id": "97ce9a02-69c3-4b33-b5f9-b892bf2b5d30"
            }
          ]
        },
        {
          "id": "9866fa3b-6afb-41eb-a67d-e3ef5be66643",
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
              "id": "0af15617-2d14-4e71-9bc0-c7b60306da15"
            }
          ]
        },
        {
          "id": "771cbd3b-85be-438b-99bb-8f3ee01f7283",
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
              "id": "357e7220-95d1-45bb-b5c9-17e4421de213"
            }
          ]
        },
        {
          "id": "d61f2866-d807-4fcc-89ac-a30511b6a2ae",
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
              "id": "1094570f-508c-4816-bf9b-5c5511005834"
            }
          ]
        },
        {
          "id": "de984235-f569-424b-afca-04fd7c99ff9b",
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
              "id": "fa9ab386-4e0b-4851-ad3f-ae122654e73a"
            }
          ]
        },
        {
          "id": "3ad75d43-4dc2-4b4a-9a57-1eaff57d90c8",
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
              "id": "a932b6aa-379d-4f61-937a-114391b2c8df"
            }
          ]
        },
        {
          "id": "665469de-30eb-41c5-affa-a05a86409d34",
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
              "id": "38d039dd-9f82-4dbc-a54e-5568c3346fa8"
            }
          ]
        },
        {
          "id": "20ffc2e6-939a-4a56-afea-79626b4b0f72",
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
              "id": "2c28d628-eec3-4b71-a737-15ed6704373e"
            }
          ]
        },
        {
          "id": "0c09ae8b-4af6-485e-aecf-c9d0ac2f7bc6",
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
              "id": "0ccf8dfb-5291-4ecb-a803-66b595b518ca"
            }
          ]
        },
        {
          "id": "10f8f73d-5150-434f-8fbc-b23ae4014e9d",
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
              "id": "b86a4858-7252-44c1-934d-689048163002"
            }
          ]
        },
        {
          "id": "bbfa6774-945f-4892-971e-cca3d6f297f9",
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
              "id": "9b9327f6-8b83-4daf-b4cf-c791a154354a"
            }
          ]
        },
        {
          "id": "3528ed36-44fd-47b2-9c28-897e3e236630",
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
              "id": "c55b65ff-fe6d-4512-bf07-9fd6b0f22b4d"
            }
          ]
        },
        {
          "id": "0920b269-13bd-4152-90e1-aba7e65f1020",
          "name": "getV5.0DevicetypeList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceType/list.json?pageNumber=%7B%7D&pageSize=%7B%7D&showOnlyInUse=%7B%7D",
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
            "description": "Device type list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5e79e05-8ecf-4d82-951a-bfc1fe0752c2"
            }
          ]
        },
        {
          "id": "1751e723-c4d3-4d37-a509-4e565e8542e2",
          "name": "getV5.0DevicetypeGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceType/get.json?id=%7B%7D&key=%7B%7D",
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
            "description": "Device type get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b6a67b5-38ed-47f1-adfe-1dae4cc71027"
            }
          ]
        },
        {
          "id": "9f1dcfbd-449a-4d31-887a-bc9c929f192f",
          "name": "getV5.0DevicepropertyGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceProperty/get.json?deviceHandle=%7B%7D&deviceId=%7B%7D&name=%7B%7D",
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
            "description": "Device property get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5f3bbaf2-dfa2-43ec-ac47-c0dcfc2fc5b4"
            }
          ]
        },
        {
          "id": "dbb7b048-1802-4f65-8ad7-86d10be9517b",
          "name": "getV5.0DevicepropertySet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceProperty/set.json?deviceHandle=%7B%7D&deviceId=%7B%7D&name=%7B%7D&value=%7B%7D",
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
            "description": "Device property set."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b7e0817-185d-4668-8017-1836429e879c"
            }
          ]
        },
        {
          "id": "08147eda-c05a-4480-a9ad-d4cabe39b911",
          "name": "getV5.0DevicepropertyDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceProperty/delete.json?deviceHandle=%7B%7D&deviceId=%7B%7D&name=%7B%7D",
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
            "description": "Device property delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2da88b8-d1b9-4146-a77e-d699b53db245"
            }
          ]
        },
        {
          "id": "7bad11e6-ee31-45c0-ad0e-2962a70681b9",
          "name": "getV5.0DevicebatchStatus.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceBatch/status.json?transactionId=%7B%7D",
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
            "description": "Device batch status."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d3e39e3f-b072-4903-8235-fcae6b30f151"
            }
          ]
        },
        {
          "id": "a87b9a6d-34e8-49d6-b328-3b3c0a1ff560",
          "name": "getV5.0DevicecommandSend.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceCommand/send.json?commandExpiryDate=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&virtualCommand=%7B%7D",
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
            "description": "Device command send."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25817e45-931f-45f4-a27d-577ccde10657"
            }
          ]
        },
        {
          "id": "87a33bb7-6b47-4193-a12a-cea75adc29d0",
          "name": "getV5.0DevicecommandGet.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceCommand/get.json?deviceHandle=%7B%7D&deviceId=%7B%7D&deviceTypeId=%7B%7D&deviceTypeKey=%7B%7D&key=%7B%7D",
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
            "description": "Device command get."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1f8f5ad-96bf-47d3-9e98-2b97572c7fdc"
            }
          ]
        },
        {
          "id": "bcff0ab5-efcc-4b04-9756-ea772fbe0f5f",
          "name": "getV5.0DevicecommandList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceCommand/list.json?deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D&deviceTypeId=%7B%7D&deviceTypeKey=%7B%7D&featureId=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
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
            "description": "Device command list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0cfc75c4-f220-445e-bd8c-e86580b95f44"
            }
          ]
        },
        {
          "id": "827f3d2a-99c2-4170-91d8-de15c29fdf3d",
          "name": "getV5.0DevicemembershipList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceMembership/list.json?deviceId=%7B%7D&groupId=%7B%7D&groupIdNot=%7B%7D&membersOnly=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
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
            "description": "Device membership list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b13568c-cd33-4cad-ae48-433d58c53a03"
            }
          ]
        },
        {
          "id": "a481c39c-591d-41e0-a1f5-34beebbdbbdd",
          "name": "getV5.0DevicemembershipCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceMembership/create.json?deviceId=%7B%7D&groupId=%7B%7D",
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
            "description": "Device membership create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0beca71f-22b6-4f78-a65b-cb8b4f02dddb"
            }
          ]
        },
        {
          "id": "2a153736-71de-4064-a1dc-975b799a5aab",
          "name": "getV5.0DevicemembershipDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceMembership/delete.json?deviceId=%7B%7D&groupId=%7B%7D&id=%7B%7D",
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
            "description": "Device membership delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "235c58fd-c622-4d59-83c7-383e7e926f92"
            }
          ]
        },
        {
          "id": "52e52a98-342c-4c19-b6a8-19aaba68fcc0",
          "name": "getV5.0DevicemembershipCount.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/deviceMembership/count.json?deviceId=%7B%7D&groupId=%7B%7D&groupIdNot=%7B%7D",
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
            "description": "Device membership count."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1b5494e-e5d1-4bb6-88bb-f0b188605017"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "49867dd3-5b58-41a4-b3e3-702cfb9e29ce",
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
              "id": "c453408f-e414-4f73-8d20-82dd46237163"
            }
          ]
        },
        {
          "id": "538fde7a-773f-402e-b7ff-4edf8d805dc5",
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
              "id": "88463d58-71f2-4338-81d6-8f1a76e4bf98"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "f9d03475-68d4-4a5e-908e-666a46e1f0f8",
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
              "id": "f93d4fd7-91cc-4ea7-8508-b5d6308b87f5"
            }
          ]
        }
      ]
    },
    {
      "name": "Campaign",
      "item": [
        {
          "id": "594383b0-403c-45cd-aa76-01358e9b1179",
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
              "id": "87041395-3315-4672-887c-a8b660a4ed93"
            }
          ]
        },
        {
          "id": "9aad116e-a00e-4463-8624-030ba243da01",
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
              "id": "1ac9bf9c-70e9-4160-824a-c8120d9b9330"
            }
          ]
        },
        {
          "id": "b600548a-ef6c-478d-980a-1d387a3c3334",
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
              "id": "a7cdd98d-1f92-4989-a93b-ec8de3822e17"
            }
          ]
        },
        {
          "id": "43c020e4-756b-4b5f-94c0-be7e9297e3ac",
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
              "id": "bf7853f1-f4f5-450c-bbe8-e6d036e396b2"
            }
          ]
        },
        {
          "id": "f2867640-b714-453c-98bb-79ab3ef3793f",
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
              "id": "0d8deed8-54ab-434b-8186-94e7223436b0"
            }
          ]
        },
        {
          "id": "884bbd01-f59a-4a9c-a074-4f4a8ee40dbb",
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
              "id": "b3c454fe-4c9b-44a1-b735-7235ec97934c"
            }
          ]
        },
        {
          "id": "2373dfff-1650-4ec4-9147-2e8d419d6971",
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
              "id": "8fb290f8-f930-4a2b-84ae-aad6d921695e"
            }
          ]
        },
        {
          "id": "47f5e027-16a3-4554-b0d8-34cd0d1acbf9",
          "name": "getV5.0CampaigntargetList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaignTarget/list.json?campaignId=%7B%7D&isSupported=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&status=%7B%7D",
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
            "description": "Campaign target list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "684bb2b4-91f3-423a-9560-50e7eff3a50e"
            }
          ]
        },
        {
          "id": "047329bd-0ee0-4117-a471-1558ee0ac5c5",
          "name": "getV5.0CampaigntargetCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaignTarget/create.json?campaignId=%7B%7D&deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D",
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
            "description": "Campaign target create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7480d3bb-7e69-47bd-9b3a-8b3ddcbf7761"
            }
          ]
        },
        {
          "id": "eda37652-815a-4c25-8efb-44e796e1541d",
          "name": "getV5.0CampaigntargetDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/campaignTarget/delete.json?campaignId=%7B%7D&deviceGroupId=%7B%7D&deviceHandle=%7B%7D&deviceId=%7B%7D",
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
            "description": "Campaign target delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6ade8a0-a9e5-46a8-8977-685c6003fa33"
            }
          ]
        }
      ]
    },
    {
      "name": "Sub",
      "item": [
        {
          "id": "9b04eaf8-61e6-46a5-b639-a8d30a8a133b",
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
              "id": "74d55988-7bf3-48f8-b4fb-debbe14d42c3"
            }
          ]
        },
        {
          "id": "9fe6b6d7-dbf9-4e37-ac0e-f010c5161788",
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
              "id": "f52850d9-a217-4ab9-ae91-ebab6ef67b63"
            }
          ]
        },
        {
          "id": "27dee431-ca11-4c96-bf78-974ce8e57908",
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
              "id": "ec05b0aa-ede0-4ca2-b6e5-76efd7eae1f7"
            }
          ]
        },
        {
          "id": "659ad84e-c619-4b1c-94e3-65951175ac6c",
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
              "id": "3eaefa51-e62f-4f34-932e-6094f42dcdf9"
            }
          ]
        }
      ]
    },
    {
      "name": "Geofence",
      "item": [
        {
          "id": "628cf90d-fdf6-4181-a8b0-facc3c269a7a",
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
              "id": "6775a527-c137-4416-992b-bd91b2fdcc2e"
            }
          ]
        },
        {
          "id": "f64531eb-f419-4647-a2e5-94a95182019d",
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
              "id": "d75e1ab6-36ca-4fe2-bc38-9ff581678f29"
            }
          ]
        },
        {
          "id": "8a1ce2f9-f17e-4882-b366-8a97bda70f99",
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
              "id": "3f56ec45-8f66-4793-a634-9132e348ee8e"
            }
          ]
        },
        {
          "id": "5f5da9f8-5de1-472c-9a13-407e56a3ad70",
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
              "id": "9ac0dcf3-bc0f-45c9-b1a1-111e605a8ad4"
            }
          ]
        },
        {
          "id": "d7b7edd3-99e5-425f-b1ad-7a0c5c67a052",
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
              "id": "cb1821da-1ea7-4b78-98e4-b45d9964cb67"
            }
          ]
        },
        {
          "id": "12e40b36-da50-46c0-afa9-223931c971b5",
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
              "id": "3cf2830d-38bc-41cb-bcd0-cfdddc70b253"
            }
          ]
        },
        {
          "id": "afc13458-e1ab-4873-831d-fcf8690f1cca",
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
              "id": "c805612c-26c8-41e4-91a1-45995974f57b"
            }
          ]
        },
        {
          "id": "1ecc35e7-9756-491a-975b-a013eaf39024",
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
              "id": "98bdd6ab-6873-4b15-8120-099c31dc539c"
            }
          ]
        },
        {
          "id": "fe931060-6ffa-4f49-8254-60f9a1a93244",
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
              "id": "7afab88e-a5e5-4ca0-ad7f-6f8ddab526eb"
            }
          ]
        },
        {
          "id": "4d0dc470-8cf5-46d3-ab6b-2bd3b03e6343",
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
              "id": "25231be3-3914-4684-b655-9f89fa0744a0"
            }
          ]
        },
        {
          "id": "1e92ad2e-7fe3-4679-a77a-62c30b263b78",
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
              "id": "8761ba4d-b311-4c34-8a14-648d7eb9cd66"
            }
          ]
        },
        {
          "id": "933c070b-a0c6-4dce-99f0-6b36bb1132e2",
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
              "id": "a7304b9b-fc89-4633-be3c-9c4a23801cc7"
            }
          ]
        },
        {
          "id": "4eb7fcb1-8275-4779-83b1-569f0bbfcd68",
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
              "id": "6140a77b-6184-4036-85ee-f60b1b8ca0e5"
            }
          ]
        },
        {
          "id": "df87fec1-9815-4148-9540-f2d44fecc810",
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
              "id": "ba8cf221-bf49-42db-b9c2-0a73a69d74e6"
            }
          ]
        },
        {
          "id": "638f7c00-5a7d-406e-b861-13425f5b3cf7",
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
              "id": "f322f3e2-2a96-4693-9bd8-fa31476a9810"
            }
          ]
        },
        {
          "id": "4c0967ef-3463-4fd5-8911-ddbc567dc380",
          "name": "getV5.0GeofencemembershipList.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceMembership/list.json?geofenceId=%7B%7D&groupId=%7B%7D&groupIdNot=%7B%7D&membersOnly=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D",
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
            "description": "Geofence membership list."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17aa167f-077f-44e8-86a4-227e5dc12ff4"
            }
          ]
        },
        {
          "id": "b0000323-fc8c-45f9-af87-f3f36af7aecc",
          "name": "getV5.0GeofencemembershipCreate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceMembership/create.json?geofenceId=%7B%7D&groupId=%7B%7D",
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
            "description": "Geofence membership create."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a3f4ced-110f-4490-989a-9cbb65122dbe"
            }
          ]
        },
        {
          "id": "8bebe89d-f4e2-4518-8298-7c21cef6eaee",
          "name": "getV5.0GeofencemembershipDelete.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/geofenceMembership/delete.json?geofenceId=%7B%7D&groupId=%7B%7D&id=%7B%7D",
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
            "description": "Geofence membership delete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c27deaa2-d079-4185-bc12-cbfe04b69968"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "095849bb-de2b-4477-8e49-7bee2d3724c1",
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
              "id": "94040478-26f2-4ef6-9bb2-c3a2aa691a9d"
            }
          ]
        },
        {
          "id": "80e9a167-fd17-43d8-8e5d-b03f64f43fde",
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
              "id": "2c68566e-e045-4d50-8013-0a172207f0c2"
            }
          ]
        },
        {
          "id": "e76e3b94-b907-4dba-9143-b45218b4ddce",
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
              "id": "b5b76dd2-8dbc-46ac-8159-6aee95d98262"
            }
          ]
        },
        {
          "id": "73d98fdc-a8a9-4a77-a585-e5750847809c",
          "name": "getV5.0NetworkprovisioningDeactivate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/networkProvisioning/deactivate.json?deviceHandle=%7B%7D&devic