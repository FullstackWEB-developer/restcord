---
title: Create Guild Ban
category: Guild
order: 17
---

# `createGuildBan`

```php
$client->guild->createGuildBan($parameters);
```

## Description

Create a guild ban, and optionally delete previous messages sent by the banned user. Requires the &#039;BAN_MEMBERS&#039; permission.  Fires a Guild Ban Add Gateway event.

## Parameters


Name | Type | Required | Default
--- | --- | --- | ---
delete-message-days | integer | false | *null*
guild.id | snowflake | 1 | *null*
user.id | snowflake | 1 | *null*

## Response

Returns a 204 empty response on success.

