# Utility

This module contains the commands that are supported by Kukita Bot to provide you with more info about users and your server.

## BotInfo

Usage: `.botinfo`

This command will send an embed with some information about the bot in the channel you're currently in.

**Command Change**

* ChangeRole -&gt; Role Create/Role Delete
* Use \_'s as spaces!

## Role Create

Usage: `.role create <role name> <hex color>`

Required Permissions: `MANAGE_ROLES, ADMINISTRATOR`

This command will create a role with the given role name.

## Role Delete

Usage: \`.role delete

Required Permissions: `MANAGE_ROLES, ADMINISTRATOR`

This command will delete the specified role

## Help

Usage: `.help`

This command will DM you an embed that includes all the commands in these documents.

## Info

Usage: `.info <user>`

This command returns an embed with info about the mentioned user such as their TTS Status, whether they're a priority speaker or not, their ability to mention everyone, ect.

## InviteMe

Usage: `.inviteme`

This command will DM you the OAuth link to invite the bot to your server.

## Ping

Usage: `.ping`

This command will send an embed with the bot latency and API Latency.

## ServerInfo

Usage: `.serverinfo`

This command will send information about your server such as member presences, voice region, and nitro level.

**Credit to applebee\#3071 for this command idea and its features!**

## Uptime

Usage: `.uptime`

This command will send an embed that displays how long Kukita Bot has been running.

## ServerEmojis

Usage: `.serveremojis`

This command will send an embed with a list of the static and animated emojis of your current guild.

## Prefix

Usage: `.prefix <new prefix>`

This command allows you to set a custom prefix for the bot in your guild.

