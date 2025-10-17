---
tags:
  - command
---

# /xtarget

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/xtarget show | set <slot> <role/name> | target <slot> | auto [on|off] | add | remove | save <name> | load <name>
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Add spawns to the Extended Target window by name, role, automatically, or from saved target sets. Common abbreviation: <span class=accent>/xtar</span>
<!--cmd-desc-end-->

## Options

**show**
:   Toggle the visiblity of the window

**set** `<slot> <role/name>`
:   assign a role, player, or NPC to a specific slot

**target** `<slot>`
:   select a target at a specific slot

**auto** `{on|off}`
:   Toggle auto-hater-targeting. Does not show any message upon command, check your `UI_<name>_<srv>.ini` to confirm `AutoAddHaters=0/1`

**add**
:   **add** current target to next available slot

**remove** `[target]`
:   **remove** last added target, or optionally remove targeted player from slots not using roles.

**load** `<name/id>`
:   Load a saved target set.

**save** `<name>`
:   Save the current target set.

## Examples

!!! example "`/xtar set 1 groupassisttarget` - Sets extended target 1 to the target of the group main assist (if MA has been set)."

!!! example "`/xtar Bobby` - Targets player regardless of range (in same zone)."

!!! example "`/xtarget target 7` - Select target at slot 7"

!!! example "`/xtarget remove target` - Removes targeted player from xtarget slots"

## See also

- [/rtarget](cmd-rtarget.md)
- [/target](cmd-target.md)
- [DataType:xtarget](../../macroquest/reference/data-types/datatype-xtarget.md)