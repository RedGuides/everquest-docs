---
tags:
  - command
---

# /grouproles

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/grouproles [ list | set | unset | roleset ] <options>
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Manage group roles, and create sets of roles you can load or unload for specific groups of characters.
<!--cmd-desc-end-->

## Options

**list**
:   Lists all the roles in the current group.

**set** `<player> <1-5>`
:   Sets the specified group member's role.  
    1. Main Tank  
    2. Main Assist  
    3. Puller  
    4. Mark NPC  
    5. Master Looter

**unset** `<player> [1-5]`
:   Unsets the specified group member's role.  
    1. Main Tank  
    2. Main Assist  
    3. Puller  
    4. Mark NPC  
    5. Master Looter

**roleset**
:   Lists the available role sets

**roleset save** `<setname>`
:   Saves the current group's roleset as `<setname>`

**roleset load** `<setname>`
:   Loads a previously saved group roleset.

**roleset delete** `<setname>`
:   Deletes a previously saved group roleset.

## Examples

!!! example "`/grouproles set bobby 1` - Sets bobby as Main Tank"

!!! example "`/grouproles unset bobby 3` - Unsets bobby as the Puller"

!!! example "`/grouproles roleset save xpgrind` - Saves the entire group's roleset as "xpgrind""
