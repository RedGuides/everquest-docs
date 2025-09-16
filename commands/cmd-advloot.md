---
tags:
  - command
---

# /advloot

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/advloot {personal | shared} setallto <loot option>
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
"/advloot" by itself will toggle the Advanced Loot window. It can also set loot options for all items in the personal or shared advanced loot window.
<!--cmd-desc-end-->

## Loot Options

**personal setallto** `<loot option>`
:   Controls the personal loot window, setallto affects all items in loot window.  

    Loot options: [loot | leave | aneed | agreed | never]

**shared setallto** `<loot option>`
:   Controls the shared loot window, setallto affects all items in loot window.  

    Loot options: [need | greed | no | aneed | agreed | never | ask | roll | askroll | autoaskroll | freegrab | leave | `<PlayerName>`]  

    `<PlayerName>` will give all items in the window to the specified player.

!!! example "Examples"

    `/advloot personal setallto aneed`
    :   Adds a filter to all items in the personal loot window to "always need"

    `/advloot shared setallto agreed`
    :   Adds a filter to all items in the shared loot window to "always greed"

    `/advloot shared setallto odii`
    :   Will give all items in the shared window to the player "Odii"

## See also

- [Advloot Generator](https://www.redguides.com/community/advloot-gen)