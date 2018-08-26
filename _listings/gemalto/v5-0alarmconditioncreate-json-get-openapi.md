---
swagger: "2.0"
x-collection-name: Gemalto
x-complete: 0
info:
  title: Gemalto IoT Application Enablement Platform API Alarm Condition Create
  description: Alarm condition create.
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
  /v5.0/geofence/get.json:
    get:
      summary: Geofence Get
      description: Geofence get.
      operationId: getV5.0GeofenceGet.json
      x-api-path-slug: v5-0geofenceget-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
  /v5.0/geofence/list.json:
    get:
      summary: Geofence List
      description: Geofence list.
      operationId: getV5.0GeofenceList.json
      x-api-path-slug: v5-0geofencelist-json-get
      parameters:
      - in: query
        name: groupId
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - List
  /v5.0/geofence/update.json:
    get:
      summary: Geofence Update
      description: Geofence update.
      operationId: getV5.0GeofenceUpdate.json
      x-api-path-slug: v5-0geofenceupdate-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: points
      - in: query
        name: properties
      - in: query
        name: radius
      - in: query
        name: width
      responses:
        200:
          description: OK
      tags:
      - Geofence
  /v5.0/geofence/delete.json:
    get:
      summary: Geofence Delete
      description: Geofence delete.
      operationId: getV5.0GeofenceDelete.json
      x-api-path-slug: v5-0geofencedelete-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
  /v5.0/networkProvisioning/getDeviceInfo.json:
    get:
      summary: Network Provisioning Get Device Info
      description: Network provisioning get device info.
      operationId: getV5.0NetworkprovisioningGetdeviceinfo.json
      x-api-path-slug: v5-0networkprovisioninggetdeviceinfo-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      responses:
        200:
          description: OK
      tags:
      - Network
      - Provisioning
      - ""
      - Device
      - Info
  /v5.0/networkProvisioning/getActivationCodes.json:
    get:
      summary: Network Provisioning Get Activation Codes
      description: Network provisioning get activation codes.
      operationId: getV5.0NetworkprovisioningGetactivationcodes.json
      x-api-path-slug: v5-0networkprovisioninggetactivationcodes-json-get
      responses:
        200:
          description: OK
      tags:
      - Network
      - Provisioning
      - ""
      - Activation
      - Codes
  /v5.0/networkProvisioning/activate.json:
    get:
      summary: Network Provisioning Activate
      description: Network provisioning activate.
      operationId: getV5.0NetworkprovisioningActivate.json
      x-api-path-slug: v5-0networkprovisioningactivate-json-get
      parameters:
      - in: query
        name: activationCode
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      responses:
        200:
          description: OK
      tags:
      - Network
      - Provisioning
      - Activate
  /v5.0/networkProvisioning/deactivate.json:
    get:
      summary: Network Provisioning Deactivate
      description: Network provisioning deactivate.
      operationId: getV5.0NetworkprovisioningDeactivate.json
      x-api-path-slug: v5-0networkprovisioningdeactivate-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      responses:
        200:
          description: OK
      tags:
      - Network
      - Provisioning
      - Deactivate
  /v5.0/deviceGroup/create.json:
    get:
      summary: Device Group Create
      description: Device group create.
      operationId: getV5.0DevicegroupCreate.json
      x-api-path-slug: v5-0devicegroupcreate-json-get
      parameters:
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Device
      - Group
      - Create
  /v5.0/deviceGroup/get.json:
    get:
      summary: Device Group Get
      description: Device group get.
      operationId: getV5.0DevicegroupGet.json
      x-api-path-slug: v5-0devicegroupget-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Device
      - Group
  /v5.0/deviceGroup/list.json:
    get:
      summary: Device Group List
      description: Device group list.
      operationId: getV5.0DevicegroupList.json
      x-api-path-slug: v5-0devicegrouplist-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Device
      - Group
      - List
  /v5.0/deviceGroup/update.json:
    get:
      summary: Device Group Update
      description: Device group update.
      operationId: getV5.0DevicegroupUpdate.json
      x-api-path-slug: v5-0devicegroupupdate-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Device
      - Group
  /v5.0/deviceGroup/delete.json:
    get:
      summary: Device Group Delete
      description: Device group delete.
      operationId: getV5.0DevicegroupDelete.json
      x-api-path-slug: v5-0devicegroupdelete-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Device
      - Group
  /v5.0/network/list.json:
    get:
      summary: Network List
      description: Network list.
      operationId: getV5.0NetworkList.json
      x-api-path-slug: v5-0networklist-json-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
  /v5.0/network/get.json:
    get:
      summary: Network Get
      description: Network get.
      operationId: getV5.0NetworkGet.json
      x-api-path-slug: v5-0networkget-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: key
      responses:
        200:
          description: OK
      tags:
      - Network
  /v5.0/geofenceGroup/create.json:
    get:
      summary: Geofence Group Create
      description: Geofence group create.
      operationId: getV5.0GeofencegroupCreate.json
      x-api-path-slug: v5-0geofencegroupcreate-json-get
      parameters:
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Group
      - Create
  /v5.0/geofenceGroup/get.json:
    get:
      summary: Geofence Group Get
      description: Geofence group get.
      operationId: getV5.0GeofencegroupGet.json
      x-api-path-slug: v5-0geofencegroupget-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Group
  /v5.0/geofenceGroup/list.json:
    get:
      summary: Geofence Group List
      description: Geofence group list.
      operationId: getV5.0GeofencegroupList.json
      x-api-path-slug: v5-0geofencegrouplist-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Group
      - List
  /v5.0/geofenceGroup/update.json:
    get:
      summary: Geofence Group Update
      description: Geofence group update.
      operationId: getV5.0GeofencegroupUpdate.json
      x-api-path-slug: v5-0geofencegroupupdate-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Group
  /v5.0/geofenceGroup/delete.json:
    get:
      summary: Geofence Group Delete
      description: Geofence group delete.
      operationId: getV5.0GeofencegroupDelete.json
      x-api-path-slug: v5-0geofencegroupdelete-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Group
  /v5.0/geofenceCondition/list.json:
    get:
      summary: Geofence Condition List
      description: Geofence condition list.
      operationId: getV5.0GeofenceconditionList.json
      x-api-path-slug: v5-0geofenceconditionlist-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: geofenceId
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Condition
      - List
  /v5.0/geofenceCondition/get.json:
    get:
      summary: Geofence Condition Get
      description: Geofence condition get.
      operationId: getV5.0GeofenceconditionGet.json
      x-api-path-slug: v5-0geofenceconditionget-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Condition
  /v5.0/geofenceCondition/create.json:
    get:
      summary: Geofence Condition Create
      description: Geofence condition create.
      operationId: getV5.0GeofenceconditionCreate.json
      x-api-path-slug: v5-0geofenceconditioncreate-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: endTime
      - in: query
        name: firstOnly
      - in: query
        name: geofenceId
      - in: query
        name: groupId
      - in: query
        name: isInside
      - in: query
        name: isOutside
      - in: query
        name: justCrossed
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Condition
      - Create
  /v5.0/geofenceCondition/update.json:
    get:
      summary: Geofence Condition Update
      description: Geofence condition update.
      operationId: getV5.0GeofenceconditionUpdate.json
      x-api-path-slug: v5-0geofenceconditionupdate-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: endTime
      - in: query
        name: firstOnly
      - in: query
        name: geofenceId
      - in: query
        name: groupId
      - in: query
        name: id
      - in: query
        name: isInside
      - in: query
        name: isOutside
      - in: query
        name: justCrossed
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Condition
  /v5.0/geofenceCondition/delete.json:
    get:
      summary: Geofence Condition Delete
      description: Geofence condition delete.
      operationId: getV5.0GeofenceconditionDelete.json
      x-api-path-slug: v5-0geofenceconditiondelete-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: geofenceId
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Condition
  /v5.0/outboundCommand/list.json:
    get:
      summary: Outbound Command List
      description: Outbound command list.
      operationId: getV5.0OutboundcommandList.json
      x-api-path-slug: v5-0outboundcommandlist-json-get
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
        name: toDate
      responses:
        200:
          description: OK
      tags:
      - Outbound
      - Command
      - List
  /v5.0/deviceType/list.json:
    get:
      summary: Device Type List
      description: Device type list.
      operationId: getV5.0DevicetypeList.json
      x-api-path-slug: v5-0devicetypelist-json-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: showOnlyInUse
      responses:
        200:
          description: OK
      tags:
      - Device
      - Type
      - List
  /v5.0/deviceType/get.json:
    get:
      summary: Device Type Get
      description: Device type get.
      operationId: getV5.0DevicetypeGet.json
      x-api-path-slug: v5-0devicetypeget-json-get
      parameters:
      - in: query
        name: id
      - in: query
        name: key
      responses:
        200:
          description: OK
      tags:
      - Device
      - Type
  /v5.0/reportBatch/purge.json:
    get:
      summary: Report Batch Purge
      description: Report batch purge.
      operationId: getV5.0ReportbatchPurge.json
      x-api-path-slug: v5-0reportbatchpurge-json-get
      parameters:
      - in: query
        name: archive
      - in: query
        name: toDate
      responses:
        200:
          description: OK
      tags:
      - Report
      - Batch
      - Purge
  /v5.0/reportBatch/download.json:
    get:
      summary: Report Batch Download
      description: Report batch download.
      operationId: getV5.0ReportbatchDownload.json
      x-api-path-slug: v5-0reportbatchdownload-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Report
      - Batch
      - Download
  /v5.0/reportBatch/stop.json:
    get:
      summary: Report Batch Stop
      description: Report batch stop.
      operationId: getV5.0ReportbatchStop.json
      x-api-path-slug: v5-0reportbatchstop-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Report
      - Batch
      - Stop
  /v5.0/reportBatch/status.json:
    get:
      summary: Report Batch Status
      description: Report batch status.
      operationId: getV5.0ReportbatchStatus.json
      x-api-path-slug: v5-0reportbatchstatus-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Report
      - Batch
      - Status
  /v5.0/reportBatch/list.json:
    get:
      summary: Report Batch List
      description: Report batch list.
      operationId: getV5.0ReportbatchList.json
      x-api-path-slug: v5-0reportbatchlist-json-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Report
      - Batch
      - List
  /v5.0/reportStat/list.json:
    get:
      summary: Report Stat List
      description: Report stat list.
      operationId: getV5.0ReportstatList.json
      x-api-path-slug: v5-0reportstatlist-json-get
      parameters:
      - in: query
        name: fromDate
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: reportType
      - in: query
        name: showDetails
      - in: query
        name: toDate
      responses:
        200:
          description: OK
      tags:
      - Report
      - Stat
      - List
  /v5.0/deviceProperty/get.json:
    get:
      summary: Device Property Get
      description: Device property get.
      operationId: getV5.0DevicepropertyGet.json
      x-api-path-slug: v5-0devicepropertyget-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Device
      - Property
  /v5.0/deviceProperty/set.json:
    get:
      summary: Device Property Set
      description: Device property set.
      operationId: getV5.0DevicepropertySet.json
      x-api-path-slug: v5-0devicepropertyset-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: name
      - in: query
        name: value
      responses:
        200:
          description: OK
      tags:
      - Device
      - Property
      - Set
  /v5.0/deviceProperty/delete.json:
    get:
      summary: Device Property Delete
      description: Device property delete.
      operationId: getV5.0DevicepropertyDelete.json
      x-api-path-slug: v5-0devicepropertydelete-json-get
      parameters:
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: name
      responses:
        200:
          description: OK
      tags:
      - Device
      - Property
  /v5.0/deviceBatch/status.json:
    get:
      summary: Device Batch Status
      description: Device batch status.
      operationId: getV5.0DevicebatchStatus.json
      x-api-path-slug: v5-0devicebatchstatus-json-get
      parameters:
      - in: query
        name: transactionId
      responses:
        200:
          description: OK
      tags:
      - Device
      - Batch
      - Status
  /v5.0/user/list.json:
    get:
      summary: User List
      description: User list.
      operationId: getV5.0UserList.json
      x-api-path-slug: v5-0userlist-json-get
      parameters:
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: subOrgKey
      responses:
        200:
          description: OK
      tags:
      - User
      - List
  /v5.0/campaignTarget/list.json:
    get:
      summary: Campaign Target List
      description: Campaign target list.
      operationId: getV5.0CampaigntargetList.json
      x-api-path-slug: v5-0campaigntargetlist-json-get
      parameters:
      - in: query
        name: campaignId
      - in: query
        name: isSupported
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
      - Target
      - List
  /v5.0/campaignTarget/create.json:
    get:
      summary: Campaign Target Create
      description: Campaign target create.
      operationId: getV5.0CampaigntargetCreate.json
      x-api-path-slug: v5-0campaigntargetcreate-json-get
      parameters:
      - in: query
        name: campaignId
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      responses:
        200:
          description: OK
      tags:
      - Campaign
      - Target
      - Create
  /v5.0/campaignTarget/delete.json:
    get:
      summary: Campaign Target Delete
      description: Campaign target delete.
      operationId: getV5.0CampaigntargetDelete.json
      x-api-path-slug: v5-0campaigntargetdelete-json-get
      parameters:
      - in: query
        name: campaignId
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      responses:
        200:
          description: OK
      tags:
      - Campaign
      - Target
  /v5.0/geofenceMembership/list.json:
    get:
      summary: Geofence Membership List
      description: Geofence membership list.
      operationId: getV5.0GeofencemembershipList.json
      x-api-path-slug: v5-0geofencemembershiplist-json-get
      parameters:
      - in: query
        name: geofenceId
      - in: query
        name: groupId
      - in: query
        name: groupIdNot
      - in: query
        name: membersOnly
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Membership
      - List
  /v5.0/geofenceMembership/create.json:
    get:
      summary: Geofence Membership Create
      description: Geofence membership create.
      operationId: getV5.0GeofencemembershipCreate.json
      x-api-path-slug: v5-0geofencemembershipcreate-json-get
      parameters:
      - in: query
        name: geofenceId
      - in: query
        name: groupId
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Membership
      - Create
  /v5.0/geofenceMembership/delete.json:
    get:
      summary: Geofence Membership Delete
      description: Geofence membership delete.
      operationId: getV5.0GeofencemembershipDelete.json
      x-api-path-slug: v5-0geofencemembershipdelete-json-get
      parameters:
      - in: query
        name: geofenceId
      - in: query
        name: groupId
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Geofence
      - Membership
  /v5.0/alarmCondition/list.json:
    get:
      summary: Alarm Condition List
      description: Alarm condition list.
      operationId: getV5.0AlarmconditionList.json
      x-api-path-slug: v5-0alarmconditionlist-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: deviceTypeKey
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      responses:
        200:
          description: OK
      tags:
      - Alarm
      - Condition
      - List
  /v5.0/alarmCondition/get.json:
    get:
      summary: Alarm Condition Get
      description: Alarm condition get.
      operationId: getV5.0AlarmconditionGet.json
      x-api-path-slug: v5-0alarmconditionget-json-get
      parameters:
      - in: query
        name: id
      responses:
        200:
          description: OK
      tags:
      - Alarm
      - Condition
  /v5.0/alarmCondition/create.json:
    get:
      summary: Alarm Condition Create
      description: Alarm condition create.
      operationId: getV5.0AlarmconditionCreate.json
      x-api-path-slug: v5-0alarmconditioncreate-json-get
      parameters:
      - in: query
        name: deviceGroupId
      - in: query
        name: deviceHandle
      - in: query
        name: deviceId
      - in: query
        name: deviceTypeKey
      - in: query
        name: hasntReportedForSeconds
      - in: query
        name: isEnabled
      - in: query
        name: name
      - in: query
        name: topic
      responses:
        200:
          description: OK
      tags:
      - Alarm
      - Condition
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