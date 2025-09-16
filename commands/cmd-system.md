---
tags:
  - command
---

# /system

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/system <cmd> [arguments]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Run commands on your computer, as if from the *Windows* command prompt. To use, `EnableSystemCommand=1` must be set in the `[default]` section of eqclient.ini
<!--cmd-desc-end-->

## Examples

!!! example "`/system notepad c:\myfile.txt` - Will open the notepad program, which will ask if you'd like to create 'myfile.txt'"
