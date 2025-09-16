---
tags:
  - command
---

# /loadskin

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/loadskin <foldername> <0|1>
```
<!--cmd-syntax-end-->
## Description

<!--cmd-desc-start-->
Opens the "Load a skin" window when used without arguments, or loads a specified skin from your EverQuest's `uifiles` folder.
<!--cmd-desc-end-->

## Options

**`<foldername>`**
:   The name of the folder in your `EverQuest\uifiles` directory. Default skins include `classic_spell_icons` and `default`.

**`<0|1>`**
:   Whether to use current INI file settings for the new skin.
    
    - `0` - do not use current INI settings
    - `1` - do use current INI settings

!!! example "`/loadskin default` - Load the default skin"