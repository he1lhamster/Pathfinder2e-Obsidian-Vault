---
ac: '20'
complexity: Complex
fortitude: '+13'
hardness: 20 Painting Hardness
hazard_type: Haunt
hp: 30 per square (6 squares must be destroyed to disable the haunt)
id: '81'
immunity:
- critical hits
- object immunities
- precision damage
level: '17'
name: Endless Elven Aging
rarity: Common
reflex: '+5'
source: '[[DATABASE/source/Pathfinder 149. Against the Scarlet Triad|Pathfinder #149:
  Against the Scarlet Triad]]'
trait:
- '[[DATABASE/trait/Complex|Complex]]'
- '[[DATABASE/trait/Haunt|Haunt]]'
- '[[DATABASE/trait/Magical|Magical]]'
type: Hazard

---
# Endless Elven Aging<span class="item-type">Hazard 17</span>

<span class="item-trait">Complex</span><span class="item-trait">Haunt</span><span class="item-trait">Magical</span>
**Source** [[DATABASE/source/Pathfinder 149. Against the Scarlet Triad|Pathfinder #149: Against the Scarlet Triad]]
**Complexity** Complex
**Stealth** +33 (master)
**Description** A haunted mural fascinates characters and swiftly drains their vitality.

---
**Disable** [[DATABASE/skill/Occultism|Occultism]] DC 38 (master) or [[DATABASE/skill/Religion|Religion]] DC 38 (master) to calm the restless energies and suppress the haunt for 1 hour; a critical success deactivates the haunt permanently.
**AC** 20, **Fort** +13, **Ref** +5
**Painting Hardness** 20, **Painting HP** 30 per square (6 squares must be destroyed to disable the haunt); **Immunities** critical hits, object immunities, precision damage
**Lifelike Scintillation** <span class="action-icon">5</span> (divination, occult) **Trigger** A living creature examines the mural or enters the room; **Effect** The haunt activates and rolls initiative.

---
**Routine** (2 actions) The haunt lures creatures into area A2 using Captivate. Any actions it hasn't used to Captivate are used to drain a living creature in the room with Live a Thousand Lives.
 **Captivate** <span class="action-icon">1</span> (charm, enchantment, incapacitation, mental, occult) The faintly moving images compel one creature within 30 feet of the room to move into the room. The creature attempts a DC 38 Will save.
**Success** The target is unaffected.
**Failure** The target must spend all its actions on its next turn moving into the room, and is then [[DATABASE/condition/Paralyzed|paralyzed]] until the end of its next turn.
**Critical Failure** As failure, and the target is also [[DATABASE/condition/Stupefied|stupefied 2]] for 1 minute.
 **Live a Thousand Lives** <span class="action-icon">1</span> (mental, occult) The haunt causes a living creature in the room to experience a full elven life, weathering every wound, misfortune, loss, and consequence of aging centuries in a matter of seconds. The target must attempt a DC 38 Fortitude save.
**Critical Success** The target is unaffected.
**Success** The target becomes [[DATABASE/condition/Fatigued|fatigued]].
**Failure** The target becomes [[DATABASE/condition/Drained|drained 1]] (or its drained value increases by 1, to a maximum of drained 3), and it is paralyzed until the end of its next turn.
**Critical Failure** As failure, but the target also becomes [[DATABASE/condition/Doomed|doomed 1]] (or its doomed value increases by 1).

---
**Reset** The haunt continues its routine until there are no targets within 30 feet of the room. It then resets over the course of 1 minute and is able to activate again.