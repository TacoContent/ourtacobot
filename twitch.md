[< BACK](/ourtacobot)

# OURTACOBOT TWITCH COMMANDS
### GENERATED: 2022-04-27 16:35:33


### COMMAND PREFIXES
The following prefixes are accepted:  

- `!taco `  
- `#taco `  
- `?taco `  


`!taco <command> [subcommand] [arg1...argN]`

# COMMAND LIST
- [COMMANDS](#commands)  

- [DISCORD](#discord)  

- [INVITE](#invite)  

- [LEAVE](#leave)  

- [TACOS](#tacos)  

  - [TACOS COUNT](#tacos-count)  

  - [TACOS COUNT](#tacos-count)  

  - [TACOS GIVE](#tacos-give)  

  - [TACOS HELP](#tacos-help)  

  - [TACOS TAKE](#tacos-take)  

  - [TACOS TOP](#tacos-top)  

---

## COMMANDS
Get a url to view documentation for all commands.

### USAGE 🤗

```!taco commands```

### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco commands`  


---

## DISCORD
Promotes the TACO discord using an invite that you have created in the discord.

### USAGE 🤗

```!taco discord```

### ALIASES 🔀

- `taco`  


### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco discord`  


---

## INVITE
Invite OurTacoBot to your twitch channel.

### USAGE 🤗

```!taco invite```

### ALIASES 🔀

- `inv`  
- `join`  


### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco invite`  


### RESTRICTED 🔒

This command is restricted to the following twitch channels:  

- [ourtaco](https://twitch.tv/ourtaco)  
- [ourtacobot](https://twitch.tv/ourtacobot)  

---

## LEAVE
Remove OurTacoBot to your twitch channel.

### USAGE 🤗

```!taco leave```

### ALIASES 🔀

- `part`  
- `remove`  


### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco leave`  


### RESTRICTED 🔒

This command is restricted to the following twitch channels:  

- [ourtaco](https://twitch.tv/ourtaco)  
- [ourtacobot](https://twitch.tv/ourtacobot)  

---

## TACOS
Set of commands to deal with tacos.

### USAGE 🤗

```!taco tacos help```

### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco tacos help`  


---
## TACOS COUNT
Get the number of tacos that you have.

### USAGE 🤗

```!taco tacos count```

### ALIASES 🔀

- `balance`  
- `bal`  


### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco tacos count`  


---
## TACOS COUNT
Get the number of tacos for a user

### USAGE 🤗

```!taco tacos count <user>```

### ALIASES 🔀

- `balance`  
- `bal`  


### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `MODERATOR`  


### EXAMPLES 📃
- `!taco tacos count @DarthMinos`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to get the taco count for. | `string` | DEFAULT: `None` | `YES` |  

---
## TACOS GIVE
Give a user tacos. The maximum amount of tacos that can be given at a time is 10. The maximum amount that can be given to a user in a rolling 24 hour period is 50. The maximum amount that can be given total in a rolling 24 hour period is 500.

### USAGE 🤗

```!taco tacos give <user> <amount> [reason]```

### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `MODERATOR`  


### EXAMPLES 📃
- `!taco tacos give @DarthMinos 1 being awesome`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to give tacos to. | `string` | DEFAULT: `None` | `YES` |  
| `amount` | The amount of tacos to give. | `number` | DEFAULT: `None`  MIN: `1`  MAX: `10` | `YES` |  
| `reason` | The reason for the giving tacos. | `string` | DEFAULT: `No reason given` | `NO` |  

---
## TACOS HELP
Shows the help for the tacos subcommands.

### USAGE 🤗

```!taco tacos help```

### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `EVERYONE`  


### EXAMPLES 📃
- `!taco tacos help`  


---
## TACOS TAKE
Take tacos from a user.

### USAGE 🤗

```!taco tacos take <user> <amount> [reason]```

### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `MODERATOR`  


### EXAMPLES 📃
- `!taco tacos take @DarthMinos 1 incorrect trivia answer`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to take tacos from. | `string` | DEFAULT: `None` | `YES` |  
| `amount` | The amount of tacos to take. | `number` | DEFAULT: `None`  MIN: `1`  MAX: `10` | `YES` |  
| `reason` | The reason for taking the tacos. | `string` | DEFAULT: `No reason given` | `NO` |  

---
## TACOS TOP
Get the leader board for users tacos.

### USAGE 🤗

```!taco tacos top [limit]```

### ALIASES 🔀

- `leaderboard`  
- `lb`  


### COOLDOWN 🕕
`30s`

### PERMISSIONS 🔑
- `MODERATOR`  


### EXAMPLES 📃
- `!taco tacos top 5`  


### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `limit` | The amount of users to show on the leader board. | `number` | DEFAULT: `5`  MIN: `1`  MAX: `10` | `NO` |  

