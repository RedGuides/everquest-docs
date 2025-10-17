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
The /advloot command toggles the Advanced Loot System window. It can also set loot options for all items in the personal or shared loot lists.
<!--cmd-desc-end-->

## Loot Options

**personal setallto** `<loot option>`
:   Controls the personal loot list. setallto affects all items in the personal loot window.  
    Loot options: [loot | leave | aneed | agreed | never]  

**shared setallto** `<loot option>`
:   Controls the shared loot list. setallto affects all items in the shared loot window.  

    Loot options: [need | greed | no | aneed | agreed | never | ask | roll | askroll | autoaskroll | freegrab | leave | leaveall | `<PlayerName>`]  



!!! example "Examples"

    `/advloot personal setallto aneed`
    :   Adds a filter to all items in the personal loot window to "always need"

    `/advloot shared setallto agreed`
    :   Adds a filter to all items in the shared loot window to "always greed"

    `/advloot shared setallto odii`
    :   Will give all items in the shared window to the player "Odii"

## See also

- [Advloot Generator](https://www.redguides.com/community/advloot-gen)