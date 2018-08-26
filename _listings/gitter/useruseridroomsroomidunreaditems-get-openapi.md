---
swagger: "2.0"
x-collection-name: Gitter
x-complete: 0
info:
  title: Gitter API Get User Unread Items
  version: 1.0.0
  description: You can retrieve unread items and mentions using the following endpoint.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/:userId/rooms/:roomId/unreadItems:
    get:
      summary: Get User Unread Items
      description: You can retrieve unread items and mentions using the following
        endpoint.
      operationId: getUserUnreadItems
      x-api-path-slug: useruseridroomsroomidunreaditems-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Messages
      - Unread
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