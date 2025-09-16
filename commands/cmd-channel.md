---
tags:
  - command
---

# /channel

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/channel [say | gsay | guildsay | tell | auction | ooc | chat] [<name>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Sets the default chat channel from "Say" to the option specified. In the case of "tell" or "chat", specify the name of the player or chatroom.
<!--cmd-desc-end-->

## Options

**say**
:   Sets the default chat channel to "[Say](cmd-say.md)".

**gsay**
:   Sets the default chat channel to "[Group Say](cmd-gsay.md)"

**guildsay**
:   Sets the default chat channel to "[Guild Say](cmd-guildsay.md)"

**tell** `<name>`
:   Sets the default chat channel to "[Tell](cmd-tell.md)". Must specify player name.

**auction**
:   Sets the default chat channel to "[Auction](cmd-auction.md)".

**ooc**
:   Sets the default chat channel to "[Out of Character](cmd-ooc.md)"

**chat** `<name>[:<password>]`
:   Sets the default chat channel to "[Chat](cmd-chat.md)". Must specific the name of a channel and if required, password.

## See also

- [/say](cmd-say.md)
- [/gsay](cmd-gsay.md)
- [/guildsay](cmd-guildsay.md)
- [/tell](cmd-tell.md)
- [/auction](cmd-auction.md)
- [/ooc](cmd-ooc.md)
- [/chat](cmd-chat.md)
