---
tags:
  - command
---

# /bandolier

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/bandolier [add | delete | activate] <SetName>
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Add, delete, and activate sets of weapons.
<!--cmd-desc-end-->

## Options

**add** `<setname>`
:   Adds a new bandolier set with the name `setname`, using the weapons you're currently wielding.

**delete** `<setname>`
:   Deletes the bandolier set `setname`.

**activate** `<setname>`
:   Equips the bandolier set `setname`. Weapons currently held will drop to inventory.

## Examples

!!! example "`/bandolier add SwordBoard` - Adds the bandolier set with the name 'SwordBoard', using the weapons you're currently wielding."

!!! example "`/bandolier activate SwordBoard` - Equips the bandolier set 'SwordBoard'. Weapons you are currently holding drop to your inventory."

!!! example "Hotkey example, assuming you set ranged weapons as 'Pullmob':"
    ```ini
    /pause 5,/bandolier activate Pullmob
    /pause 5,/autofire on
    /pause 5,/autofire off
    /bandolier activate SwordBoard
    /g Incoming!
    ```

## See also
* For non-weapon slots, use [MQ2Bandolier](../../mq2bandolier/index.md).  
* For your own scripts, see the [bandolier](../../macroquest/reference/data-types/datatype-bandolier.md) data type.