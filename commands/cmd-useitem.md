---
tags:
  - command
---

# /useitem

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/useitem <slot> [subindex]
/useitem "<item name>"
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Activates the use effect on items. You can specify an inventory slot number or the "exact name" of the item. When using the item name, it activates the item regardless of its inventory slot, including items in your key ring.
<!--cmd-desc-end-->

## Options

**`<slot>`** `[subindex]`
:   The slot number. If a bag, the subindex as well.

**`"<item name>"`**
:   The full name of the item to activate. Works for items in any inventory slot or key ring.

## Examples

!!! example
    `/useitem "Stormguard's Iron Stud"` - Activates effect on the earring.

!!! example
    `/useitem 23 0` - Eats the Mushroom in the top-left slot of the first bag.

!!! example
    `/useitem "corrupted hammer of consternation"` - Activates the Corrupted Hammer of Consternation item.

## Slot numbers

A complete list of slot numbers can be found on [Slot names](../../macroquest/reference/general/slot-names.md).