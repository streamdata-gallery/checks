---
swagger: "2.0"
x-collection-name: Pingdom
x-complete: 0
info:
  title: Checks API Get Check
  description: Gets info about a check, current SLA, last result and its status.
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.pingdom.com
basePath: /
paths:
  '/checks ':
    ' get ':
      summary: Get Checks
      description: Gets a list of all checks that are visible to you as a user or
        a customer depending on the request context.
      operationId: getChecks
      x-api-path-slug: checks-get
      responses:
        200:
          description: OK
      tags:
      - Checks
  '/checks/{checkId} ':
    ' get ':
      summary: Get Check
      description: Gets info about a check, current SLA, last result and its status.
      operationId: getChecksCheck
      x-api-path-slug: checkscheckid-get
      responses:
        200:
          description: OK
      tags:
      - Checks
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