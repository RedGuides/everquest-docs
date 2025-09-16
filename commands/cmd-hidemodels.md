---
tags:
  - command
---

# /hidemodels

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/hidemodels { players | pets | mercenaries | all } [ none | afk | afk noncombat | noncombat ]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Hide the specified models. Optionally, do so in certain situations.
<!--cmd-desc-end-->

## Options

**players** `[none | afk | afk noncombat | noncombat]`
:   Hide player models

**pets** `[none | afk | afk noncombat | noncombat]`
:   Hide pets models

**mercenaries** `[none | afk | afk noncombat | noncombat]`
:   Hide mercenary models

**all** `[none | afk | afk noncombat | noncombat]`
:   Hide all models

!!! example "Examples"

    `/hidemodels all none`
    :   Don't hide any models

    `/hidemodels players afk`
    :   Hide players when they're AFK

    `/hidemodels pets`
    :   Hide pet models

## See also

- [/hidecorpses](cmd-hidecorpses.md)
