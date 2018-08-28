---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Get team unreads for a user
  description: |-
    Get the count for unread messages and mentions in the teams the user is a member of.
    ##### Permissions
    Must be logged in.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/channels/{channel_id}/unread:
    get:
      summary: Get unread messages
      description: |-
        Get the total unread messages and mentions for a channel for a user.
        ##### Permissions
        Must be logged in as user and have the `read_channel` permission, or have `edit_other_usrs` permission.
      operationId: get-the-total-unread-messages-and-mentions-for-a-channel-for-a-user-permissionsmust-be-logged-in-as-
      x-api-path-slug: usersuser-idchannelschannel-idunread-get
      parameters:
      - in: path
        name: channel_id
        description: Channel GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Unread
      - Messages
  /users/{user_id}/teams/unread:
    get:
      summary: Get team unreads for a user
      description: |-
        Get the count for unread messages and mentions in the teams the user is a member of.
        ##### Permissions
        Must be logged in.
      operationId: get-the-count-for-unread-messages-and-mentions-in-the-teams-the-user-is-a-member-of-permissionsmust-
      x-api-path-slug: usersuser-idteamsunread-get
      parameters:
      - in: query
        name: exclude_team
        description: Optional team id to be excluded from the results
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Team
      - Unreadsa
      - User
  /users/{user_id}/teams/{team_id}/unread:
    get:
      summary: Get unreads for a team
      description: |-
        Get the unread mention and message counts for a team for the specified user.
        ##### Permissions
        Must be the user or have `edit_other_users` permission and have `view_team` permission for the team.
      operationId: get-the-unread-mention-and-message-counts-for-a-team-for-the-specified-user-permissionsmust-be-the-u
      x-api-path-slug: usersuser-idteamsteam-idunread-get
      parameters:
      - in: path
        name: team_id
        description: Team GUID
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - Unreadsa
      - Team
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