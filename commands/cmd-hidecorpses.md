---
tags:
  - command
---

# /hidecorpses

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/hidecorpses [ none | all | always | alwaysnpc | allbutgroup | npc | looted | listed | listedunlocked ]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Will hide specified corpses. Your own corpses will never be hidden, except when using **always**.
<!--cmd-desc-end-->

## Options

**none**
:   Show all corpses.

**all**
:   Hide all corpses, except for your own.

**always**
:   Hide all and future corpses, including your own.

**alwaysnpc**
:   Hide all and future NPC corpses.

**allbutgroup**
:   Hide all except corpses of group members.

**npc**
:   Hide all, except for players.

**looted**
:   Hide corpses after you loot them.

**listed**
:   Hide [advanced loot](cmd-advloot.md) corpses you have access to.

**listedunlocked**
:   Hide [advanced loot](cmd-advloot.md) corpses unlocked to you.

## See also

- [/advloot](cmd-advloot.md)
- [/corpse](cmd-corpse.md)
- [/hidemodels](cmd-hidemodels.md)
