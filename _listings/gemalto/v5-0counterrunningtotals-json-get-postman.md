{
  "info": {
    "name": "Gemalto IoT Application Enablement Platform API Counter Running Totals",
    "_postman_id": "aa6756dd-c41d-4f2f-9b7b-b4b09156bcfc",
    "description": "Counter running totals.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Tools",
      "item": [
        {
          "id": "f5d7baee-ddfd-448f-aef3-cc59618118e2",
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
              "id": "61384eae-0568-4b30-b2b7-5fd7fbc2cca4"
            }
          ]
        }
      ]
    },
    {
      "name": "Auth",
      "item": [
        {
          "id": "5c13ffda-62c4-49a2-90ff-20d64a0d6f27",
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
              "id": "06a2cc36-ee82-41d1-ae5a-7237a26a3f49"
            }
          ]
        }
      ]
    },
    {
      "name": "Device",
      "item": [
        {
          "id": "6f1ab052-bc4c-4b92-9cd0-2965ec99dc44",
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
              "id": "4b7c4477-ad1a-4fc3-b16d-e57214f4d4db"
            }
          ]
        },
        {
          "id": "5b75f23c-d096-4d98-be19-b0cbdb3f579c",
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
              "id": "9518e86e-52ec-41ee-9390-8102e64214b5"
            }
          ]
        },
        {
          "id": "bbc75cd4-bd6e-4d3b-9a2e-9380180de7e6",
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
              "id": "d1b66d57-882e-41d4-9b46-1a6c061561b1"
            }
          ]
        },
        {
          "id": "55c35cc9-41d6-4c9e-87ba-febeb7c676a6",
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
              "id": "469f0da3-1898-48de-987a-4f97c0e5ab02"
            }
          ]
        },
        {
          "id": "54bf2e44-7817-4184-9cfe-709420c02e44",
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
              "id": "5fea3b29-8f6c-4e2c-aa05-4135932e90a7"
            }
          ]
        },
        {
          "id": "201ddf14-f9e7-437f-b8d3-7c41f5408da5",
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
              "id": "9ec48b14-1dc9-4a9c-be8d-e3e72a047db1"
            }
          ]
        },
        {
          "id": "43325821-aaa4-485f-b3a5-73667fc05e37",
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
              "id": "962a6d56-94de-4143-a93a-535e8f008b44"
            }
          ]
        },
        {
          "id": "9d0ce90b-f847-4923-aa28-31f45378a1c3",
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
              "id": "3c929c0a-1e46-46b1-b09e-d01bb706dc29"
            }
          ]
        },
        {
          "id": "e21face4-1f0f-4ae8-81bc-56682e104816",
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
              "id": "56f2baba-5c99-45f4-b736-c4d0d609dc3d"
            }
          ]
        },
        {
          "id": "20faee5f-135e-4320-8adb-3b8dab750335",
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
              "id": "42238dba-07ca-47c9-af2f-1d0b44ab503a"
            }
          ]
        },
        {
          "id": "5c265d76-9f16-4f38-877a-77c810867291",
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
              "id": "4b525616-4fa0-46b2-b2b8-2dd6d3270d51"
            }
          ]
        },
        {
          "id": "862a80db-9eec-4818-8f73-a3ffbe7de5c1",
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
              "id": "b06e9bf6-5e8b-45e4-8fe2-d6457023b193"
            }
          ]
        },
        {
          "id": "e7097812-5d14-49dd-bce3-67094254587a",
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
              "id": "28dd1e67-ef9f-4cd0-88d3-c915765a478d"
            }
          ]
        },
        {
          "id": "c17ded02-b272-4f06-8379-adf998922269",
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
              "id": "1bac7ee0-4490-4b6b-ac6a-a930037aceb5"
            }
          ]
        },
        {
          "id": "f9984818-c9e6-4ff0-97c3-546f90e4b29a",
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
              "id": "1a1b5a5d-7174-4eda-b608-22ef696d9ce0"
            }
          ]
        },
        {
          "id": "11ecf017-4e89-4ec5-ac7e-592e150dd679",
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
              "id": "a558e332-75a3-4a46-9930-b231b2409197"
            }
          ]
        },
        {
          "id": "43cd1ae1-553e-4b1b-a724-7674188ddd13",
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
              "id": "a190918c-6d83-4288-844c-5519f8f97922"
            }
          ]
        },
        {
          "id": "5daec5ac-6c29-40de-b955-8021cd5f5805",
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
              "id": "5cd96212-aedd-433b-90e9-1e5678edfaca"
            }
          ]
        },
        {
          "id": "9cf6513e-40a4-4d96-a384-d6f882e4c00e",
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
              "id": "c36342d8-f804-41af-9655-b08a58ad878a"
            }
          ]
        },
        {
          "id": "d194cbaa-f218-42f6-bfc5-780e6c3a44ff",
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
              "id": "ba5ef428-4aec-4b22-b73f-8b7186bf8335"
            }
          ]
        },
        {
          "id": "497d173b-28cb-4890-89e5-b85fbbb22090",
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
              "id": "c1eba40e-dfb4-456c-bfcb-d77150652844"
            }
          ]
        },
        {
          "id": "1635d75c-330d-482f-acb0-a30e0766aeb0",
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
              "id": "91bb1ec3-5827-4066-ab31-f51f884620b0"
            }
          ]
        },
        {
          "id": "8ece0056-fad3-468b-a6ff-3ed3e68363d8",
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
              "id": "e88c6be9-640b-484d-9022-43065c92c973"
            }
          ]
        },
        {
          "id": "0aafd2f9-427a-406b-9176-e40fcc2e1b51",
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
              "id": "3c45fb31-9311-4bb4-9816-5a23d09c979c"
            }
          ]
        },
        {
          "id": "9035f27f-5c59-4bde-a97c-5a6265296e17",
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
              "id": "b40322f0-09dd-44da-9045-207d5b447026"
            }
          ]
        },
        {
          "id": "0384e159-77e6-4efa-bbb4-154b0297284f",
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
              "id": "9a12606d-0ffd-4a8a-b33a-852db39ab3c0"
            }
          ]
        },
        {
          "id": "5eb4827f-44d5-4168-8e49-9215325fefab",
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
              "id": "720851e1-8d87-4299-a067-aedae2ed887a"
            }
          ]
        },
        {
          "id": "0bbefd17-81a2-4ea3-bbb8-b982855c5fb8",
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
              "id": "34f789fc-f0f2-44bc-84b8-0013c4a8cf37"
            }
          ]
        },
        {
          "id": "88dbd11e-df47-42ce-a713-ecd7a5404a70",
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
              "id": "245c593f-023c-4213-b3bd-be63ddaaac27"
            }
          ]
        },
        {
          "id": "555310a5-36ac-4e6d-833c-39a53de6dbef",
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
              "id": "5bdfce99-d7ff-4817-8426-0a33e00745d0"
            }
          ]
        },
        {
          "id": "de3a6314-d6a2-49db-82d1-dec871f5c25d",
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
              "id": "d4f7736a-f7a7-488b-8fb1-146976c76ca5"
            }
          ]
        }
      ]
    },
    {
      "name": "Event",
      "item": [
        {
          "id": "de974e29-382f-42e9-96a8-790110dcf2cd",
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
              "id": "9868c9a9-642c-4447-9003-54e16168ea0b"
            }
          ]
        },
        {
          "id": "73da9007-8c13-4c28-94e5-40d3bbedb8c4",
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
              "id": "880727ef-e00e-40cf-80d6-19df725dfd3f"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "bdcc8b8d-6c17-4943-bc0e-bb471cdb3236",
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
              "id": "d9e7d7c4-9005-4404-a718-a145622a1bb1"
            }
          ]
        }
      ]
    },
    {
      "name": "Campaign",
      "item": [
        {
          "id": "cd2fe9b4-7725-43a9-b412-1fab0703e3a0",
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
              "id": "59ddb3e4-aca0-4fec-baf8-326d8dabd539"
            }
          ]
        },
        {
          "id": "fb94e62b-f4d0-48db-81db-ae4fcd913d65",
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
              "id": "956cd5eb-0f2a-4110-a836-b8906236b325"
            }
          ]
        },
        {
          "id": "d2eab1b3-073a-444f-8144-e11c18a47c2c",
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
              "id": "a7347d64-ba2a-4fbf-8f3c-fe0496a51510"
            }
          ]
        },
        {
          "id": "a925464f-0f1b-4509-9507-e1b132831fd7",
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
              "id": "484164aa-0b42-42c4-b00f-fd32a6e81c56"
            }
          ]
        },
        {
          "id": "38931e83-ba60-48f8-888e-7684586d407b",
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
              "id": "b3acd13f-4901-4de8-9290-4fbe5b270f7e"
            }
          ]
        },
        {
          "id": "bf9c5355-817d-4f92-85d8-0cd5dee37112",
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
              "id": "fcb1edb1-ec38-4d84-ae4a-764fe9fb423b"
            }
          ]
        },
        {
          "id": "873845d5-cd47-41ab-a17e-16a10fae789d",
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
              "id": "1cca052f-aa06-4f76-a7b9-d0c348941001"
            }
          ]
        },
        {
          "id": "0669fab3-f530-4c2a-94f5-c29ad8073e19",
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
              "id": "46ba59b7-5bc1-4e7a-a597-ecab46530208"
            }
          ]
        },
        {
          "id": "ff6e204e-f1bd-4bc4-aa60-507593eb9bc3",
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
              "id": "710cde8e-21de-4e52-bc2a-04056fc57def"
            }
          ]
        },
        {
          "id": "2a97233f-cde4-47ad-85dd-4ed18a5c709c",
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
              "id": "c22766e5-fab1-4acb-b8d3-a4582d4b5a37"
            }
          ]
        }
      ]
    },
    {
      "name": "Sub",
      "item": [
        {
          "id": "9bad4057-860b-497a-8730-bed538893804",
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
              "id": "5f08e8d0-4aae-41b6-8d51-80d4d7eff663"
            }
          ]
        },
        {
          "id": "54d829cd-5a41-45a0-87f6-2c6d05fae58b",
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
              "id": "84662118-b35c-4ee3-a24e-f99ce79775ae"
            }
          ]
        },
        {
          "id": "9960cc15-d948-4649-abc1-d0066520f064",
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
              "id": "9f7669b3-2374-42b7-96a4-8cf813f950a7"
            }
          ]
        },
        {
          "id": "1272d5b1-70b9-4c96-bca6-d4d90335cd98",
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
              "id": "e2339e02-16e8-4ccf-9c6d-d90019b772c5"
            }
          ]
        }
      ]
    },
    {
      "name": "Geofence",
      "item": [
        {
          "id": "200e3072-2eeb-4099-bc8c-66352279d9a1",
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
              "id": "9839940c-26f5-4a7f-a664-4975049ec5ec"
            }
          ]
        },
        {
          "id": "0873bda3-5791-478f-b325-ad0b968789c7",
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
              "id": "214cda93-59d3-413d-8f4b-57054e3fa28f"
            }
          ]
        },
        {
          "id": "a45da85b-da61-438e-a182-0d972f8f39ad",
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
              "id": "8f679120-6a8c-488e-b810-eba114e78e85"
            }
          ]
        },
        {
          "id": "4e72088d-d7c9-44bc-9696-9c455675d5db",
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
              "id": "151c7aef-536f-4df0-a9c3-228b2027f974"
            }
          ]
        },
        {
          "id": "5b1df612-40bc-4850-89b8-b246ca763605",
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
              "id": "1807820c-cf39-41bf-878a-72622dc4f256"
            }
          ]
        },
        {
          "id": "bbeb6314-3774-4c1a-a56c-37d3639d9db1",
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
              "id": "e4b5aecb-ed1a-47a0-9636-101772520a73"
            }
          ]
        },
        {
          "id": "b3b1f7d5-d50c-4b61-97c0-e91c0f59657a",
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
              "id": "301bbb44-7bf4-4b70-b80d-d61872e9729b"
            }
          ]
        },
        {
          "id": "2425f9f3-4f30-4251-a9c3-9e20543c61c1",
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
              "id": "65e5c6ad-f9a1-4269-979e-6ab1adf124a0"
            }
          ]
        },
        {
          "id": "b8ab2303-525d-4f3b-82cd-1f3b8fd60ec3",
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
              "id": "8238e36a-c0c2-40e3-ab37-8b4704b404ec"
            }
          ]
        },
        {
          "id": "e9f4db48-f51c-40c7-bf71-a2fde115f502",
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
              "id": "08a6cf5f-2583-4157-a391-58a26dcea19e"
            }
          ]
        },
        {
          "id": "b8d070d5-0687-4987-a8ba-d46a7718abf8",
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
              "id": "65eda8c3-4e82-485f-83dc-23611e8c18f3"
            }
          ]
        },
        {
          "id": "02619da6-1e09-439c-a68b-c6afc6b70144",
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
              "id": "3d5dd53f-54ec-43ae-b7e8-b79dcefdb2ed"
            }
          ]
        },
        {
          "id": "8ebc54a7-7df2-4d2f-8bd7-6a17234e8049",
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
              "id": "391fbc27-4604-4670-b1d3-566fde780187"
            }
          ]
        },
        {
          "id": "d8e6709e-74e9-4536-80e5-7a22e9a46bcd",
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
              "id": "9578f552-9e13-4719-89c4-78a7869f5730"
            }
          ]
        },
        {
          "id": "1842b81f-7a98-4a63-bfc8-24a9f99e40e6",
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
              "id": "edbe0dfa-aff7-43fc-8dde-948631a554d2"
            }
          ]
        },
        {
          "id": "c5eda069-f17e-4693-9e93-ecb74a35f939",
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
              "id": "7324614c-dc3d-44d2-a042-57ab0b1ab835"
            }
          ]
        },
        {
          "id": "ecff3c97-173c-4b51-ade5-337dcadcf319",
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
              "id": "198aa91a-3b26-4eb8-8743-9a93e7e616ec"
            }
          ]
        },
        {
          "id": "ac94dd53-287b-46bc-b82f-67a8efe43872",
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
              "id": "afb14ef8-dc0c-4600-95df-fd0d3e811b09"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "36640efc-9ca4-46ff-8ccd-84de0e032c9d",
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
              "id": "bbe0c46a-4c57-4708-92b9-d73ea1e9115a"
            }
          ]
        },
        {
          "id": "f4f4007c-0b08-48f5-8156-0257641ae5d2",
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
              "id": "f77767a5-88c0-4eef-83ae-0ccafc5c7fb9"
            }
          ]
        },
        {
          "id": "34f6515f-c3b2-4baf-a19b-4154e27a3517",
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
              "id": "9d0480a2-ac48-4ba6-97c4-9506f678537c"
            }
          ]
        },
        {
          "id": "1f135e2b-7200-43b1-b162-3ec91255664e",
          "name": "getV5.0NetworkprovisioningDeactivate.json",
          "request": {
            "url": "http://virtserver.swaggerhub.com/tkarakai-gto/gemalto-iot-aep/1.0.0/v5.0/networkProvisioning/deactivate.json?deviceHandle=%7B%7D&deviceId=%7B%7D",
      