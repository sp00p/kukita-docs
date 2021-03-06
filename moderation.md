# Moderation

This module contains the commands that are supported by Kukita Bot to help moderate your server

**Required Permissions is not explicit. The permission handler will simply check if the user has any of the permissions listed. They can be found under each role in your discord server settings.**

## WarnClear

Usage: `.clearwarns <user>`

Required Permissions: `KICK_MEMBERS, ADMINISTRATOR`

This command clears all warns for a user in your guild.

## Ban

Usage: `.ban <user> [reason]`

Required Permissions: `BAN_MEMBERS, ADMINISTRATOR`

This command will ban the specified user and DM them an embed with the information about their removal from the server. A reason is optional and will send "Not Specified" if no reason is given.

## Kick

Usage: `.kick <user> [reason]`

Required Permissions: `KICK_MEMBERS, ADMINISTRATOR`

This command will ban the specified user and DM them an embed with the information about their removal from the server. A reason is optional and will send "Not Specified" if no reason is given.

## Mute

Usage: `.mute <user> [reason]`

Required Permissions: `MUTE_MEMBERS, ADMINISTRATOR`

This command will mute the specified user and DM them an embed with the information about their mute. A reason is optional and will send "Not Specified" if no reason is given.

Note: You must have a role with the name of "Muted" although I plan to make it more customizable in the future.

## Purge

Usage: `.purge <number of messages>`

Required Permissions: `MANAGE_MESSAGES, ADMINISTRATOR`

This command can purge up to 100 messages at a time that are newer than 14 days old. Kukita Bot will send you a message after all of the possible messages are deleted.

## ResetChannel

Usage: `.resetchannel`

Required Permissions:`ADMINISTRATOR`

This command will cause the channel you are resetting, along with all the messages within that channel to be deleted. The channel will then be duplicated and will have all the same role permissions as it did just without the messages.

## Roleban

Usage: `.roleban <rolename>`

Required Permissions: `ADMINISTRATOR`

This command will ban all the the users in your guild with the given role.

## Rolekick

Usage: `.rolekick <rolename>`

Required Permissions: `ADMINISTRATOR`

This command will kick all the users in your guild with the given role.

## Slowmode

Usage: `.slowmode <time>`

Required Permissions: `MANAGE_CHANNELS, ADMINISTRATOR`

This command changes the slowmode setting for the channel it's sent in. Great for stopping raids.

## VCKick

Usage: `.vckick <user> [reason]`

Required Permissions: `KICK_MEMBERS, ADMINISTRATOR`

This command will kick the specified user out of their current voice channel.

## Warn

Usage: `.warn <user>`

Required Permissions: `KICK_MEMBERS, ADMINISTRATOR`

This command will warn the specified user. It's then stored in a database that can be accessed if you want to keep track of warns. It also stores your guildID so there won't be any issues with your guild being interfered with.

Note: You must have a role with the name of "Muted" for the user to be muted. In the future I'll make it more customizable.

## Warns

Usage: `.warns <user>`

This command will display the warns for the specified user in the current server

## Coming Soon

* Kick when user reaches a certain amount of warns

