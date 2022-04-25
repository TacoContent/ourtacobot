
## TWITCH COMMANDS

### COMMAND PREFIX

`!taco `: All commands in OurTacoBot begin with `!taco ` with a space before the command.

`!taco <command> [subcommand] [arg1...argN]`


## COMMANDS

| NAME | DESCRIPTION | EXAMPLE USAGE | PERMISSION | COOLDOWN | CHANNELS |  
|---|---|---|---|---|---|
| [`commands`](#commands) | Gives a link to this documentation | `!taco commands` | EVERYONE | 30s | ALL |
| [`discord`](#discord) | Display an invite to the TACO discord. This invite is an invite that you created, that is set to never expire, or a random invite if you haven't created one. If you haven't you should create an invite, as you get 25 tacos🌮 for inviting someone. | `!taco discord` | EVERYONE | 30s | ALL |  
| [`tqotd`](#tqotd) | Displays the currently active TACO Question of the Day along with an invite to the discord (see `discord` command) | `!taco tqotd` | EVERYONE | 30s | ALL |  
| [`tacos count`](#tacos-count) | Get the total tacos for yourself. | `!taco tacos count` | EVERYONE | 30s | ALL |  
| [`tacos count <user>`](#tacos-count-user) | Get the total tacos for a specific user. | `!taco tacos count darthminos` | **MODERATOR** | 30s | ALL |  
| [`tacos give <user> <count> [reason]`](#tacos-give) | Give a user the specified number of tacos for the given reason. You can give 10 tacos max at a time. You can give a specific user a max of 50 tacos per rolling 24 hours. You can give a total of 500 tacos per rolling 24 hours.| `!taco tacos give 5 darthminos being awesome` | **MODERATOR** | 30s | ALL |  
| [`tacos top [limit <= 10 \|\| 5]`](#tacos-top) | Get the top `N` users and how many tacos they have. The default is `5`, the max is `10`. | `!taco tacos top 10` | EVERYONE | 30s | ALL |  
| [`link`](#link) | A request to start to link your twitch account to your discord account within OurTacoBot. There is a similar command in the Discord Taco Bot to do this the opposite way. This command will output a CODE for you to use in a command in discord. | `!taco link` | EVERYONE | 30s | ALL |
| [`link <code>`](#link-code) | Run this command after running the `.taco link` command in discord to request a code to link your discord and twitch within OurTacoBot. | `!taco link ABC123` | EVERYONE | 30s | ALL |
| [`invite`](#invite) | Invite OurTacoBot to your twitch channel. | `!taco invite` | EVERYONE | 30s | [@OurTacoBot](https://twitch.tv/ourtacobot) |  
| [`leave`](#leave) | Have OurTacoBot leave your twitch channel. | `!taco leave` | EVERYONE | 30s | [@OurTacoBot](https://twitch.tv/ourtacobot) |  


# COMMANDS

`!taco commands`

Gives a link to this documentation. 


# DISCORD

`!taco discord`

Display an invite to the TACO discord. This invite is an invite that you created, that is set to never expire, or a random invite if you haven't created one. If you haven't you should create an invite, as you get 25 tacos🌮 for inviting someone.

It is recommended that you create your own invite in the TACO discord, making sure that the invite never expires, and has unlimited uses. This way you can be credited 25 tacos 🌮 for inviting the user to the discord.

# TQOTD

`!taco tqotd`

Displays the currently active TACO Question of the Day along with an invite to the discord (see [`discord`](#discord) command)

# TACOS COUNT

`!taco tacos count`

Get the total tacos for yourself.

# TACOS COUNT USER

`!taco tacos count <user>`

### ARGUMENTS 

| NAME | DESCRIPTION | DEFAULT |
|---|---|---|
| `user` | The user to check the taco count for | `""` |

Get the total tacos for a specific user.

# TACOS GIVE

`!taco tacos give <user> <count> [reason]`

### ARGUMENTS 

| NAME | DESCRIPTION | DEFAULT |
|---|---|---|
| `user` | The user to give the tacos to | `""` |
| `count` | The number of tacos to give. Max 10. Min 1 | `""` |
| `reason` | The reason to give them the tacos | `being awesome` |

Give a user the specified number of tacos for the given reason. You can give 10 tacos max at a time. You can give a specific user a max of 50 tacos per rolling 24 hours. You can give a total of 500 tacos per rolling 24 hours.

# TACOS TOP

`!taco tacos top [limit <= 10 || 5]`

### ARGUMENTS 

| NAME | DESCRIPTION | DEFAULT |
|---|---|---|
| `limit` | The number of users to return. Max 10. Min 1. | `5` |

# LINK

`!taco link`

A request to start to link your twitch account to your discord account within OurTacoBot. There is a similar command in the Discord Taco Bot to do this the opposite way. This command will output a CODE for you to use in a command in discord. 

# LINK CODE

`!taco link <code>`

Run this command with the code you receive after running the `.taco link` command in discord to request to link your discord and twitch within OurTacoBot.

### ARGUMENTS 

| NAME | DESCRIPTION | DEFAULT |
|---|---|---|
| `code` | The code supplied to you by running the `.taco link` command in discord. | `""` |

# INVITE

`!taco invite`

Invite OurTacoBot to your twitch channel.

# LEAVE

`!taco leave`

Have OurTacoBot leave your twitch channel.