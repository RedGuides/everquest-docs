---
tags:
  - command
---

# /random

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/random <#> [<#>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Rolls a magic die from 0 to `<#>`. Optionally add another `<#>` to specify the complete range.
<!--cmd-desc-end-->

## Options

**`<#>`** `[<#>]`
:   If one number is provided, it represents the upper bound, and 0 is the lower bound. If two numbers are provided, the first is lower bound, the second upper bound.


## Examples

!!! example "`/random 8 50` - Rolls for any number between 8 and 50."

!!! example "`/random 100` - Rolls between 0 and 100."