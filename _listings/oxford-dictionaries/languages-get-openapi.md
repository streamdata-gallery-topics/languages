---
swagger: "2.0"
x-collection-name: Oxford Dictionaries
x-complete: 0
info:
  title: Oxford Dictionaries Lists available dictionaries
  description: Returns a list of monolingual and bilingual language datasets available
    in the API
  termsOfService: http://helloreverb.com/terms/
  version: 1.8.0
host: od-api-demo.oxforddictionaries.com:443
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /languages:
    get:
      summary: Lists available dictionaries
      description: Returns a list of monolingual and bilingual language datasets available
        in the API
      operationId: getLanguages
      x-api-path-slug: languages-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: sourceLanguage
        description: IANA language code
      - in: query
        name: targetLanguage
        description: IANA language code
      responses:
        200:
          description: OK
      tags:
      - Languages
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