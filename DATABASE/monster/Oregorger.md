﻿---
ac: '30'
burrow_speed: '20'
charisma: '+3'
constitution: '+7'
creature_ability:
- Caustic Rust
- Devour Metal
- Rust Vision
- Searing Spew
creature_family: '[[DATABASE/monsterfamily/Elemental, Metal|Elemental, Metal]]'
dexterity: '+2'
element: Metal
fly_speed: '20'
fortitude: '+24'
hp: '245'
id: '2653'
immunity:
- bleed
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/trait/Sleep|sleep]]'
intelligence: '-1'
land_speed: '30'
language:
- '[[DATABASE/language/Talican|Talican]]'
level: '11'
max_speed: '30'
name: Oregorger
perception: '+18'
rarity: Common
reflex: '+17'
resistance:
- '[[DATABASE/trait/Acid|acid]] 10'
- '[[DATABASE/trait/Electricity|electricity]] 10'
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
- rust vision
size: Large
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +17'
- '[[DATABASE/skill/Athletics|Athletics]] +25'
source: '[[DATABASE/source/Rage of Elements|Rage of Elements]]'
speed:
- 30 feet
- burrow 20 feet
- fly 20 feet
strength: '+8'
strength_req: '8'
strongest_save:
- Fortitude
trait:
- '[[DATABASE/trait/Elemental|Elemental]]'
- '[[DATABASE/trait/Metal|Metal]]'
type: Creature
vision: Darkvision
weakest_save:
- Reflex
will: '+20'
wisdom: '+3'

---
# Oregorger

Oregorgers are hulking, four-limbed brutes with bodies of raw primal metals accreted in layers. Driven entirely by an insatiable drive to consume metal, an oregorger stops at nothing to greedily devour as much metal as it can and expel it as caustic rust.
**Recall Knowledge - Elemental ([[DATABASE/skill/Arcana|Arcana]], [[DATABASE/skill/Nature|Nature]])**: DC 28
**Unspecific Lore**: DC 26
**Specific Lore**: DC 23

# Oregorger<span class="item-type">Creature 11</span>

<span class="trait-size item-trait">Large</span><span class="item-trait">Elemental</span><span class="item-trait">Metal</span>
**Source** [[DATABASE/source/Rage of Elements|Rage of Elements]]
**Perception** +18; [[DATABASE/monsterability/Darkvision|darkvision]], rust vision
**Languages** [[DATABASE/language/Talican|Talican]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +17, [[DATABASE/skill/Athletics|Athletics]] +25
**Str** +8, **Dex** +2, **Con** +7, **Int** -1, **Wis** +3, **Cha** +3
**Rust Vision** An oregorger ignores the [[DATABASE/condition/Concealed|concealed]] condition from rust clouds.

---
**AC** 30; **Fort** +24, **Ref** +17, **Will** +20
**HP** 245; **Immunities** bleed, [[DATABASE/condition/Paralyzed|paralyzed]], poison, sleep; **Resistances** acid 10, electricity 10
<span class="in-box-ability">**Caustic Rust** (acid, aura) 5 feet. The oregorger continually leaks tiny fragments of partially digested rust into the air around it. Any creature that ends its turn in the aura takes 2d6 acid damage with a DC 27 basic Reflex save. A creature that critically fails is also [[DATABASE/condition/Sickened|sickened 1]].</span>

---
**Speed** 30 feet, burrow 20 feet, fly 20 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> adamantine bite +23 [+18/+13] (reach 10 feet), **Damage** 2d12+12 piercing plus devour metal</span><span class="in-box-ability">**Melee** <span class="action-icon">1</span> claw +23 [+19/+15] (agile), **Damage** 2d6+12 slashing</span><span class="in-box-ability">**Devour Metal** Any time the oregorger scores a critical hit with an adamantine bite attack, it deals the same amount of damage to any metal armor worn by the target, automatically bypassing any Hardness lower than 10. If a creature uses the [[DATABASE/feat/Shield Block|Shield Block]] reaction with a metal shield against an oregorger's adamantine bite, the shield is automatically [[DATABASE/condition/Broken|broken]], but no other item takes damage from that attack. Unattended metal items automatically take full damage from an oregorger's adamantine bite attack, ignoring their Hardness if it's lower than 10.</span><span class="in-box-ability">**Searing Spew** <span class="action-icon">2</span> (acid) The oregorger belches forth a cloud of caustic, rusted debris from its maw, filling a cube adjacent to itself that's 10 feet on each side. Any creature in this area takes 6d6 acid damage and 6d6 slashing damage (DC 30 basic Reflex). The ground under the cloud is difficult terrain for 1 hour, after which the shrapnel crumbles to dust. The oregorger can't use Searing Spew again for 1d4 rounds, but the ability recharges if the oregorger damages an item with devour metal.</span>