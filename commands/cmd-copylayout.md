---
tags:
  - command
---

# /copylayout

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/copylayout [<layout> <inifile>] [restore]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
With no parameters, opens "Copy Layout" window. Otherwise it will copy the specified layout and INI file. Restore will copy the layout from your current INI and desktop resolution.
<!--cmd-desc-end-->

## Options

**`<layout> <inifile>`**
:   `<layout>` is the resolution whose layout you want copied over the current layout (for example 1280x1024) or "windowed" to copy the windowed mode layout. `<inifile>` is the filename for the UI_name_server.ini file or default.ini. If no INI file is provided, the current INI file will be used.

**restore**
:   Will copy the layout from your current INI file using the desktop's resolution.

## Examples

!!! example "`/copylayout Windowed UI_Odii_firiona.ini`"

!!! example "`/copylayout 1440x900 UI_Jobo_vox.ini`"