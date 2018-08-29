---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 0
info:
  title: AWS Elastic Beanstalk API Abort Environment Update
  version: 1.0.0
  description: |-
    Cancels in-progress environment configuration update or application version
          deployment.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AbortEnvironmentUpdate:
    get:
      summary: Abort Environment Update
      description: |-
        Cancels in-progress environment configuration update or application version
              deployment.
      operationId: abortEnvironmentUpdate
      x-api-path-slug: actionabortenvironmentupdate-get
      parameters:
      - in: query
        name: EnvironmentId
        description: This specifies the ID of the environment with the in-progress
          update that you want to      cancel
        type: string
      - in: query
        name: EnvironmentName
        description: This specifies the name of the environment with the in-progress
          update that you want to      cancel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
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