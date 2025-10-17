---
tags:
  - command
---

# /hidecorpse

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/hidecorpse [none | all | always | alwaysnpc | allbutgroup | npc | looted | listed | listedunlocked]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Controls the hiding of corpses in the game world. Your own corpse(s) will never be hidden.
<!--cmd-desc-end-->

## Options

**`none`**
:   Show all corpses.

**`all`**
:   Hide all corpses (including NPC corpses). Corpses created after this command will not be hidden.

**`always`**
:   Hide all current and future corpses (including NPC corpses).

**`alwaysnpc`**
:   Hide all current and future NPC corpses.

**`allbutgroup`**
:   Hide all corpses (including NPC corpses), except corpses of group members.

**`npc`**
:   Hide all corpses (including NPC corpses), except corpses of players.

**`looted`**
:   Hide corpses after you loot them.

**`listed`**
:   Hide advanced loot corpses you have access to.

**`listedunlocked`**
:   Hide advanced loot corpses unlocked to you.

## Notes

!!! note
    Your own corpse(s) will never be hidden. Any corpses created after use of this command will not be hidden (except when using `always` or `alwaysnpc`).

!!! warning
    The options `all`, `always`, `allbutgroup`, and `npc` hide NPC corpses too, not just player corpses!