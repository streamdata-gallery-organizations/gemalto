{
  "info": {
    "name": "Gemalto IoT Application Enablement Platform API Alarm Condition Field List",
    "_postman_id": "53a3b464-c0a4-40e9-b467-e5c2e0ffc0fd",
    "description": "Alarm condition field list.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "82734b7e-f176-4d28-af0a-3894c349013f",
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
              "id": "fcde3fdf-934b-4e15-b5d2-c52522ade9df"
            }
          ]
        }
      ]
    },
    {
      "name": "Auth",
      "item": [
        {
          "id": "1acfbeab-f9f6-434f-80b0-1ddb414919f3",
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
              "id": "1772e21d-d5c7-42ea-ab7b-6f5a382158d2"
            }
          ]
        }
      ]
    },
    {
      "name": "Device",
      "item": [
        {
          "id": "7aca5caa-37d7-421b-aee3-634dd45fd7ec",
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
              "id": "d291130c-6a10-4c21-9702-5d5c1d81d124"
            }
          ]
        },
        {
          "id": "0813ac61-4c3a-4a3e-8e59-d0d689985a7f",
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
              "id": "67fac2c7-01c1-4754-851a-bacad9bdc288"
            }
          ]
        },
        {
          "id": "79a149ce-36ef-40ca-bb01-8c503d316195",
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
              "id": "851c022a-815a-4a66-ac7d-3c8cc9ec6466"
            }
          ]
        },
        {
          "id": "e1812983-2172-40ee-b3b8-ee43f0573201",
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
              "id": "43672869-e19e-46be-a27c-c96c017d5943"
            }
          ]
        },
        {
          "id": "182c45e5-ad01-4c03-ad4a-d71b90a9b34b",
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
              "id": "01cf4145-c12b-4c28-bf55-0bd4ec9bc195"
            }
          ]
        },
        {
          "id": "574b082a-eee5-498e-8e79-0f006481c687",
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
              "id": "e956a383-900b-4453-bc0a-cc71f8347ec1"
            }
          ]
        },
        {
          "id": "996be52d-9ac4-4430-817d-b30b368f3d21",
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
              "id": "7a9d6a08-bcd1-42ce-a167-cde1b116f050"
            }
          ]
        },
        {
          "id": "1a653ca7-ea9e-423c-b720-d7730013150c",
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
              "id": "a0781546-623a-48d2-a119-ed74e08d2b4c"
            }
          ]
        },
        {
          "id": "78b9cbf8-76b3-4393-89f6-55f7fae96564",
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
              "id": "098bed21-522a-419c-9431-8228a2286198"
            }
          ]
        },
        {
          "id": "ca0d6cdd-7f8d-47a3-8f5a-42ca0781dbed",
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
              "id": "279f082e-8efc-4b7e-8edb-811d19cc80b9"
            }
          ]
        },
        {
          "id": "003dec7b-5d2e-43ea-8e5c-cda0f63c09a3",
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
              "id": "4c7ad35e-64b7-4348-905e-94e55ed821eb"
            }
          ]
        },
        {
          "id": "f51689f4-e083-4f14-8ea4-0bffceb3fa0e",
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
              "id": "dc23fc7e-e699-4cbb-811b-020301a37165"
            }
          ]
        },
        {
          "id": "9b31405f-23f8-4bf3-a14d-ff9957881409",
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
              "id": "a81205ef-8245-4eb9-b960-9a58bac33d9d"
            }
          ]
        },
        {
          "id": "004f5013-afb7-4717-b869-388094a7f8e0",
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
              "id": "f7794fb1-36d6-433b-8f2e-6385f0026680"
            }
          ]
        },
        {
          "id": "48067bef-e09b-4856-93bb-60cc8564f829",
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
              "id": "7a2ead28-ba7e-4100-b392-b32b6ce87465"
            }
          ]
        },
        {
          "id": "8b9f5805-f9ca-4ab7-85f3-55f13dd966aa",
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
              "id": "1c2e5363-f56a-4cbd-bfc4-df2706e5cca5"
            }
          ]
        },
        {
          "id": "2ebd4c01-8f69-4d40-9c46-58c5414f9fc8",
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
              "id": "82436e8c-7f55-4d86-9e5e-ce5a5f5d4bab"
            }
          ]
        },
        {
          "id": "dd804f06-4914-46f8-8c73-124f322a6878",
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
              "id": "43d43100-1175-4d89-b8e1-d615c64d0aa2"
            }
          ]
        },
        {
          "id": "f1c2c5fb-8cf4-4aba-99a5-ff52cf5a69b7",
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
              "id": "4202aa27-58cb-4a86-b042-8d53144755b2"
            }
          ]
        },
        {
          "id": "fbbdceda-3282-49fc-b2e9-704b12485333",
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
              "id": "85ebf7bb-5b72-4d54-8fd4-be673939728b"
            }
          ]
        },
        {
          "id": "33ad5f3c-40ca-4fed-9995-bce98e7f642e",
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
              "id": "78a4e29b-355e-42f3-b2e5-88684d0a3fe0"
            }
          ]
        },
        {
          "id": "b92da675-a3a8-4134-9756-7fa93147545e",
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
              "id": "a879b0ea-3ab0-4930-923e-14cc99d99eb3"
            }
          ]
        },
        {
          "id": "7fd94895-f874-4e65-93c4-4b8a56a82b69",
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
              "id": "20ca8652-8ef7-430c-b52d-49e810a24891"
            }
          ]
        },
        {
          "id": "711939b1-9b43-4bb6-b753-dc8bb27123bf",
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
              "id": "a6e2dc41-fcde-4bf5-ba3a-67a26bdfc7a5"
            }
          ]
        },
        {
          "id": "cc0c772d-a0bf-400d-bcb3-6e45bdcc6fb3",
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
              "id": "1aec6e80-f8b4-4faa-a5c7-9bba488a0194"
            }
          ]
        },
        {
          "id": "0275b2f7-16a3-47f8-9ea8-78f90b9a31d6",
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
              "id": "74eb81a4-1997-46a1-afaf-e55c7ba07bcd"
            }
          ]
        },
        {
          "id": "0a837eea-4f57-4874-89af-0a248d6f96ac",
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
              "id": "aabd1155-164a-4465-a87c-6b44d6a18228"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "8cecdd5a-56d8-460c-b91e-6031a5b32499",
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
              "id": "c08ee49d-9da9-4540-9ab1-3a03bdaa771d"
            }
          ]
        },
        {
          "id": "cc0a5cf1-dce2-4dff-88fb-98086d9960fd",
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
              "id": "29078d7d-a534-40d7-8f6e-48334f489e46"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "d802f6b2-3ead-4a15-9b7e-5229a16c6226",
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
              "id": "9502acd5-7e63-41a4-82ae-1107c532b22a"
            }
          ]
        }
      ]
    },
    {
      "name": "Campaign",
      "item": [
        {
          "id": "1b4ec2fa-0f71-48a2-bacd-3526e00ee302",
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
              "id": "732705c6-c2c3-4dfd-b205-d79c829f55bb"
            }
          ]
        },
        {
          "id": "425db8b4-30f1-4d54-b2fb-e91967ff8a4b",
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
              "id": "b1a74b15-8769-4d8f-9ff5-1d67317fb14d"
            }
          ]
        },
        {
          "id": "bd79fb6c-e268-4a60-baee-bbf25fe746d2",
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
              "id": "2303771c-d4b4-4b83-8424-2e825c59d4cf"
            }
          ]
        },
        {
          "id": "72e81370-73bc-4f35-b726-5fcce9302355",
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
              "id": "d37eeb82-3b6e-49f5-a6bf-9d87a2eae363"
            }
          ]
        },
        {
          "id": "c2c2f12a-89c8-46f5-b7d8-a34c2b636e44",
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
              "id": "5a2a22d2-47dc-4a78-8cfc-d39b180b6233"
            }
          ]
        },
        {
          "id": "8bab3c8c-e1fa-44e1-9325-f71ef82533b8",
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
              "id": "0169fe1a-5e86-4bc0-bbf0-cc3d425c27bb"
            }
          ]
        },
        {
          "id": "c1fa04ef-9e8b-4dd9-9704-9cfec08338b8",
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
              "id": "76d06dc7-7fea-411e-9649-c457ddbf6629"
            }
          ]
        },
        {
          "id": "228100e0-7a17-4ed5-bed4-1248c14b479f",
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
              "id": "4fcb3a74-c0e5-49e2-b4ec-ff100173b6c4"
            }
          ]
        },
        {
          "id": "6f929e0e-38d7-4246-8ff8-8bd8d5afc31f",
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
              "id": "015bb813-121b-43e5-9468-9873368805f3"
            }
          ]
        },
        {
          "id": "bb4c92dc-2940-406d-83f6-cf1b1907b414",
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
              "id": "c281e178-f24c-41f4-b824-50d5a85a6157"
            }
          ]
        }
      ]
    },
    {
      "name": "Sub",
      "item": [
        {
          "id": "66754625-1220-4638-a2a1-6b029be8406d",
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
              "id": "bcf17c5e-427d-4eea-90be-11bd3c7c9496"
            }
          ]
        },
        {
          "id": "d80c2151-b3c9-48ce-b2e1-5c48ac1608cf",
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
              "id": "4c07711e-4a84-408a-9eb0-909b6e278c2d"
            }
          ]
        },
        {
          "id": "6112668b-8f34-43a3-a6f6-f981f2d78d42",
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
              "id": "4583c705-9e58-4c41-8e0c-e0dff8919032"
            }
          ]
        },
        {
          "id": "89733013-da05-45f4-b6e0-b092f23be302",
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
              "id": "5d5d84a6-0a8a-4e9e-8db3-711e993e3856"
            }
          ]
        }
      ]
    },
    {
      "name": "Geofence",
      "item": [
        {
          "id": "3e3dc40a-52ab-4581-98bc-5df6e4974d10",
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
              "id": "192b01c8-9b8d-4a5a-9ef3-74879264dfdd"
            }
          ]
        },
        {
          "id": "30cc44fd-c9fb-4a9e-acb4-173ac98bd3bc",
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
              "id": "082b78ae-2706-43df-b97c-aa64268dc1a3"
            }
          ]
        },
        {
          "id": "fede3b8f-52db-418a-8cec-a24371fb7233",
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
              "id": "80ce0a2a-5740-4043-bda6-497b319ab101"
            }
          ]
        },
        {
          "id": "02cef0e3-e1c4-47d0-aae9-3d4763ac1501",
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
              "id": "ada399b7-f4a0-4138-9118-06a3de91992b"
            }
          ]
        },
        {
          "id": "3615efad-218a-460d-96a1-43f7f73c5774",
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
              "id": "5614e955-8140-4f10-b0a5-119f72da486c"
            }
          ]
        },
        {
          "id": "7b6ad9e7-e3df-49c7-9dac-f6cad66c417a",
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
              "id": "8afc5f81-9afc-48f7-bc7e-c2c92e0b3f3c"
            }
          ]
        },
        {
          "id": "5add00f5-1b8b-4ae8-90a8-731ff288f06a",
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
              "id": "e8165fd5-16cf-4671-8b66-f8f8ac501402"
            }
          ]
        },
        {
          "id": "db5d79b2-9d8c-4d38-b96f-c84765d96411",
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
              "id": "58d7e0ba-3cdb-4b1b-b057-873877960a06"
            }
          ]
        },
        {
          "id": "d34822c2-4ad6-4389-b0b1-53e3a8f5ac0f",
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
              "id": "f1ddabfb-42ee-4739-b485-832825af83a2"
            }
          ]
        },
        {
          "id": "908866ae-3d23-44d7-ada4-87911fca7f10",
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
              "id": "c355024c-b010-4b67-bbfb-0fa0ef47b36c"
            }
          ]
        },
        {
          "id": "51a9db54-4079-46f2-980e-4493347cd16a",
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
              "id": "4b5845ca-d63d-4ed7-9d56-fc205a3e75c0"
            }
          ]
        },
        {
          "id": "0c2f9486-57a9-4bcc-be05-b39fb26b43cb",
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
              "id": "6c32442e-f062-449b-9ce4-a60f1dd9375a"
            }
          ]
        },
        {
          "id": "cb144f16-dac9-407c-beec-2540d52d13a1",
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
              "id": "e75ced25-2531-4e0b-b8ec-36c15db7b40d"
            }
          ]
        },
        {
          "id": "f1e6c553-ee8a-4953-821b-1e6d4c617a97",
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
              "id": "2c0c0bb4-eba7-4679-81f7-3c184ea0c36f"
            }
          ]
        },
        {
          "id": "8c0e624a-7d63-42ac-b279-bf08b0db12bd",
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
              "id": "af13acda-8aef-4299-9ceb-a7601843cb75"
            }
          ]
        },
        {
          "id": "7c83fbd3-6593-40f7-9c3d-5ae9c7f4032d",
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
              "id": "a36b5508-f686-4489-981b-e912ead1e5ee"
            }
          ]
        },
        {
          "id": "327414dd-1994-40fb-9a23-2e82d742bf76",
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
              "id": "3de69efe-0e21-489b-a52c-23351bdbcfc7"
            }
          ]
        },
        {
          "id": "14cf8735-aabb-46f6-8ef4-ba7aee6e5969",
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
              "id": "c4a5fcc9-4d01-4f78-be52-d6a28cd0f345"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "3cb8383f-afe4-4b39-b621-5477c7e39722",
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
              "id": "1b778aac-6aec-413c-82e6-7c3340f4558f"
            }
          ]
        },
        {
          "id": "1c8fd5e4-d4e3-4240-8d3c-0b5c975f66dc",
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
              "id": "ca6104b8-6f29-4d8e-9751-10db4e7d2565"
            }
          ]
        },
        {
          "id": "12c4b923-9314-4c55-ac32-6716157c62f2",
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
              "id": "9d9caf58-fcda-4686-8e94-257a24d87c97"
            }
          ]
        },
        {
          "id": "8031fc1a-c2e7-423a-bd34-c10cbe68f359",
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
              "id": "b36c95ef-9986-4811-9d51-cb0e490f8c83"
            }
          ]
        },
        {
          "id": "c6be8a95-4144-4fcc-98a0-ef2434570f7b",
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
              "id": "8a03eb30-8d3a-4614-b098-5773413cbe3b"
            }
          ]
        },
        {
          "id": "5288eb56-19dd-4311-96e2-e8d0166fee3c",
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
              "id": "449d1d89-8bc1-41a7-aae0-806a5a0227f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Outbound",
      "item": [
        {
          "id": "db1903a2-9ac5-4e82-91cd-62db7d83ef06",
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
              "id": "934ff689-f109-4cd3-b0fd-6d72024977a8"
            }
          ]
        }
      ]
    },
    {
      "name": "Report",
      "item": [
        {
          "id": "a6050e4b-cf77-4769-a681-56481b2cf4ac",
          "name": "getV5.0ReportbatchPurge.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-io