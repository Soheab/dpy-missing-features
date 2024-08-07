# Features

This page contains all the features that the API supports and may get added on discord.py.
These are divided in different categories depending on the object or concept they affect.

# Contents Index

[Interactions](#interactions)
  - [Application Commands](#application-commands)

[Resources](#resources)
  - [Application](#application)
  - [Guild](#guild)
  - [Guild Scheduled Event](#guild-scheduled-event)
  - [Invite](#invite)
  - [Message](#message)
  - [Webhook](#webhook)

---

## Interactions

### Application Commands

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Fetch Localised Application Commands | Support for getting the localisation data when fetching application commands | Not Released | | [GH-9452](https://github.com/Rapptz/discord.py/pull/9452) | |

---

## Resources

### Application

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Application Emojis | Support for getting, editing, deleting and other various methods for application based emojis | Not Released | [GH-7010](https://github.com/discord/discord-api-docs/pull/7010) | [GH-9891](https://github.com/Rapptz/discord.py/pull/9891) | |
| Application Integration Types | Support for getting and editing application integration types | Not Released | | [GH-9818](https://github.com/Rapptz/discord.py/pull/9818) | Also see this [bikeshedding post](https://canary.discord.com/channels/336642139381301249/1236782377980657836) in discord.py's server |
| Modify Application Fields | Add & Update multiple attributes for the AppInfo object | Not Released | [GH-6484](https://github.com/discord/discord-api-docs/pull/6484) | | Also see this [bikeshedding post](https://canary.discord.com/channels/336642139381301249/1236550182791942186) in discord.py's server |

### Guild

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Clans | New guild type, new fields, new objects and other various things | Not Released | [GH-6836](https://github.com/discord/discord-api-docs/pull/6836) | [GH-9899](https://github.com/Rapptz/discord.py/pull/9899) | |
| Get Guild Previews | Allows getting guild previews | Not Released | | [GH-2642](https://github.com/Rapptz/discord.py/pull/2642) | |
| Guild Incidents Data | Adds new safety related fields to guild | Not Released | [GH-6396](https://github.com/discord/discord-api-docs/pull/6396) | [GH-9808](https://github.com/Rapptz/discord.py/pull/9808) | |
| Onboarding | Support for getting, editing, deleting and other various methods related to guild onboarding | Not Released | [GH-5915](https://github.com/discord/discord-api-docs/pull/5915) | [GH-9260](https://github.com/Rapptz/discord.py/pull/9260) | |
| Various Parameters For `Guild.create_guild` | Adds support for passing more parameters to `Guild.create_guild` | Not Released | | | This has no PR, you can follow the discussion in the [discord.py's bikeshedding post](https://discord.com/channels/336642139381301249/1084586605928517662) |

### Guild Scheduled Event

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Scheduled Event Recurrence | Support for creating and editing recurrence rule on scheduled events | Not Released | [GH-7058](https://github.com/discord/discord-api-docs/pull/7058) | [GH-9685](https://github.com/Rapptz/discord.py/pull/9685) | |

### Invite

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Guest Invites | Adds support for guest invites | Not Released | [GH-6247](https://github.com/discord/discord-api-docs/pull/6247) | [GH-9476](https://github.com/Rapptz/discord.py/pull/9476) | |
| Invite Flags | Adds new invite flags | Released in version 2.4 | [GH-6568](https://github.com/discord/discord-api-docs/pull/6568) | [GH-9682](https://github.com/Rapptz/discord.py/pull/9682) | |

### Message

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Attachment Title | Allows getting message attachments' titles | Not Released | [GH-6945](https://github.com/discord/discord-api-docs/pull/6945) | [GH-9904](https://github.com/Rapptz/discord.py/pull/9904) | |
| Forwarding | Message reference type and field on messages with new message snapshots | Not Released | [GH-6833](https://github.com/discord/discord-api-docs/pull/6833) | [GH-9892](https://github.com/Rapptz/discord.py/pull/9892) | |
| `POLL_RESULT` Type  | Message type and field on messages with finished polls | Not Released | [GH-7050](https://github.com/discord/discord-api-docs/pull/7050) | [GH-9905](https://github.com/Rapptz/discord.py/pull/9905) | |
| `PURCHASE_NOTIFICATION` Type | Message type | Not Released | [GH-6927](https://github.com/discord/discord-api-docs/pull/6927) | [GH-9906](https://github.com/Rapptz/discord.py/pull/9906) | |

### Webhook

|    Feature    |    Description    |    Status    |    Discord Docs PR    |    discord.py PR    |    Notes    |
|---------------|-------------------|--------------|-----------------------|---------------------|-------------|
| Sending Voice Messages via Webhook | Allows sending voice messages via webhooks | Not Released | | [GH-9459](https://github.com/Rapptz/discord.py/pull/9459) | |
