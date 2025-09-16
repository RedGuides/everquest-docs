---
tags:
  - command
---

# /alternateadv

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/alternateadv {on <#> | off | list | activate <#> | buy | buyall}
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Use, list, or purchase Alternate Advancements (AA). This can also be carried out in the Alternate Advancement window (found in the Inventory window.) Commonly abbreviated: `/alt`, `/alt act`
<!--cmd-desc-end-->

## Options

| Option | Description |
|--------|-------------|
| `On <#>` | Sets the level of experience gained going towards AA at 100%, unless you specify a different percentage. |
| `Off` | All experience gained will be set to go towards your normal experience bar. Experience to AA will be 0%. |
| `List` | Provides a list of all Alternate Advancement (AA) abilities available to this character; their respective number, title, description, and AA (point) cost per level. |
| `Activate <#>` | The command `/alternateadv act #` can be used to activate an AA ability using its corresponding AA number. Abbreviated: `act` |
| `Buy <#>` | This option is used to buy AA points in a specified AA ability group (the same ID used for alt activate, the one found with "list") |
| `Buyall <#>` | This option is used to buy out the entire AA ability group specified, assuming you have enough points. |

## Examples

The command `/alternateadv on 50`, would set the amount of experience gained going towards AA at 50%

The command `/alternateadv list`, could provide a list such as:

```text
Ability #1: Innate Eminence
Description: This passive ability increases your your strength, stamina, agility, dexterity, wisdom, intelligence, and charisma by 2 points.
Cost per Level: 7

Ability #8: Innate Spell Resistance
Description: This passive ability improves your cold, disease, fire, magic, and poison resistances by 2 points.
Cost per Level: 5

Ability #119: Mental Clarity
Description: This passive ability increases your mana regeneration by 1 point.
```

Note: this is an example AA List and has been truncated for example purposes. Turn your [/log on](cmd-log.md) and open in notepad to easily search the list.
