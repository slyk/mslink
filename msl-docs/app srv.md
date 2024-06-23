---
aliases:
  - srv
  - srv app
---
srv (nestjs) ^7fc770

Server side [[nestjs]] app used for additional functions.
For database working mainly [[directus]] is used.
This app connects to [[directus]] to make writes to db and direct connect to [[mysql]] when need to fast read data (read-only access).