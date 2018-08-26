---
swagger: "2.0"
x-collection-name: Gemalto
x-complete: 0
info:
  title: Gemalto IoT Application Enablement Platform API Device List By Property
  description: Device list by property.
  version: 1.0.0
host: virtserver.swaggerhub.com
basePath: /tkarakai-gto/gemalto-iot-aep/1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v5.0/tools/time:
    get:
      summary: Tools Time
      description: Tools time.
      operationId: getV5.0ToolsTime
      x-api-path-slug: v5-0toolstime-get
      responses:
        200:
          description: OK
      tags:
      - Tools
      - Time
  /v5.0/auth/sign:
    get:
      summary: Auth Sign
      description: Auth sign.
      operationId: getV5.0AuthSign
      x-api-path-slug: v5-0authsign-get
      parameters:
      - in: query
        name: authOrg
        description: the organization key
      - in: query
        name: authTime
        description: the current time in yyyyMMddHHmmss format
      - in: query
        name: authUser
        description: the user name
      responses:
        200:
          description: OK
      tags:
      - Auth
      - Sign
  /v5.0/device/get.json:
    get:
      summary: Device Get
      description: Device get.
      operationId: getV5.0DeviceGet.json
      x-api-path-slug: v5-0deviceget-json-get
      parameters:
      - in: query
        name: handle
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Device
  /v5.0/device/list.json:
    get:
      summary: Device List
      description: Device list.
      operationId: getV5.0DeviceList.json
      x-api-path-slug: v5-0devicelist-json-get
      parameters:
      - in: query
        name: deviceTypeId
      - in: query
        name: deviceTypeKey
      - in: query
        name: deviceTypeName
      - in: query
        name: endDateCreated
      - in: query
        name: groupId
      - in: query
        name: groupIdNot
      - in: query
        name: id
      - in: query
        name: name
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: startDateCreated
      responses:
        200:
          description: OK
      tags:
      - Device
      - List
  /v5.0/device/count.json:
    get:
      summary: Device Count
      description: Device count.
      operationId: getV5.0DeviceCount.json
      x-api-path-slug: v5-0devicecount-json-get
      responses:
        200:
          description: OK
      tags:
      - Device
      - Count
  /v5.0/device/create.json:
    get:
      summary: Device Create
      description: Device create.
      operationId: getV5.0DeviceCreate.json
      x-api-path-slug: v5-0devicecreate-json-get
      parameters:
      - in: query
        name: deviceTypeId
      - in: query
        name: deviceTypeKey
      - in: query
        name: groupId
      - in: query
        name: handle
      - in: query
        name: iccid
      - in: query
        name: msisdn
      - in: query
        name: name
      - in: query
        name: networkId
      - in: query
        name: properties
      responses:
        200:
          description: OK
      tags:
      - Device
      - Create
  /v5.0/device/update.json:
    get:
      summary: Device Update
      description: Device update.
      operationId: getV5.0DeviceUpdate.json
      x-api-path-slug: v5-0deviceupdate-json-get
      parameters:
      - in: query
        name: deviceTypeId
      - in: query
        name: deviceTypeKey
      - in: query
        name: handle
      - in: query
        name: iccid
      - in: query
        name: id
      - in: query
        name: msisdn
      - in: query
        name: name
      - in: query
        name: networkId
      - in: query
        name: properties
      responses:
        200:
          description: OK
      tags:
      - Device
  /v5.0/device/delete.json:
    get:
      summary: Device Delete
      description: Device delete.
      operationId: getV5.0DeviceDelete.json
      x-api-path-slug: v5-0devicedelete-json-get
      parameters:
      - in: query
        name: handle
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Device
  /v5.0/device/listByProperty.json:
    get:
      summary: Device List By Property
      description: Device list by property.
      operationId: getV5.0DeviceListbyproperty.json
      x-api-path-slug: v5-0devicelistbyproperty-json-get
      parameters:
      - in: query
        name: name
      - in: query
        name: value
      responses:
        200:
          description: OK
      tags:
      - Device
      - List
      - Property
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---