---
tags:
  - command
---

# /blockspell

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/blockspell [display | add | remove | clear] [me | pet] <spellnumber>...
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Toggle blocking beneficial spells from being cast on you or your pet. The blocklist is written to the `[BlockedSpells]` section of your `<character>`_`<server>`.ini
<!--cmd-desc-end-->

## Options

**display** `[me | pet]`
:   Outputs a list of blocked spells on you or your pet.

**add** `[me | pet] <spellnumber>...`
:   Adds the spell(s) to the blocklist on you or your pet.

**remove** `[me | pet] <spellnumber>...`
:   Removes the spell(s) from the blocklist on you or your pet.

**clear** `[me | pet]`
:   Clears the blocklist.

## Examples

!!! example "`/blockspell add me 1693 2517` - Will block spells 1693 (Clarity II) and 2517 (Spirit of Eagle) from being cast on you."

!!! example "`/blockspell display pet` - Will show a list of all spell currently blocked for your pet."

## See also

- [Hazimil's Blocking Buffs page](https://www.jaburt.com/eq/blocking.htm)
