---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: Unread
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Reference - Get unread messages
  x-api-slug: usersuser-idchannelschannel-idunread-get
  description: |-
    Get the total unread messages and mentions for a channel for a user.
    ##### Permissions
    Must be logged in as user and have the `read_channel` permission, or have `edit_other_usrs` permission.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idchannelschannel-idunread-get-openapi.md
- name: Mattermost API Reference - Get team unreads for a user
  x-api-slug: usersuser-idteamsunread-get
  description: |-
    Get the count for unread messages and mentions in the teams the user is a member of.
    ##### Permissions
    Must be logged in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idteamsunread-get-openapi.md
- name: Mattermost API Reference - Get unreads for a team
  x-api-slug: usersuser-idteamsteam-idunread-get
  description: |-
    Get the unread mention and message counts for a team for the specified user.
    ##### Permissions
    Must be the user or have `edit_other_users` permission and have `view_team` permission for the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idteamsteam-idunread-get-openapi.md
- name: Mattermost API Reference - Get team unreads for a user
  x-api-slug: usersuser-idteamsunread-get
  description: |-
    Get the count for unread messages and mentions in the teams the user is a member of.
    ##### Permissions
    Must be logged in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idteamsunread-get-openapi.md
- name: Mattermost API Reference - Get unreads for a team
  x-api-slug: usersuser-idteamsteam-idunread-get
  description: |-
    Get the unread mention and message counts for a team for the specified user.
    ##### Permissions
    Must be the user or have `edit_other_users` permission and have `view_team` permission for the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idteamsteam-idunread-get-openapi.md
- name: Mattermost API Reference - Get unreads for a team
  x-api-slug: usersuser-idteamsteam-idunread-get
  description: |-
    Get the unread mention and message counts for a team for the specified user.
    ##### Permissions
    Must be the user or have `edit_other_users` permission and have `view_team` permission for the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idteamsteam-idunread-get-openapi.md
- name: Mattermost API Reference - Get team unreads for a user
  x-api-slug: usersuser-idteamsunread-get
  description: |-
    Get the count for unread messages and mentions in the teams the user is a member of.
    ##### Permissions
    Must be logged in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/unread/master/_listings/mattermost/usersuser-idteamsunread-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://matrix.api.gallery.streamdata.io
- type: x-api-stack
  url: http://mattermost.stack.network
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---