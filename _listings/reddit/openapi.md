swagger: "2.0"
x-collection-name: Reddit
x-complete: 1
info:
  title: Reddit
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