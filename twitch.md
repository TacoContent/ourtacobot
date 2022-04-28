[⏪ BACK](/ourtacobot)<a name="top"></a>

# OURTACOBOT TWITCH COMMANDS
### GENERATED: 2022-04-28 14:08:42


### COMMAND PREFIXES
The following prefixes are accepted:  

- `!taco `  
- `#taco `  
- `?taco `  


`!taco <command> [subcommand] [arg1...argN]`

# COMMAND LIST
Commands with 🛡️ are only available to admins.
- [COMMANDS](#commands)  

- [DISCORD](#discord)  

- [INVITE](#invite)  

- [LEAVE](#leave)  

- [TACOS](#tacos)  

  - [TACOS COUNT](#tacos-count)  

  - [TACOS COUNT🛡️](#tacos-count)  

  - [TACOS GIVE🛡️](#tacos-give)  

  - [TACOS TAKE🛡️](#tacos-take)  

  - [TACOS TOP🛡️](#tacos-top)  

- [TQOTD](#tqotd)  

- [LINK](#link)  

- [LINK](#link)  

---

<a name="commands"></a>
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

<a name="discord"></a>
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

<a name="invite"></a>
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

<a name="leave"></a>
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

<a name="tacos"></a>
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
<a name="tacos-count"></a>
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
<a name="tacos-count"></a>
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
<a name="tacos-give"></a>
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
<a name="tacos-take"></a>
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
<a name="tacos-top"></a>
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

<a name="tqotd"></a>
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

<a name="link"></a>
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

<a name="link"></a>
## LINK
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

