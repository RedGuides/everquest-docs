---
tags:
  - command
---

# /who

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/who [<name | class | race>] [all] [afk] [lfg] [corpse] [count] [guild] [raid] [<"guild name">] [<level> [<level>]]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Search for characters in the current zone or across all zones. The command can also be invoked on a player by clicking their name in a chat window.
<!--cmd-desc-end-->

## Options

**`<name | class | race>`**
:   Filter by a partial name, a class, or a race.

**all**
:   Search across all zones.

**afk**
:   Show players who are marked away from keyboard.

**lfg**
:   Show players who are looking for a group.

**corpse**
:   List your corpses in the current zone.

**count**
:   Show only the count of matches. Does not work with `all`.

**guild**
:   Show your guildmates in the current zone.

**raid**
:   Show players in your raid, including their level, class, name, and raid group.

**`<"guild name">`**
:   Show members of the specified guild (use quotes).

**`<level>`** `[<level>]`
:   Show players at a specific level or within a level range.

## Examples

!!! example "`/who all "the cool guild"` - Shows members of The Cool Guild across all zones"

!!! example "`/who 65 70` - Shows players within level 65 to 70 in your zone."

!!! example "`/who druid count` - Shows a count of druids in zone"

## See also

- [/whotarget](cmd-whotarget.md)