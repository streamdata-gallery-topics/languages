---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Translation Hub Languages that SAP Translation Hub supports.
  description: Returns a list of the languages that SAP Translation Hub supports.
    You can also check whether a particualr language is available in SAP Translation
    Hub.
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /languages:
    get:
      summary: Languages that SAP Translation Hub supports.
      description: Returns a list of the languages that SAP Translation Hub supports.
        You can also check whether a particualr language is available in SAP Translation
        Hub.
      operationId: returns-a-list-of-the-languages-that-sap-translation-hub-supports-you-can-also-check-whether-a-parti
      x-api-path-slug: languages-get
      parameters:
      - in: header
        name: Content-Type
        description: Specifies the nature of the data in the body so that the receiving
          agent can process the data accordingly
      - in: query
        name: search
        description: Determines whether a particular language is available in SAP
          Translation Hub
      responses:
        200:
          description: Successful response
      tags:
      - Languages
      - That
      - SAP
      - Translation
      - Hub
      - Supports
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