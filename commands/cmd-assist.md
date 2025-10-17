---
tags:
  - command
---

# /assist

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/assist [<name> | group | raid | main | on/off]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Assists a player or NPC, changing your current target to their target. All variants of the /assist command function at the same distance. Also toggles auto-attack on assist. If no option specified, it will assist your current target.
<!--cmd-desc-end-->

!!! note "The options 'group', 'raid', and 'main' prioritize the respective roles over player names that begin with those words."

## Options

**`<name>`**
:   The name of who you'd like to assist.

**group**
:   Will assist whoever is assigned "main assist" in your group.

**raid**
:   Will assist whoever is assigned "main assist" in your raid.

**main**
:   Will assist the nearest player who is assigned "main assist", whether group or raid.

**[on|off]**
:   Toggles auto-attack on assist.