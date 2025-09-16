
# Chat Variables

EverQuest includes a few chat variables which are mostly useful for pronouns.

**%m**
::    Supposed to output the name of your target's pet, though doesn't work. Use MacroQuest's [`${Target.Pet}`](../../macroquest/reference/data-types/datatype-target.md) instead.

**%o**
::    Outputs the objective gender-specific pronoun of your target (Him, Her, It).

**%p**
::    Outputs the possessive gender-specific pronoun of your target (His, Her, Its).

**%r**
::    Outputs the race of your target, but only works on players. For NPCs, use MacroQuest's [`${Target.Race}`](../../macroquest/reference/data-types/datatype-target.md) instead.

**%s**
::    Outputs the subjective gender-specific pronoun for the target (He, She, It).

**%t**
::    Outputs the name of your current target.

!!! example "Example usage" 
    `/say Direct your focus upon %t and unleash your might upon %p!`  
    will output:  
    `You say, 'Direct your focus upon Lady Vox and unleash your might upon her!'`


