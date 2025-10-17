---
tags:
  - command
---

# /pet

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/pet <action> [<target>]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Control actions for your combat pet. 
<!--cmd-desc-end-->

## Options

**attack** `[<name>]`
:   Pet will attack the targeted or specified creature.

**qattack** `[<name>]`
:   Pet will queue an attack on the targeted or specified creature.

**back**
:   Pet will clear its hatelist.

**focus**
:   Tells pet to focus on current target.

**feign**
:   A necromancer's pet will attempt to play dead, if they have the relevant AA.

**follow**
:   Pet will start to follow you.

**get lost** | **leave**
:   Pet will leave.

**guard here**
:   Will stand here, and return here after fights.

**guard me**
:   Pet will attack anything you attack and anything that attacks you.

**health report** | **report health**
:   Orders your pet to say its health in percent and any spells currently affecting it.

**ghold**
:   Greater holding. Will only attack something new if ordered, and will not build a hate list of other mobs. If told to attack, will do so in *reverse* order.

**hold**
:   Holding. Will not start attacks until ordered. Once it attacks, the pet will build a hate list and attack other mobs as usual.

**inventory check**
:   Returns a list of your pet's currently equipped items.

**inventory destroy** `<slot>`
:   Destroys the item your pet has in the chosen slot.

**leader**
:   Pet will report who summoned it.

**regroup**
:   Toggle. Pet returns to you whether its target is alive or not. Does not clear hatelist.

**resume**
:   

**stop**
:   Will stop attacking. Seems to trigger its resting regeneration.

**spellhold**
:   Toggle. Prevents pet from casting.

**sit**
:   Toggle sit.

**swarm**
:   Swarm attack.

**qswarm**
:   Queue swarm attack.

**swarmleave** | **swleave**
:   Causes the swarm to leave.

**target**
:   Targets your pet. Can also use F1 key (toggles between you and your pet).

**taunt** | **no taunt**
:   Toggles whether your pet will taunt in battle.

## Examples

!!! example
    `/pet inventory check` - Returns a list of your pet's currently equipped items.

!!! example
    `/pet inventory destroy <slot>` - Destroys the item your pet has in the chosen slot.