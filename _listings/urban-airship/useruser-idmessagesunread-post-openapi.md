---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Post User User Messages Unread
  description: Marks multiple messages as read at once. If a message has already been
    marked as read, it will be silently skipped.
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/{user_id}/messages/unread:
    get:
      summary: Get User User Messages Unread
      description: Returns a list of unread message IDs and their URLs.
      operationId: user.user_id.messages.unread.get
      x-api-path-slug: useruser-idmessagesunread-get
      parameters:
      - in: query
        name: user_id
        description: The user ID
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - User
      - User
      - Id
      - Messages
      - Unread
    post:
      summary: Post User User Messages Unread
      description: Marks multiple messages as read at once. If a message has already
        been marked as read, it will be silently skipped.
      operationId: user.user_id.messages.unread.post
      x-api-path-slug: useruser-idmessagesunread-post
      parameters:
      - in: header
        name: Content-Type
        description: Content type
      - in: query
        name: Content-Type
        description: Content type
      - in: query
        name: user_id
        description: The user ID
      - in: path
        name: user_id
      responses:
        200:
          description: OK
      tags:
      - User
      - User
      - Id
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