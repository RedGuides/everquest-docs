---
tags:
  - command
---

# /autojoin

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/autojoin [add | remove] <channel1>[:<password>] [,<channel2>] ... [,<channel10>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Always join a channel or up to 10 channels every session, information is saved to eqclient.ini as `ChannelAutoJoin=`
<!--cmd-desc-end-->

## Options

**[add | remove]** `<channel>[:<password>],...<channel10>[:<password>]`
:   Will add/replace a channel to the existing list, or remove a channel from the existing list. To join multiple, separate each channel with a comma.

## Examples

!!! example "`/autojoin Bard` - Will join the channel 'Bard' every session."

!!! example "`/autojoin raidhealz:ourpass` - Will join the channel 'raidhealz' with the password 'ourpass' every session."

!!! example "`/autojoin Bard,raidhealz:ourpass,redguides:funtime` - Will join the channels 'Bard', 'raidhealz' with the password 'ourpass', and 'redguides' with the password 'funtime' every session."

## See also

- [/chat](cmd-chat.md)
