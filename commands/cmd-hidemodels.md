---
tags:
  - command
---

# /hidemodels

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/hidemodels { none | players | pets | mercenaries | familiars | all } [ none | afk | afk noncombat | noncombat ]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Hide or un-hide the specified models based on conditions. 
<!--cmd-desc-end-->

## Options

**none**
:   Un-hide all players, pets, mercenaries, and familiars.

**players** `[none | afk | afk noncombat | noncombat]`
:   Hide player models

**pets** `[none | afk | afk noncombat | noncombat]`
:   Hide pets models

**mercenaries** `[none | afk | afk noncombat | noncombat]`
:   Hide mercenary models

**familiars** `[none | afk | afk noncombat | noncombat]`
:   Hide familiar models

**all** `[none | afk | afk noncombat | noncombat]`
:   Hide all models, including players, pets, mercenaries, and familiars.

## Examples

!!! example
    `/hidemodels all none` - Don't hide any models

    `/hidemodels players afk` - Hide players when they're AFK

    `/hidemodels pets` - Hide pet models

## See also

- [/hidecorpses](cmd-hidecorpses.md)