---
title: Create Guild Integration
category: Guild
order: 29
---

# `createGuildIntegration`

```php
$client->guild->createGuildIntegration($parameters);
```

## Description

Attach an integration object from the current user to the guild. Requires the &#039;MANAGE_GUILD&#039; permission.  Fires a Guild Integrations Update Gateway event.

## Parameters


Name | Type | Required | Default
--- | --- | --- | ---
type | string | false | *null*
id | snowflake | false | *null*
guild.id | snowflake | true | *null*

## Response

Returns a 204 empty response on success.

