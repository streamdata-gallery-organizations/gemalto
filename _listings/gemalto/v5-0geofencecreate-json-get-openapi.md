---
swagger: "2.0"
x-collection-name: Gemalto
x-complete: 0
info:
  title: Gemalto IoT Application Enablement Platform API Geofence Create
  description: Geofence create.
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
  /v5.0/device/listByPropertySet.json:
    get:
      summary: Device List By Property Set
      description: Device list by property set.
      operationId: getV5.0DeviceListbypropertyset.json
      x-api-path-slug: v5-0devicelistbypropertyset-json-get
      parameters:
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Device
      - List
      - Property
      - Set
  /v5.0/device/listByPropertyNotSet.json:
    get:
      summary: Device List By Property Not Set
      description: Device list by property not set.
      operationId: getV5.0DeviceListbypropertynotset.json
      x-api-path-slug: v5-0devicelistbypropertynotset-json-get
      parameters:
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Device
      - List
      - Property
      - Not
      - Set
  /v5.0/deviceState/get.json:
    get:
      summary: Device State Get
      description: Device state get.
      operationId: getV5.0DevicestateGet.json
      x-api-path-slug: v5-0devicestateget-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: featureId
      - in: query
        name: fieldNames
      responses:
        200:
          description: OK
      tags:
      - Device
      - State
  /v5.0/deviceState/list.json:
    get:
      summary: Device State List
      description: Device state list.
      operationId: getV5.0DevicestateList.json
      x-api-path-slug: v5-0devicestatelist-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: field.<field-name>.<qualifier>
      - in: query
        name: fieldNames
      - in: query
        name: isInAlarm
      - in: query
        name: notReportedSince
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Device
      - State
      - List
  /v5.0/deviceFeature/list.json:
    get:
      summary: Device Feature List
      description: Device feature list.
      operationId: getV5.0DevicefeatureList.json
      x-api-path-slug: v5-0devicefeaturelist-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: deviceTypeId
      - in: query
        name: deviceTypeKey
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: profileId
      - in: query
        name: showActive
      - in: query
        name: showAlarmConditionFields
      - in: query
        name: showDetails
      - in: query
        name: showEventReports
      - in: query
        name: showLastReportPropertyValues
      - in: query
        name: showLocationReports
      - in: query
        name: showMetaData
      - in: query
        name: showNotActive
      - in: query
        name: showNotVisible
      - in: query
        name: showStatusReports
      - in: query
        name: showVirtualCommands
      - in: query
        name: showVisible
      responses:
        200:
          description: OK
      tags:
      - Device
      - Feature
      - List
  /v5.0/deviceFeature/get.json:
    get:
      summary: Device Feature Get
      description: Device feature get.
      operationId: getV5.0DevicefeatureGet.json
      x-api-path-slug: v5-0devicefeatureget-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: id
      - in: query
        name: profileId
      responses:
        200:
          description: OK
      tags:
      - Device
      - Feature
  /v5.0/eventReport/list.json:
    get:
      summary: Event Report List
      description: Event report list.
      operationId: getV5.0EventreportList.json
      x-api-path-slug: v5-0eventreportlist-json-get
      parameters:
      - in: query
        name: ack
      - in: query
        name: atLeastLatest
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: eventType
      - in: query
        name: fromDate
      - in: query
        name: latestOnly
      - in: query
        name: maxAge
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: propertyName
      - in: query
        name: toDate
      responses:
        200:
          description: OK
      tags:
      - Event
      - Report
      - List
  /v5.0/eventReport/setAck.json:
    get:
      summary: Event Report Set Ack
      description: Event report set ack.
      operationId: getV5.0EventreportSetack.json
      x-api-path-slug: v5-0eventreportsetack-json-get
      parameters:
      - in: query
        name: ack
      - in: query
        name: reportIds
      responses:
        200:
          description: OK
      tags:
      - Event
      - Report
      - Set
      - Ack
  /v5.0/statusReport/list.json:
    get:
      summary: Status Report List
      description: Status report list.
      operationId: getV5.0StatusreportList.json
      x-api-path-slug: v5-0statusreportlist-json-get
      parameters:
      - in: query
        name: atLeastLatest
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: fromDate
      - in: query
        name: latestOnly
      - in: query
        name: maxAge
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: propertyName
      - in: query
        name: toDate
      responses:
        200:
          description: OK
      tags:
      - Status
      - Report
      - List
  /v5.0/campaign/get.json:
    get:
      summary: Campaign Get
      description: Campaign get.
      operationId: getV5.0CampaignGet.json
      x-api-path-slug: v5-0campaignget-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Campaign
  /v5.0/campaign/list.json:
    get:
      summary: Campaign List
      description: Campaign list.
      operationId: getV5.0CampaignList.json
      x-api-path-slug: v5-0campaignlist-json-get
      parameters:
      - in: query
        name: name
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: status
      responses:
        200:
          description: OK
      tags:
      - Campaign
      - List
  /v5.0/campaign/create.json:
    get:
      summary: Campaign Create
      description: Campaign create.
      operationId: getV5.0CampaignCreate.json
      x-api-path-slug: v5-0campaigncreate-json-get
      parameters:
      - in: query
        name: name
      - in: query
        name: virtualCommandKey
      - in: query
        name: virtualCommandParams
      responses:
        200:
          description: OK
      tags:
      - Campaign
      - Create
  /v5.0/campaign/update.json:
    get:
      summary: Campaign Update
      description: Campaign update.
      operationId: getV5.0CampaignUpdate.json
      x-api-path-slug: v5-0campaignupdate-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: name
      - in: query
        name: virtualCommandKey
      - in: query
        name: virtualCommandParams
      responses:
        200:
          description: OK
      tags:
      - Campaign
  /v5.0/campaign/schedule.json:
    get:
      summary: Campaign Schedule
      description: Campaign schedule.
      operationId: getV5.0CampaignSchedule.json
      x-api-path-slug: v5-0campaignschedule-json-get
      parameters:
      - in: query
        name: deliveryMethod
      - in: query
        name: id
      - in: query
        name: startTime
      responses:
        200:
          description: OK
      tags:
      - Campaign
      - Schedule
  /v5.0/campaign/cancel.json:
    get:
      summary: Campaign Cancel
      description: Campaign cancel.
      operationId: getV5.0CampaignCancel.json
      x-api-path-slug: v5-0campaigncancel-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Campaign
      - Cancel
  /v5.0/campaign/delete.json:
    get:
      summary: Campaign Delete
      description: Campaign delete.
      operationId: getV5.0CampaignDelete.json
      x-api-path-slug: v5-0campaigndelete-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Campaign
  /v5.0/subOrganization/create.json:
    get:
      summary: Sub Organization Create
      description: Sub organization create.
      operationId: getV5.0SuborganizationCreate.json
      x-api-path-slug: v5-0suborganizationcreate-json-get
      parameters:
      - in: query
        name: name
      - in: query
        name: secret
      - in: query
        name: userName
      responses:
        200:
          description: OK
      tags:
      - Sub
      - Organization
      - Create
  /v5.0/subOrganization/update.json:
    get:
      summary: Sub Organization Update
      description: Sub organization update.
      operationId: getV5.0SuborganizationUpdate.json
      x-api-path-slug: v5-0suborganizationupdate-json-get
      parameters:
      - in: query
        name: key
      - in: query
        name: name
      - in: query
        name: secret
      responses:
        200:
          description: OK
      tags:
      - Sub
      - Organization
  /v5.0/subOrganization/showHierarchy.json:
    get:
      summary: Sub Organization Show Hierarchy
      description: Sub organization show hierarchy.
      operationId: getV5.0SuborganizationShowhierarchy.json
      x-api-path-slug: v5-0suborganizationshowhierarchy-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: key
      responses:
        200:
          description: OK
      tags:
      - Sub
      - Organization
      - Show
      - Hierarchy
  /v5.0/subOrganization/retire.json:
    get:
      summary: Sub Organization Retire
      description: Sub organization retire.
      operationId: getV5.0SuborganizationRetire.json
      x-api-path-slug: v5-0suborganizationretire-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: key
      responses:
        200:
          description: OK
      tags:
      - Sub
      - Organization
      - Retire
  /v5.0/geofence/create.json:
    get:
      summary: Geofence Create
      description: Geofence create.
      operationId: getV5.0GeofenceCreate.json
      x-api-path-slug: v5-0geofencecreate-json-get
      parameters:
      - in: query
        name: groupId
      - in: query
        name: name
      - in: query
        name: points
      - in: query
        name: properties
      - in: query
        name: radius
      - in: query
        name: type
      - in: query
        name: width
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Create
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