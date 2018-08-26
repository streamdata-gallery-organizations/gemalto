---
swagger: "2.0"
x-collection-name: Gemalto
x-complete: 0
info:
  title: Gemalto IoT Application Enablement Platform API Tools Time
  description: Tools time.
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