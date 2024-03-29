[bot-invite]: https://easypoll.me/invite?utm_source=github&utm_medium=readme&utm_campaign=easypoll
[discord-invite]: https://easypoll.me/discord
[license]: https://github.com/fbrettnich/easypoll-bot/blob/main/LICENSE
[guilds-shield]: https://img.shields.io/badge/dynamic/json?color=7289DA&label=Servers&query=guildCount&url=https%3A%2F%2Fdiscord.bots.gg%2Fapi%2Fv1%2Fbots%2F437618149505105920
[discord-shield]: https://discord.com/api/guilds/552156123734474762/widget.png
[license-shield]: https://img.shields.io/github/license/fbrettnich/easypoll-bot?label=License

[ ![guilds-shield][] ][bot-invite]
[ ![discord-shield][] ][discord-invite]
[ ![license-shield][] ][license]

<img align="right" src="https://raw.githubusercontent.com/fbrettnich/easypoll-bot/main/.github/images/easypoll-logo.png" height="200" width="200">

# EasyPoll Discord Bot

With EasyPoll, a Discord Poll Bot, they can easily create polls and your members can vote by clicking on a reaction very easily and quickly.

## Invite
If you want to use **EasyPoll** on your server, you can invite it via the following link:  
&#128279; **[https://easypoll.me/invite][bot-invite]**

## Usage & Commands

| Command     | Description                                                                                                             |
| ----------- | ----------------------------------------------------------------------------------------------------------------------- |
| /poll       | Create a normal poll without time limit and with up to 20 own answers                                                   |
| /timepoll   | Create a timed poll, set an end date until when the poll will run. Use time specifications for this like 10m / 3h / 1d  |
| /closepoll  | Close a poll so that no more votes are counted and display the final result                                             |
| /easypoll   | Get a list and help with all commands                                                                                   |
| /vote       | Vote for the EasyPoll Bot                                                                                               |
| /invite     | Invite EasyPoll to your own Discord Serve                                                                               |
| /info       | Show some information about EasyPoll                                                                                    |
| /ping       | See the Ping of the Bot to the Discord Gateway                                                                          |

## Getting Help
If you have any questions about using the EasyPoll Bot, feel free to visit the official [EasyPoll Support Discord][discord-invite]

## Contributing to EasyPoll
If you want to contribute to EasyPoll, follow these steps:
- [Fork](https://github.com/fbrettnich/easypoll-bot/fork) this repository
- Make your changes
- Check your changes
- Create a [pull request](https://github.com/fbrettnich/easypoll-bot/pulls)
<!--    - **Important:** Create pull requests only in our `development` or `feature` branch, pull requests to the `main` branch will be rejected! -->

Please also read the [contributing guidelines](https://github.com/fbrettnich/easypoll-bot/blob/main/.github/CONTRIBUTING.md) to contribute properly!

We are happy about any contribution &#9786;

## Dependencies
- [JDA (Java Discord API)](https://github.com/DV8FromTheWorld/JDA/)
- [mongodb-driver](https://github.com/TenorioStephano/MongoDB)
- [mysql-connector-j](https://github.com/mysql/mysql-connector-j)
- [emoji-java](https://github.com/vdurmont/emoji-java)
- [sentry-java](https://github.com/getsentry/sentry-java)
- [unirest-java](https://github.com/Kong/unirest-java)

## Self-Hosting
Running your own version of EasyPoll Bot is not supported.  
No help is provided for editing, compiling or building this code.  
All changes must follow the [license][license].
