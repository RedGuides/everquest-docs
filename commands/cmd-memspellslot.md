---
tags:
  - command
---

# /memspellslot

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/memspellslot <gem slot> {<spell name>|<spell #>}
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
In the specified gem slot, memorize a spell. Can use spell name or ID number. To forget a gem slot, provide a "0" for spell.
<!--cmd-desc-end-->

## Options

**`<gem slot>`**
:   See your gem slot window. By default, 1 is at the top.

**`<spell name>`**
:   The name of the spell

**`<spell id>`**
:   The ID of the spell, best to look it up on lucy.

!!! example
    `/memspellslot 2 Lifetap` Will memorize Lifetap in the #2 gem slot.

## See also

- [/memspellset](cmd-memspellset.md)