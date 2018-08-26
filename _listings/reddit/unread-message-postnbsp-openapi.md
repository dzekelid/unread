---
swagger: "2.0"
x-collection-name: Reddit
x-complete: 0
info:
  title: Reddit Add Unread Message
  description: A comma-separated list of thing fullnames
  version: 1.0.0
host: www.reddit.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /unread_message:
    post&nbsp;:
      summary: Add Unread Message
      description: A comma-separated list of thing fullnames
      operationId: post&nbsp;UnreadMessage
      x-api-path-slug: unread-message-postnbsp
      parameters:
      - in: query
        name: id
        description: A comma-separated list of thing fullnames
        type: string
      - in: query
        name: uh / X-Modhash header
        description: a modhash
        type: string
      responses:
        200:
          description: OK
      tags:
      - Unread
      - Message
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