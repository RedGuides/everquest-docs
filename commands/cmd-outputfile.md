---
tags:
  - command
---

# /outputfile

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/outputfile [ achievements | faction | guild | guildbank | guildhall | inventory | missingspells | raid | realestate | recipes <argument> | spellbook ] [<filename>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Export data to the default or specified file. The file is saved as `<player>_<server>-<parameter>.txt` in the root folder.
<!--cmd-desc-end-->

## Options

**`achievements`**
:   Open, Complete, and Locked achievements

**`faction`**
:   

**`guild`**
:   Name, level, class, rank, date, zone, note

**`guildbank`**
:   

**`guildhall`**
:   You may only dump the real estate guild hall while you are on the guild plot or in the real estate guild hall.

**`inventory`**
:   

**`missingspells`**
:   

**`raid`**
:   

**`realestate`**
:   

**`recipes`** `[alchemy | baking | blacksmithing | brewing | fishing | fletching | jewelcrafting | poisonmaking | pottery | research | tailoring | tinkering] <[filename]>`
:   Specify the tradeskill type to export

**`spellbook`**
:   

## Examples

!!! example
    `/outputfile missingspells` - Exports missing spells to a file named `<charactername>_<server>-MissingSpells.txt`
