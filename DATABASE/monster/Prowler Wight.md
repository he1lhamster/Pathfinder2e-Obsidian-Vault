---
ac: '28'
alignment: LE
charisma: '+3'
constitution: '+2'
creature_ability:
- Drain Life
- Feign Death
- Final Spite
- Sneak Attack
- Spawn Prowler Wight
creature_family: '[[DATABASE/monsterfamily/Wight|Wight]]'
dexterity: '+5'
fortitude: '+17'
hp: 155 ( negative healing )
id: '1916'
immunity:
- '[[DATABASE/trait/Death|death]] effects'
- '[[DATABASE/trait/Disease|disease]]'
- '[[DATABASE/condition/Paralyzed|paralyzed]]'
- '[[DATABASE/trait/Poison|poison]]'
- '[[DATABASE/condition/Unconscious|unconscious]]'
intelligence: '+1'
land_speed: '25'
language:
- '[[DATABASE/language/Common|Common]]'
- '[[DATABASE/language/Necril|Necril]]'
level: '9'
max_speed: '25'
name: Prowler Wight
perception: '+18'
rarity: Uncommon
reflex: '+20'
sense:
- '[[DATABASE/monsterability/Darkvision|darkvision]]'
size: Medium
skill:
- '[[DATABASE/skill/Acrobatics|Acrobatics]] +18'
- '[[DATABASE/skill/Deception|Deception]] +18'
- '[[DATABASE/skill/Stealth|Stealth]] +20'
source: '[[DATABASE/source/Book of the Dead|Book of the Dead]]'
speed:
- 25 feet
strength: '+4'
strength_req: '4'
strongest_save:
- Reflex
trait:
- '[[DATABASE/trait/Uncommon|Uncommon]]'
- '[[DATABASE/trait/Undead|Undead]]'
- '[[DATABASE/trait/Wight|Wight]]'
type: Creature
vision: Darkvision
weakest_save:
- Will
will: '+16'
wisdom: '+3'

---
# Prowler Wight

Often found lurking in the dark, prowler wights wield subterfuge as their greatest weapon. They frequently feign death in old sewers, graveyards, and mausoleums, waiting for hapless victims to pass by before striking.
**Recall Knowledge - Undead ([[DATABASE/skill/Religion|Religion]])**: DC 28
**Unspecific Lore**: DC 26
**Specific Lore**: DC 23

# Prowler Wight<span class="item-type">Creature 9</span>

<span class="trait-uncommon item-trait">Uncommon</span><span class="trait-alignment item-trait">LE</span><span class="trait-size item-trait">Medium</span><span class="item-trait">Undead</span><span class="item-trait">Wight</span>
**Source** [[DATABASE/source/Book of the Dead|Book of the Dead]]
**Perception** +18; [[DATABASE/monsterability/Darkvision|darkvision]]
**Languages** [[DATABASE/language/Common|Common]], [[DATABASE/language/Necril|Necril]]
**Skills** [[DATABASE/skill/Acrobatics|Acrobatics]] +18, [[DATABASE/skill/Deception|Deception]] +18 (+20 to [[DATABASE/action/Feint|Feint]]), [[DATABASE/skill/Stealth|Stealth]] +20
**Str** +4, **Dex** +5, **Con** +2, **Int** +1, **Wis** +3, **Cha** +3
**Items** _+1 [[DATABASE/equipment/Striking|striking]] [[DATABASE/weapon/Dagger|dagger]]_, [[DATABASE/armor/Leather Armor|leather armor]]

---
**AC** 28; **Fort** +17, **Ref** +20, **Will** +16
**HP** 155 ([[DATABASE/monsterability/Negative Healing|negative healing]]); **Immunities** death effects, disease, [[DATABASE/condition/Paralyzed|paralyzed]], poison, [[DATABASE/condition/Unconscious|unconscious]]
<span class="in-box-ability">**Final Spite <span class="action-icon">5</span> ** **Trigger** The prowler wight is reduced to 0 Hit Points; **Effect** The prowler wight makes a Strike before being destroyed. They don't gain any temporary HP from drain life on this Strike.</span>

---
**Speed** 25 feet
<span class="in-box-ability">**Melee** <span class="action-icon">1</span> _dagger_ +21 [+17/+13] (agile, finesse, magical, versatile S), **Damage** 2d4+7 piercing plus drain life</span><span class="in-box-ability">**Melee** <span class="action-icon">1</span> claw +20 [+16/+12] (agile, finesse), **Damage** 1d8+7 slashing plus drain life</span><span class="in-box-ability">**Drain Life** (divine, necromancy) When the prowler wight damages a living creature using an unarmed attack or their bound weapon, they gain 9 temporary Hit Points, and the creature must succeed at a DC 25 Fortitude save or become [[DATABASE/condition/Drained|drained 1]]. Further damage dealt by the prowler wight's unarmed and bound weapon attacks increases the value of the drained condition by 1 on a failed save, to a maximum of drained 4.</span><span class="in-box-ability">**Feign Death** <span class="action-icon">1</span> (concentrate) The prowler wight quenches the telltale red glow in their eye sockets, falls [[DATABASE/condition/Prone|prone]], and lies completely still. Until the next time they act, the prowler wight appears to be an ordinary corpse. They have an automatic result of 38 on [[DATABASE/skill/Deception|Deception]] checks and DCs to pass as an ordinary corpse.</span><span class="in-box-ability">**[[DATABASE/monsterability/Sneak Attack|Sneak Attack]]** The prowler wight deals an additional 2d6 precision damage to [[DATABASE/condition/Flat-Footed|flat-footed]] creatures.</span><span class="in-box-ability">**Spawn Prowler Wight** (divine, necromancy) A living humanoid killed by a prowler wight's weapon or claw Strike rises as a prowler wight spawn after 1d4 rounds. This spawn is under the command of the prowler wight that killed them. They don't have drain life or spawn prowler wight and are [[DATABASE/condition/Clumsy|clumsy 2]] for as long as they're a prowler wight spawn. If the creator of the prowler wight spawn dies, the prowler wight spawn becomes a fully autonomous prowler wight; they regain their free will, gain drain life and spawn prowler wight, and are no longer clumsy.</span>