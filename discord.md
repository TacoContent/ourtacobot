[⏪ BACK](/ourtacobot)<a name="top"></a>

# OURTACOBOT DISCORD COMMANDS
### GENERATED: 2022-04-28 15:05:30


### COMMAND PREFIXES
The following prefixes are accepted:  

- `.taco `  
- `!taco `  
- `?taco `  


`.taco <command> [subcommand] [arg1...argN]`

# COMMAND LIST
Commands with 🛡️ are only available to admins.
- [BIRTHDAY](#birthday)  

- [CHANGELOG](#changelog)  

- [GIF](#gif)  

- [LINK](#link)  

- [LINK](#link)  

- [MOVE🛡️](#move)  

- [SUGGEST](#suggest)  

- [TQOTD🛡️](#tqotd)  

  - [TQOTD GIVE🛡️](#tqotd-give)  

- [TACOS](#tacos)  

  - [TACOS COUNT](#tacos-count)  

  - [TACOS GIFT](#tacos-gift)  

  - [TACOS GIVE🛡️](#tacos-give)  

  - [TACOS PURGE🛡️](#tacos-purge)  

- [TEAM](#team)  

  - [TEAM INVITE](#team-invite)  

  - [TEAM INVITE-USER🛡️](#team-invite-user)  

- [TRIVIA](#trivia)  

- [TWITCH](#twitch)  

  - [TWITCH SET](#twitch-set)  

  - [TWITCH SET-USER🛡️](#twitch-set-user)  

  - [TWITCH GET](#twitch-get)  

---

<a name="birthday"></a>
## BIRTHDAY
Sets your birthday

### USAGE 🤗

```.taco birthday```

### ALIASES 🔀

- `bday`  


### EXAMPLES 📃
- `.taco birthday`  
- `.taco bday`  




[🔼 TOP](#top)  

---

<a name="changelog"></a>
## CHANGELOG
Shows the changelog

### USAGE 🤗

```.taco changelog```

### ALIASES 🔀

- `cl`  


### EXAMPLES 📃
- `.taco changelog`  
- `.taco cl`  




[🔼 TOP](#top)  

---

<a name="gif"></a>
## GIF
Gets a random gif from the given tag

### USAGE 🤗

```.taco gif [search_term]```

### ALIASES 🔀

- `giphy`  


### EXAMPLES 📃
- `.taco gif`  
- `.taco gif taco tuesday`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `search_term` | The string to search for | `string` | DEFAULT: `taco` | `🔲` |  


[🔼 TOP](#top)  

---

<a name="link"></a>
## LINK
Request a code from the bot to link your discord account to your twitch account

### USAGE 🤗

```.taco link```

### EXAMPLES 📃
- `.taco link`  




[🔼 TOP](#top)  

---

<a name="link"></a>
## LINK
Use a code from the bot to link your discord account to your twitch account

### USAGE 🤗

```.taco link <code>```

### EXAMPLES 📃
- `.taco link ABC123`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `code` | The code given to you by the bot in twitch chat | `string` | DEFAULT: `None` | `✅` |  


[🔼 TOP](#top)  

---

<a name="move"></a>
## MOVE🛡️
Moves a message from one channel to another. Must be ran in the channel that the message is in.

### USAGE 🤗

```.taco move <message_id>```

### EXAMPLES 📃
- `.taco move 12345678901234567890123456789`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `message_id` | The message id of the message to move | `string` | DEFAULT: `None` | `✅` |  


[🔼 TOP](#top)  

---

<a name="suggest"></a>
## SUGGEST
Starts a suggestion. I will DM you to ask you questions to create the suggestion.

### USAGE 🤗

```.taco suggest```

### EXAMPLES 📃
- `.taco suggest`  




[🔼 TOP](#top)  

---

<a name="tqotd"></a>
## TQOTD🛡️
Adds a question of the day

### USAGE 🤗

```.taco tqotd [command]```

---
<a name="tqotd-give"></a>
## TQOTD GIVE🛡️
Gives TQotD tacos to the user who answered the question

### USAGE 🤗

```.taco tqotd give <@user>```

### EXAMPLES 📃
- `.taco tqotd give @DarthMinos#1161`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to give tacos to for answering the question | `user` | DEFAULT: `None` | `✅` |  


[🔼 TOP](#top)  

---

<a name="tacos"></a>
## TACOS
Commands that will give info on tacos🌮.

### USAGE 🤗

```.taco tacos <command>```

---
<a name="tacos-count"></a>
## TACOS COUNT
Retrieve the number of tacos you have.

### USAGE 🤗

```.taco tacos count```

### EXAMPLES 📃
- `.taco tacos count`  



---
<a name="tacos-gift"></a>
## TACOS GIFT
Gift someone a number of tacos. You can gift a maximum of 10 tacos per 24 hours (rolling).

### USAGE 🤗

```.taco tacos gift <@user#1234> <amount> [reason]```

### EXAMPLES 📃
- `.taco tacos gift @user#1234 10`  
- `.taco tacos gift @user#1234 10 You are awesome!`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to gift tacos to | `user` | DEFAULT: `None` | `✅` |  
| `amount` | The amount of tacos to gift | `number` | DEFAULT: `None`  MIN: `1`  MAX: `10` | `✅` |  
| `reason` | The reason for the gift | `string` | DEFAULT: `No reason given` | `🔲` |  

---
<a name="tacos-give"></a>
## TACOS GIVE🛡️
Allows an admin to give someone tacos.

### USAGE 🤗

```.taco tacos give <@user#1234> <amount> [reason]```

### EXAMPLES 📃
- `.taco tacos give @user#1234 10`  
- `.taco tacos give @user#1234 10 You are awesome!`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to give tacos to | `user` | DEFAULT: `None` | `✅` |  
| `amount` | The amount of tacos to give | `number` | DEFAULT: `None`  MIN: `1`  MAX: `10` | `✅` |  
| `reason` | The reason for the gift | `string` | DEFAULT: `No reason given` | `🔲` |  

---
<a name="tacos-purge"></a>
## TACOS PURGE🛡️
Allows an admin to purge all tacos from a user.

### USAGE 🤗

```.taco tacos purge <@user#1234> [reason]```

### EXAMPLES 📃
- `.taco tacos purge @user#1234`  
- `.taco tacos purge @user#1234 Exploited the taco system`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to purge tacos from | `user` | DEFAULT: `None` | `✅` |  
| `reason` | The reason for the purge | `string` | DEFAULT: `No reason given` | `🔲` |  


[🔼 TOP](#top)  

---

<a name="team"></a>
## TEAM
Commands that will allow you to be a part of the Twitch Team.

### USAGE 🤗

```.taco team <command>```

---
<a name="team-invite"></a>
## TEAM INVITE
This will put in a request to join the twitch team. Once approved, you will have to accept it from your creator dashboard. Twitch Dashboard -> Settings -> Channel -> Featured Content => Scroll to the bottom.

### USAGE 🤗

```.taco team invite <twitch_name>```

### EXAMPLES 📃
- `.taco team invite darthminos`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `twitch_name` | The twitch name of the user to invite | `string` | DEFAULT: `None` | `✅` |  

---
<a name="team-invite-user"></a>
## TEAM INVITE-USER🛡️
Admin version of the `invite` command. This will invite a user to the twitch team. Once approved, they will have to accept it from their creator dashboard. Twitch Dashboard -> Settings -> Channel -> Featured Content => Scroll to the bottom.

### USAGE 🤗

```.taco team invite-user <@user#1234> <twitch_name>```

### EXAMPLES 📃
- `.taco team invite-user @DarthMinos#1161 darthminos`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to invite | `user` | DEFAULT: `None` | `✅` |  
| `twitch_name` | The twitch name of the user to invite | `string` | DEFAULT: `None` | `✅` |  


[🔼 TOP](#top)  

---

<a name="trivia"></a>
## TRIVIA
Start a trivia question to earn tacos.

### USAGE 🤗

```.taco trivia```

### EXAMPLES 📃
- `.taco trivia`  




[🔼 TOP](#top)  

---

<a name="twitch"></a>
## TWITCH
Commands to set up your Twitch account with Taco Bot.

### USAGE 🤗

```.taco twitch <command>```

---
<a name="twitch-set"></a>
## TWITCH SET
Set your twitch name. This will allow the bot to know your twitch account associated with your discord account.

### USAGE 🤗

```.taco twitch set [twitch_name]```

### EXAMPLES 📃
- `.taco twitch set darthminos`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `twitch_name` | The twitch name of the user to invite | `string` | DEFAULT: `None` | `✅` |  

---
<a name="twitch-set-user"></a>
## TWITCH SET-USER🛡️
Set a user's twitch name so Taco Bot can resolve a discord user to a twitch user, and vice versa.

### USAGE 🤗

```.taco twitch set-user <@user#1234> [twitch_name]```

### EXAMPLES 📃
- `.taco twitch set-user @DarthMinos#1161 darthminos`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to set the twitch name for | `user` | DEFAULT: `None` | `✅` |  
| `twitch_name` | The twitch name of the user to set | `string` | DEFAULT: `None` | `🔲` |  

---
<a name="twitch-get"></a>
## TWITCH GET
Will tell you what the twitch username is associated with your, or the specified, account.

### USAGE 🤗

```.taco twitch get [@user#1234]```

### EXAMPLES 📃
- `.taco twitch get @DarthMinos#1161`  



### ARGUMENTS 🔖

| NAME | DESCRIPTION | TYPE | DEFAULT/MIN/MAX | REQUIRED |  
|---|---|---|---|---|  
| `user` | The user to get the twitch name for | `user` | DEFAULT: `None` | `🔲` |  


[🔼 TOP](#top)  

