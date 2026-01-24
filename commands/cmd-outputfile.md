---
tags:
  - command
---

# /outputfile

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/outputfile [ achievements [<filter>] | faction | guild | guildbank | guildhall | guildlobby | inventory | missingspells | raid | realestate | recipes <argument> | spellbook ] [<filename>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Export data to the default or specified file. The file is saved as `<player>_<server>-<parameter>.txt` in the root folder. If a filename is specified and does not end with '.txt', the extension is automatically appended.
<!--cmd-desc-end-->

## Options

**`achievements`** `[<filter>]`
:   Outputs a filtered list of achievements. The filter specifies which states to include: Complete, Open, and/or Locked. If no filter is provided, all states are included.

**`faction`**
:   Faction data

**`guild`**
:   Name, level, class, rank, date, zone, note

**`guildbank`**
:   Guild bank contents

**`guildhall`**
:   You may only dump the real estate guild hall while you are on the guild plot or in the real estate guild hall.

**`guildlobby`**
:   Exports data for the Guild Lobby.

**`inventory`**
:   Inventory items, items from all keyrings, Dragon's Hoard items if the Dragon's Hoard window is open, and Personal Tradeskill Depot items if the depot is loaded.

**`missingspells`**
:   Outputs a list of all spells and combat abilities usable by your class up to your current level that you haven't yet scribed in your spellbook. Entries are sorted by level and then alphabetically by name. Does not include spells that cannot be scribed.

**`raid`**
:   Raid data

**`realestate`**
:   Real estate data

**`recipes`** `[alchemy | baking | blacksmithing | brewing | fishing | fletching | jewelcrafting | poisonmaking | pottery | research | tailoring | tinkering] <[filename]>`
:   Outputs the names of tradeskill recipes you know if they qualify you for additional skill points past the cap.

**`spellbook`**
:   Outputs all spells and combat abilities in your spell book. Entries are sorted by level and then alphabetically by name.

## Examples

!!! example
    `/outputfile missingspells` - Exports missing spells to a file named `<charactername>_<server>-MissingSpells.txt`