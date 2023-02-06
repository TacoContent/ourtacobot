[⏪ BACK](/ourtacobot)<a name="top"></a>

# OURTACOBOT TWITCH COMMANDS
### GENERATED: 2023-02-06 12:22:04


### COMMAND PREFIXES
The following prefixes are accepted:  

- `!taco `  
- `#taco `  
- `?taco `  


`!taco <command> [subcommand] [arg1...argN]`

# COMMAND LIST
Commands with 🛡️ are only available to moderators.  
Commands with 🔒 can only be ran in the specified channels.  

- [COMMANDS](#commands_command)  

- [DISCORD](#discord_command)  

- [DIXPER🛡️](#dixper_command)  

  - [DIXPER START🛡️](#dixper-start_command)  

  - [DIXPER STOP🛡️](#dixper-stop_command)  

- [RAINMAKER🛡️](#rainmaker_command)  

  - [RAINMAKER START🛡️](#rainmaker-start_command)  

  - [RAINMAKER SET🛡️](#rainmaker-set_command)  

  - [RAINMAKER STOP🛡️](#rainmaker-stop_command)  

- [GAME](#game_command)  

- [INVITE🔒](#invite_command)  

- [LEAVE🔒](#leave_command)  

- [STREAMELEMENTS🛡️](#streamelements_command)  

  - [STREAMELEMENTS START🛡️](#streamelements-start_command)  

  - [STREAMELEMENTS STOP🛡️](#streamelements-stop_command)  

  - [STREAMELEMENTS TIP🛡️](#streamelements-tip_command)  

- [STREAMRAIDERS🛡️](#streamraiders_command)  

  - [STREAMRAIDERS START🛡️](#streamraiders-start_command)  

  - [STREAMRAIDERS STOP🛡️](#streamraiders-stop_command)  

- [TACOS](#tacos_command)  

  - [TACOS COUNT](#tacos-count_command)  

  - [TACOS COUNT🛡️](#tacos-_count_command)  

  - [TACOS GIVE🛡️](#tacos-give_command)  

  - [TACOS TAKE🛡️](#tacos-take_command)  

  - [TACOS TOP🛡️](#tacos-top_command)  

- [TQOTD](#tqotd_command)  

- [LINK](#link_command)  

- [LINK \<CODE\>](#_link_command)  


# EVENT LIST
- [FIRST CHAT](#first-chat_event)  

- [RAID](#raid_event)  

- [HOST](#host_event)  

- [CHEER](#cheer_event)  

- [SUBSCRIPTION](#subscription_event)  

- [STREAM RAIDERS EPIC PLACEMENT](#stream-raiders-epic-placement_event)  

- [DIXPER](#dixper_event)  

- [RAINMAKER](#rainmaker_event)  

- [STREAM ELEMENTS TIP](#stream-elements-tip_event)  

---

<a name="commands_command"></a>
## COMMANDS  
Get a url to view documentation for all commands.

### USAGE 🤗

```!taco commands```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco commands`  



![](https://i.imgur.com/8lx0Ohy.png)  


### PERMISSIONS 🔑
- `EVERYONE`  



[🔼 TOP](#top)  

---

<a name="discord_command"></a>
## DISCORD  
Promotes the TACO discord using an invite that you have created in the discord.

### USAGE 🤗

```!taco discord```

### ALIASES 🔀

- `taco`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco discord`  



![](https://i.imgur.com/n0wBukf.png)  


### PERMISSIONS 🔑
- `EVERYONE`  



[🔼 TOP](#top)  

---

<a name="dixper_command"></a>
## DIXPER🛡️  
Allows you to control if the bot will give tacos for purchase of dixper packs. If you do not use dixper in your channel, this will not matter.

### USAGE 🤗

```!taco dixper <on/off>```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco dixper on`  
- `!taco dixper start`  
- `!taco dixper enable`  
- `!taco dixper off`  
- `!taco dixper stop`  
- `!taco dixper disable`  



### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="dixper-start_command"></a>
## DIXPER START🛡️  
Enables the bot to give tacos when people purchase dixper packs.

### USAGE 🤗

```!taco dixper start```

### ALIASES 🔀

- `start`  
- `on`  
- `enable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco dixper on`  
- `!taco dixper start`  
- `!taco dixper enable`  



![](https://i.imgur.com/3fkoGdY.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="dixper-stop_command"></a>
## DIXPER STOP🛡️  
Disabled the bot from giving tacos when people purchase dixper packs.

### USAGE 🤗

```!taco dixper stop```

### ALIASES 🔀

- `stop`  
- `off`  
- `disable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco dixper off`  
- `!taco dixper stop`  
- `!taco dixper disable`  



### PERMISSIONS 🔑
- `MODERATOR`  



[🔼 TOP](#top)  

---

<a name="rainmaker_command"></a>
## RAINMAKER🛡️  
Allows you to control if the bot will give tacos for retweets notified via rainmaker. If you do not use rainmaker in your channel, this will not matter.

### USAGE 🤗

```!taco rainmaker <on/off>```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco rainmaker on`  
- `!taco rainmaker start`  
- `!taco rainmaker enable`  
- `!taco rainmaker off`  
- `!taco rainmaker stop`  
- `!taco rainmaker disable`  



### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="rainmaker-start_command"></a>
## RAINMAKER START🛡️  
Enables the bot to give tacos when people retweet.

### USAGE 🤗

```!taco rainmaker start```

### ALIASES 🔀

- `start`  
- `on`  
- `enable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco rainmaker on`  
- `!taco rainmaker start`  
- `!taco rainmaker enable`  



![](https://i.imgur.com/3fkoGdY.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="rainmaker-set_command"></a>
## RAINMAKER SET🛡️  
Set the retweet message regular expression. By default it is set to match the default rainmaker message. If you have a custom message, you can set it here.

### USAGE 🤗

```!taco rainmaker set <regex>```

### ALIASES 🔀

- `set`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco rainmaker set ^Thank you for tweeting out the stream, (?P<user>@?[a-zA-Z0-9-_]+).$`  



### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="rainmaker-stop_command"></a>
## RAINMAKER STOP🛡️  
Disabled the bot from giving tacos when people retweet.

### USAGE 🤗

```!taco rainmaker stop```

### ALIASES 🔀

- `stop`  
- `off`  
- `disable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco rainmaker off`  
- `!taco rainmaker stop`  
- `!taco rainmaker disable`  



### PERMISSIONS 🔑
- `MODERATOR`  



[🔼 TOP](#top)  

---

<a name="game_command"></a>
## GAME  
Shows the name of the game that is currently being offered via the TACO Rewards.

### USAGE 🤗

```!taco game```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco game`  



![](https://i.imgur.com/9pPPWhz.png)  


### PERMISSIONS 🔑
- `EVERYONE`  



[🔼 TOP](#top)  

---

<a name="invite_command"></a>
## INVITE  
Invite OurTacoBot to your twitch channel.

### USAGE 🤗

```!taco invite```

### ALIASES 🔀

- `inv`  
- `join`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco invite`  



![](https://i.imgur.com/vJgtOCj.png)  


### PERMISSIONS 🔑
- `EVERYONE`  


### RESTRICTED 🔒

This command is restricted to the following twitch channels:  

- [@OURTACO](https://twitch.tv/ourtaco)  
- [@OURTACOBOT](https://twitch.tv/ourtacobot)  


[🔼 TOP](#top)  

---

<a name="leave_command"></a>
## LEAVE  
Remove OurTacoBot to your twitch channel.

### USAGE 🤗

```!taco leave```

### ALIASES 🔀

- `part`  
- `remove`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco leave`  



![](https://i.imgur.com/6mkkHmk.png)  


### PERMISSIONS 🔑
- `EVERYONE`  


### RESTRICTED 🔒

This command is restricted to the following twitch channels:  

- [@OURTACO](https://twitch.tv/ourtaco)  
- [@OURTACOBOT](https://twitch.tv/ourtacobot)  


[🔼 TOP](#top)  

---


[🔼 TOP](#top)  

---

<a name="streamelements_command"></a>
## STREAMELEMENTS🛡️  
Allows you to control if the bot will give tacos for streamelements tips. If you do not use streamelements  in your channel, this setting doesn't matter.

### USAGE 🤗

```!taco streamelements <on/off>```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamelements on`  
- `!taco streamelements start`  
- `!taco streamelements enable`  
- `!taco streamelements off`  
- `!taco streamelements stop`  
- `!taco streamelements disable`  



### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="streamelements-start_command"></a>
## STREAMELEMENTS START🛡️  
Enables the bot to give tacos if someone tips through streamelements.

### USAGE 🤗

```!taco streamelements start```

### ALIASES 🔀

- `start`  
- `on`  
- `enable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamelements on`  
- `!taco streamelements start`  
- `!taco streamelements enable`  



![](https://i.imgur.com/meTuhIQ.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="streamelements-stop_command"></a>
## STREAMELEMENTS STOP🛡️  
Disables the bot from giving tacos if someone tips through streamelements.

### USAGE 🤗

```!taco streamelements stop```

### ALIASES 🔀

- `stop`  
- `off`  
- `disable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamelements off`  
- `!taco streamelements stop`  
- `!taco streamelements disable`  



![](https://i.imgur.com/Uzy2O9B.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="streamelements-tip_command"></a>
## STREAMELEMENTS TIP🛡️  
Sets the streamelements tip message so the bot knows what to look for. Make sure to include the `{user}`, `{currency}`, `{amount}` tags. If you use the default message, you do not need to set this.

### USAGE 🤗

```!taco streamelements tip <message>```

### ALIASES 🔀

- `tip`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamelements tip {user} just tipped {currency}{amount} PogChamp`  



![](https://i.imgur.com/X5rOzTo.png)  


### PERMISSIONS 🔑
- `BROADCASTER`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `message` | The message to set as the tip message. Make sure to include the `{user}`, `{currency}`, `{amount}` tags. | `string` | DEFAULT: `""` | `✅` |  


[🔼 TOP](#top)  

---

<a name="streamraiders_command"></a>
## STREAMRAIDERS🛡️  
Allows you to control if the bot will give tacos for streamraiders tips. If you do not use streamraiders  in your channel, this setting doesn't matter.

### USAGE 🤗

```!taco streamraiders <on/off>```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamraiders on`  
- `!taco streamraiders start`  
- `!taco streamraiders enable`  
- `!taco streamraiders off`  
- `!taco streamraiders stop`  
- `!taco streamraiders disable`  



### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="streamraiders-start_command"></a>
## STREAMRAIDERS START🛡️  
Enables the bot to give tacos if someone Epic on the battlefield in streamraiders.

### USAGE 🤗

```!taco streamraiders start```

### ALIASES 🔀

- `start`  
- `on`  
- `enable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamraiders on`  
- `!taco streamraiders start`  
- `!taco streamraiders enable`  



![](https://i.imgur.com/Fup71Na.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


---
<a name="streamraiders-stop_command"></a>
## STREAMRAIDERS STOP🛡️  
Disables the bot from giving tacos if someone places an Epic on the battlefield in streamraiders.

### USAGE 🤗

```!taco streamraiders stop```

### ALIASES 🔀

- `stop`  
- `off`  
- `disable`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco streamraiders off`  
- `!taco streamraiders stop`  
- `!taco streamraiders disable`  



![](https://i.imgur.com/EJYrl1Y.png)  


### PERMISSIONS 🔑
- `MODERATOR`  



[🔼 TOP](#top)  

---

<a name="tacos_command"></a>
## TACOS  
Set of commands to deal with tacos.

### USAGE 🤗

```!taco tacos help```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tacos help`  



### PERMISSIONS 🔑
- `EVERYONE`  


---
<a name="tacos-count_command"></a>
## TACOS COUNT  
Get the number of tacos that you have.

### USAGE 🤗

```!taco tacos count```

### ALIASES 🔀

- `balance`  
- `bal`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tacos count`  



![](https://i.imgur.com/BHwu2db.png)  


### PERMISSIONS 🔑
- `EVERYONE`  


---
<a name="tacos-_count_command"></a>
## TACOS COUNT🛡️  
Get the number of tacos for a user

### USAGE 🤗

```!taco tacos count <user>```

### ALIASES 🔀

- `balance`  
- `bal`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tacos count @DarthMinos`  



![](https://i.imgur.com/k1wxnVL.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to get the taco count for. | `string` | DEFAULT: `None` | `✅` |  

---
<a name="tacos-give_command"></a>
## TACOS GIVE🛡️  
Give a user tacos. The maximum amount of tacos that can be given at a time is 10. The maximum amount that can be given to a user in a rolling 24 hour period is 50. The maximum amount that can be given total in a rolling 24 hour period is 500.

### USAGE 🤗

```!taco tacos give <user> <amount> [reason]```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tacos give @DarthMinos 1 being awesome`  



![](https://i.imgur.com/IyvB6oq.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to give tacos to. | `string` | DEFAULT: `None` | `✅` |  
| `amount` | The amount of tacos to give. | `number` | DEFAULT: `None`  MIN: `1`  MAX: `10` | `✅` |  
| `reason` | The reason for the giving tacos. | `string` | DEFAULT: `No reason given` | `🔲` |  

---
<a name="tacos-take_command"></a>
## TACOS TAKE🛡️  
Take tacos from a user.

### USAGE 🤗

```!taco tacos take <user> <amount> [reason]```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tacos take @DarthMinos 1 incorrect trivia answer`  



![](https://i.imgur.com/A3PS0Y7.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to take tacos from. | `string` | DEFAULT: `None` | `✅` |  
| `amount` | The amount of tacos to take. | `number` | DEFAULT: `None`  MIN: `1`  MAX: `10` | `✅` |  
| `reason` | The reason for taking the tacos. | `string` | DEFAULT: `No reason given` | `🔲` |  

---
<a name="tacos-top_command"></a>
## TACOS TOP🛡️  
Get the leader board for users tacos.

### USAGE 🤗

```!taco tacos top [limit]```

### ALIASES 🔀

- `leaderboard`  
- `lb`  


### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tacos top 5`  



![](https://i.imgur.com/XY0y4Qc.png)  

![](https://i.imgur.com/hYJKHvj.png)  


### PERMISSIONS 🔑
- `MODERATOR`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `limit` | The amount of users to show on the leader board. | `number` | DEFAULT: `5`  MIN: `1`  MAX: `10` | `🔲` |  


[🔼 TOP](#top)  

---

<a name="tqotd_command"></a>
## TQOTD  
Gives you the TACO question of the day.

### USAGE 🤗

```!taco tqotd```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco tqotd`  



![](https://i.imgur.com/A1MdC8Q.png)  


### PERMISSIONS 🔑
- `EVERYONE`  



[🔼 TOP](#top)  

---

<a name="link_command"></a>
## LINK  
Gives you a command and a code to run in discord to link your twitch with your discord account.

### USAGE 🤗

```!taco link```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco link`  



![](https://i.imgur.com/opzviIC.png)  

![](https://i.imgur.com/OdqB6vK.png)  


### PERMISSIONS 🔑
- `EVERYONE`  



[🔼 TOP](#top)  

---

<a name="_link_command"></a>
## LINK \<CODE\>  
Links your discord account with your twitch account.

### USAGE 🤗

```!taco link <code>```

### COOLDOWN 🕕
`30s`

### EXAMPLES 📃
- `!taco link ABC567`  



![](https://i.imgur.com/aZ4rSnO.png)  

![](https://i.imgur.com/OdqB6vK.png)  


### PERMISSIONS 🔑
- `EVERYONE`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `code` | The code you received from the link command. | `string` | DEFAULT: `None` | `✅` |  


[🔼 TOP](#top)  


# EVENTS  

Here are some events that @ourtacobot will act on.

---

<a name="first-chat_event"></a>
### FIRST CHAT  

The first time someone chats in your channel, in a rolling 24 hour period, I will give them 1 taco.


[🔼 TOP](#top)  

---

<a name="raid_event"></a>
### RAID  

When an incoming raid from a TACO member is detected I will give the raiding channel 5 tacos.


[🔼 TOP](#top)  

---

<a name="host_event"></a>
### HOST  

When an incoming host from a TACO member is detected I will give the raiding channel 5 tacos.


[🔼 TOP](#top)  

---

<a name="cheer_event"></a>
### CHEER  

When a cheer >= 100 bits is detected I will give the person 5 tacos for supporting.


[🔼 TOP](#top)  

---

<a name="subscription_event"></a>
### SUBSCRIPTION  

When a user subscribes, or gifts a subscription to the channel I will give them 5 tacos.


[🔼 TOP](#top)  

---

<a name="stream-raiders-epic-placement_event"></a>
### STREAM RAIDERS EPIC PLACEMENT  

When someone places an Epic on the Battlefield for Stream Raiders, I will give them 2 tacos.


[🔼 TOP](#top)  

---

<a name="dixper_event"></a>
### DIXPER  

When someone purchases Dixper packs, I will give them 5 tacos.


[🔼 TOP](#top)  

---

<a name="rainmaker_event"></a>
### RAINMAKER  

When someone retweets the stream, and rainmaker notifies the chat of the retweet, I will give them 5 tacos.


[🔼 TOP](#top)  

---

<a name="stream-elements-tip_event"></a>
### STREAM ELEMENTS TIP  

When someone tips through Stream Elements, I will give them 5 tacos.


[🔼 TOP](#top)  

---


[🔼 TOP](#top)  

