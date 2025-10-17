---
tags:
  - command
---

# /loginterval

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/loginterval [seconds]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Throttles log file writes by setting the interval between file operations to reduce frequent writes. A value of 0 disables throttling and writes immediately. The default interval is 1 second.
<!--cmd-desc-end-->