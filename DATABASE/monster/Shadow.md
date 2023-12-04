---
ac: '20'
alignment: CE
all_resistance: '5'
burrow_speed: null
charisma: '+3'
climb_speed: null
constitution: '+0'
creature_ability:
- Light Vulnerability
- Shadow Spawn
- Slink in Shadows
- Steal Shadow
creature_family: '[[DATABASE/monsterfamily/Shadow|Shadow]]'
description: 'The mysterious undead known as shadows lurk in dark places and feed
  on those who stray too far from the light. Those who parley with shadows, typically
  by keeping them at bay with a glowing weapon, may learn great secrets, for they
  are ideal spies.<br/><br/><b><u>Recall Knowledge - Undead</u> ( [[DATABASE/skill/Religion|Religion]]
  )</b>: DC 19<br/><b><u>Unspecific Lore</u></b>: DC 17<br/><b><u>Specific Lore</u></b>:
  DC 14'
dexterity: '+4'
element: null
fly_speed: '30'
fortitude: '+8'
hardness: null
hp: '40'
id: '362'
immunity:
- death effects
- disease
- paralyzed
- poison
- precision
- unconscious
intelligence: '-2'
land_speed: null
language:
- '[[DATABASE/language/Necril|Necril]]'
level: '4'
max_speed: '30'
name: Shadow
perception: '+10'
rarity: Common
reflex: '+14'
resistance:
- all 5 (except force
- ghost touch
- or positive; double resistance against non-magical)
rus_type_level: null
school: null
sense:
- darkvision
size: Medium
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +10'
- '[[DATABASE/skill/Stealth|Stealth]] +14'
source: '[[DATABASE/source/Bestiary|Bestiary]]'
speed:
- fly 30 feet
spell: null
strength: '-5'
strength_req: '-5'
strongest_save:
- Reflex
swim_speed: null
trait:
- '[[DATABASE/trait/Incorporeal|Incorporeal]]'
- '[[DATABASE/trait/Undead|Undead]]'
type: Creature
vision: Darkvision
weakest_save:
- Fortitude
weakness:
- light vulnerability
will: '+12'
wisdom: '+2'

---
# Shadow

The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light. Those who parley with shadows, typically by keeping them at bay with a glowing weapon, may learn great secrets, for they are ideal spies.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 19
**Unspecific Lore**: DC 17
**Specific Lore**: DC 14

# Shadow<span class="item-type">Creature 4</span>

<span class="trait-alignment item-trait">CE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Incorporeal</span><span class="item-trait">Undead</span>
**Source** [[DATABASE/source/Bestiary|Bestiary]]
**Perception** +10; darkvision
**Languages** [[DATABASE/language/Necril|Necril]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +10, [[DATABASE/skill/Stealth|Stealth]] +14
**Str** -5, **Dex** +4, **Con** +0, **Int** -2, **Wis** +2, **Cha** +3

---
**AC** 20; **Fort** +8, **Ref** +14, **Will** +12
**HP** 40; **Immunities** death effects, disease, paralyzed, poison, precision, unconscious; **Resistances** all 5 (except force, _ghost touch_, or positive; double resistance against non-magical); **Weaknesses** light vulnerability
<span class="in-box-ability">**Light Vulnerability** An object shedding magical light (such as from the _light_ spell) is treated as magical when used to attack the shadow.</span>

---
**Speed** fly 30 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> shadow hand +15 [+10/+5] (finesse, magical), **Damage** 2d6+3 negative
</span><span class="in-box-ability">**Shadow Spawn** When a creature’s shadow is pulled free by Steal Shadow, it becomes a shadow spawn under the command of the shadow that created it. This shadow spawn doesn’t have Steal Shadow and is perpetually and incurably [[DATABASE/condition/Clumsy|clumsy 2]]. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its enfeeblement, its shadow returns to it and the shadow spawn is extinguished.</span><span class="in-box-ability">**Slink in Shadows** The shadow can Hide or end its Sneak in a creature’s or object’s shadow.</span><span class="in-box-ability">**Steal Shadow** <span class="action-icon">1</span> (divine, necromancy) **Requirement** The shadow hit a living creature with a shadow hand Strike on its previous action. **Effect** The shadow pulls at the target’s shadow, making the creature [[DATABASE/condition/Enfeebled|enfeebled 1]]. This is cumulative with other [[DATABASE/condition/Enfeebled|enfeebled]] conditions from shadows, to a maximum of [[DATABASE/condition/Enfeebled|enfeebled 4]]. If this increases a creature’s [[DATABASE/condition/Enfeebled|enfeebled]] value to 3 or more, the target’s shadow is separated from its body (see shadow spawn). [[DATABASE/condition/Enfeebled|Enfeebled]] from Steal Shadow decreases by 1 every hour.</span>