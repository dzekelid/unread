---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 1
info:
  title: Urban Airship
  description: the-urban-airships-api-powers-mobile-applications-with-push-rich-push-inapp-purchases-and-subscription-services-
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
---