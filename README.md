# Discord Bot
Automate your discord server, roles, commands, events, guild manager, musics, logs


[![](https://img.shields.io/discord/677642178083946580?color=%23768ACF&label=Discord)](https://discord.gg/3HTqPFDBmT)


[JOIN THE DISCORD BOT TO YOUR SERVER](https://discord.com/api/oauth2/authorize?client_id=778451003950760007&permissions=8&scope=bot)


### Hi, I'm Discord bot, i'd like to help your server, I have the following commands below, that's I can do!
![enter image description here](discord.svg)
\
![enter image description here](usa.svg)

## I'll help you to manage your server making it easier to set members roles, permissions, get tutorials, also members can call me to play songs in audio channel, down below you'll find some of my commands & how to use them properly.

```yml
Considering your guild prefix is set as: $
```

# **`help:`** displays this help message.
```scss
E.g: $help 
        
Returns an embedded message with help info
```
---

# **`lang:`** shows the current bot language.
```scss
E.g: $lang
        
Returns a text info as the current bot language
```
---

# **`setlang:`** changes the bot language.
```scss
E.g: $setlang [es | en | pt]
        
Sets the new bot language
```
---

# **`locale:`** shows the bot locale.
```scss
E.g: $locale

Returns a text info as the current bot locale
```
---

# **`setlocale:`** changes the bot locale.
```scss
E.g: $setlocale [es-ES | en-US | pt-BR]

Sets the new bot locale
```
---

# **`zone:`** shows the current bot timezone.
```scss
E.g: $zone

Returns a text info as the current bot timezone
```
---

# **`setzone:`** changes the bot zone.
```scss
E.g: $setzone America/Chicago

Sets the new bot timezone
```
---

# **`prefix:`** shows the current bot prefix.
```scss
E.g: $prefix

Returns a char info as the current bot prefix
```
---

# **`setprefix:`** changes the bot prefix.
```scss
E.g: $setprefix !

Changes the bot prefix
```
---

# **`autorole:`** changes the default role for new members.
```scss
E.g: $autorole

Shows the indexes of roles to choose one as default
```
```mysql
CHOOSE THE DEFAULT ROLE FOR NEW MEMBERS!
Enter the role index that should automatically be given to a new member!
```
`0` Staff
\
`1` Dev
\
`2` Vip
\
`3` Member

```
➕   3|                      🎁 😄
```
```lombok.config
Default role for new members set as: Member
```

---

# **`moverole:`** moves the selected role to another position.
```scss
E.g: $moverole

Shows the indexes of roles to be moved to another role position
```

```mysql
CHOOSE THE ROLE TO CHANGE ITS POSITION!
Enter the role index that should be changed to another position!
```
`0` Staff
\
`1` Dev
\
`2` Vip
\
`3` Member
```
➕   3|                      🎁 😄
```
```mysql
CHOOSE THE ROLE TO CHANGE ITS POSITION!
Now, type the new index for the role!
```
`0` Staff
\
`1` Dev
\
`2` Vip
\
`3` **Member**
```
➕   1|                      🎁 😄
```
```lombok.config
Success! New roles positions:
```
`0` Staff
\
`1` Member
\
`2` Dev
\
`3` Vip


---

# **`setjoinchannel:`** changes the welcome channel.
```scss
E.g: $setjoinchannel

Shows the indexes of channels to be the selected to announce arrivals
```
```mysql
CHOOSE THE WELCOME CHANNEL!
Enter the channel index to announce the arrival of a new member!
```

【🍱】CONTROL ROOM *(category)*
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`0`【👉】check-in *(channel)*
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`1`【👈】check-out️ *(channel)*
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`2`【🌎】global ☑ *(channel)*
\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
`3`【📻】radio-player️ *(channel)*

```
➕   0|                      🎁 😄
```

```lombok.config
Welcome channel set to: #【👉】check-in
```

---
# **`delete:`** bulk deletes messages on the channel.
```scss
E.g: $delete 100

Bulk deletes messages on the channel; max 100 per command 
```
---


# **`join:`** call the bot to join the audio channel to play.
```scss
E.g: $join

Makes the bot be in the audio channel
```
---

# **`add:`** add a music track to the queue to be played.
```scss
E.g: $add Djavan - Sem Saber

Searches for music to return it to the bot queue
```
---
# **`play:`** play the music track / queue.
```scss
E.g: $play

Plays the bot track queue
```
---
# **`repeat:`** repeat the track playing after it's ending.
```scss
E.g: $repeat

Repeats the current playing track
```
---
# **`volume:`** changes the volume of the bot player.
```scss
E.g: $volume 100

Changes the player volume percentage
```
---
# **`skip:`** skips to the next track to be played and plays it.
```scss
E.g: $skip

Skip the current playing track then starts the next
```
---
# **`queue:`** check the track playing and the queue of tracks to be play.
```scss
E.g: $queue

Returns an embedded message with tracks in the queue & your durations
```
---
# **`pause:`** pause the player current playing track.
```scss
E.g: $pause

Pauses the bot player, (use play command to unpause it)
```
---
# **`stop:`** stop the player & clear the tracks in the queue.
```scss
E.g: $stop

Stops the bot player, clear all tracks
```
