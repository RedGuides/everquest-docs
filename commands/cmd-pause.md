---
tags:
  - command
---

# /pause

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/pause <1-600>[,]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Pause a [social macro](cmd-hotbutton.md) from 1 to 600 deciseconds. Can add other commands with a comma, but will always be executed last. Can only be used within social buttons.
<!--cmd-desc-end-->

## Options

**`<1-600>`**
:   Deciseconds. 600 is equal to 60 seconds.

**`<1-600>,<command>`**
:   The pause will always be executed **after** `<command>`

## Examples

Both of these socials have a 5 second pause before the `/echo`. 

```eqcommand
/sit off
/cast 3
/pause 50
/echo 5 second pause is over
```

```eqcommand
/sit off
/pause 50, /cast 3
/echo 5 second pause is over
```

!!! warning "*/pause is always parsed last even when it appears first!*"

## See also

- [/hotbutton](cmd-hotbutton.md)
- [/timed](../../macroquest/reference/commands/timed.md)
- [/delay](../../macroquest/reference/commands/delay.md)
