---
tags:
  - command
---

# /chat

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/chat [ [1-10] <message> ] | [ join | leave | leaveall | list | set | announce | invisible | afk | buddy | namespace | invite | grant | password | kick | moderate | voice | local | oplist | opadd | opremove | setowner ] <options>
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Controls chat channels. All options in this syntax can instead be used as standalone commands with a ";" e.g. `;join`, `;set`, `;kick`, etc. For cross-server chat, use [`<server short name>`](../general/server-short-names.md).`<name>` for channels and players.
<!--cmd-desc-end-->

## Options

**[1-10]** `<message>`
:    Sends a message to the specified channel number, from 1 up to 10. Note that you can also use `/` or `;` and just the channel number, eliminating the need for /chat. e.g. `;2 hello everyone`, `/2 how are you`

**join** `<channel1>[:<password>] ... [,channel10][:<password>]`
:    Join one or more channels, and where applicable specify a password required to join a specific channel. To join automatically each session, use [/autojoin](cmd-autojoin.md). Alternate commands: `;join`, `/join`

**leave** `<channel name or number>`
:    Leave the specified chat channel. Alternate commands: `;leave`, `/leave`

**leaveall**
:    Leave all chat channels. Alternate commands: `;leaveall`, `/leaveall`

**list** `<channel name or number>`
:    If no channel specified, it will list all currently joined chat channels. If a specified channel name (or number) is provided, it will list all members currently in that channel. Alternate commands: `;list`, `/list`

**set** `<channel1>[:<password>] ... [,channel10][:<password>]`
:    Makes you a member of all of the channels listed, or a moderator if it's a new channel. You will be joined to those channels in the order listed (see [/join](cmd-chat.md) for details on what 'joining' a channel means). This will remove you from all previously joined channels. See examples below. If you just want to join a new channel, use the ;join instead. Alternate command: `;set`

**announce** `[on|off]`
:    Toggles on and off the announcements heard when people join or leave chat channels. This is set OFF by default. Alternate commands: `;announce`, `/announce`

**invisible** `[on | off]`
:    Toggle. Make yourself appear as offline, so even if someone has you on their friends list, you won't show as online. They can still message you however. Alternate command: `;invisible`

**buddy** `<name>`
:    Adds `<name>` to your friends list. Can prefix with server shortname. Alternate commands: `;buddy`, [`/friends`](cmd-friends.md)

**afk** `[ on | off | <message> ]`
:    This is a chat version of afk, not the same as the [/afk](cmd-afk.md), i.e. no "AFK" appears over your character's head. Any `<message>` will turn it on. Alternate command: `;afk`

**namespace**
:    Shows your current namespace for cross-server communication, aka your current [server short name](../general/server-short-names.md). To communicate cross server, [`;tell`](cmd-tell.md) `namespace.character`

**invite** `<character> <channel>`
:    Sends an invitation to the specified character to join a the chat channel. If no channel is specified the character will be invited to join your first channel (whichever channel is your channel number 1). The invitation arrives as a text message. If the channel is password protected, the invited person can enter the channel only once without a password. Alternate command: `;invite`

**grant** `<character> <channel>`
:    Grants moderator privileges in the channel specified to the character named. If no channel is specified the character will be given moderator privileges to your first channel (whichever channel is your channel number 1). Alternate command: `;grant`

**password** `<password> <channel>`
:    Sets the password for the channel specified. If no channel is specified the password will be applied to your first channel (whichever channel is your channel number 1). Note: A password protected channel is the only type of channel that is semi-permanent. Such a channel will disappear after it has been empty for 24 hours. All other channels cease to exist once they are empty. Alternate command: `;password`

**kick** `<character> <channel>`
:    Kicks the character named off of the chat channel listed. If no channel is specified the character will be kicked our of your first channel (whichever channel is your channel number 1). Alternate command: `;kick`

**moderate** `<channel>`
:    Sets the specified channel to 'moderated' mode. This means that only those given 'voice' in the channel will be able to speak in that channel. If no channel is specified your first channel (whichever channel is your channel number 1) will be set into moderated mode. This is a toggle command, so if you execute this command a second time the channel will return to unmoderated status. Alternate command: `;moderate`

**voice** `<character> <channel>`
:    Give the named character the ability to speak in a moderated channel. If no channel is specified the character will be allowed voice in your first channel (whichever channel is your channel number 1). Alternate command: `;voice`

**local** `<channel name or number>`
:    Toggles local-status on the specified channel. Alternate command: `;local`

**oplist** `<channel name>`
:    Will show owner and operators of the current channel. Alternate command: `;oplist`

**opadd** `<character> <channel name>`
:    On the specified channel, add player as an operator. Alternate command: `;opadd`

**opremove** `<character> <channel name>`
:    On the specified channel, remove player as an operator. Alternate command: `;opremove`

**setowner** `<character> <channel name>`
:    On the specified channel, set player as the new owner. Alternate command: `;setowner`

## Examples

### /chat

- `/chat join general` - Equivalent to using the command `/join general`
- `/chat set Voxraidleader:seekrit, Voxraidgroupleader:notsoseekrit, Voxraidgeneral` - That would set three channels (Voxraidleader, Voxraidgroupleader and Voxraidgeneral), two with passwords (seekrit and notsoseekrit).

### /join

- `/join General`  
  would be used to join the channel called General
- `/join OurGuild:ourpassword`  
  would be used to join the channel called OurGuild, with a password of 'ourpassword'
- `/join General,OurGuild:ourpassword`  
  would be used to join multiple channels

### /leave

- `/leave NewPlayers`
- `/leave 1`

<!-- "See also" is required to be the last section-->
## See also
- [/autojoin](cmd-autojoin.md)
- [/say](cmd-say.md)
- [/shout](cmd-shout.md)
- [/gsay](cmd-gsay.md)
- [/guildsay](cmd-guildsay.md)
- [/tell](cmd-tell.md)
- [/auction](cmd-auction.md)
- [/ooc](cmd-ooc.md)
- [/channel](cmd-channel.md)
