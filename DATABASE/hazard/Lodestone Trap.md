---
ac: '18'
all_resistance: null
complexity: Complex
element: null
fortitude: '+11'
hardness: '8'
hazard_type: Trap
hp: 30 (BT 15)
id: '247'
immunity:
- critical hits
- object immunities
- precision damage
level: '2'
name: Lodestone Trap
rarity: Unique
reflex: '+5'
resistance: null
rus_type_level: null
school: null
source: '[[DATABASE/source/Crown of the Kobold King|Crown of the Kobold King]]'
trait:
- '[[DATABASE/trait/Complex|Complex]]'
- '[[DATABASE/trait/Magical|Magical]]'
- '[[DATABASE/trait/Trap|Trap]]'
- '[[DATABASE/trait/Unique|Unique]]'
type: Hazard
weakness: null
will: null

---
# Lodestone Trap<span class="item-type">Hazard 2</span>

<span class="trait-unique item-trait">Unique</span><span class="item-trait">Complex</span><span class="item-trait">Magical</span><span class="item-trait">Trap</span>
**Source** [[DATABASE/source/Crown of the Kobold King|Crown of the Kobold King]]
**Complexity** Complex
**Stealth** +8
**Description** The magical lodestone discharges bolts of electricity that also magnetize metal in the room.

---
**Disable** DC 18 [[DATABASE/skill/Thievery|Thievery]] to unhook the pressure plates from the trap, or [[DATABASE/spell/Dispel Magic|dispel magic]] (2nd level, counteract DC 18) to counteract the trap
**AC** 18, **Fort** +11, **Ref** +5
**Hardness** 8, **HP** 30 (BT 15); **Immunities** critical hits, object immunities, precision damage
**Magneto-Electric Pulse** <span class="action-icon">5</span> **Trigger** A single Medium or two or more Small creatures end their turn inside the room. **Effect** A pulse of electricity discharges from the lodestone to strike all four doors, with smaller arcs of electricity lancing out to strike all creatures in the room. The south and east doors slam shut, while the north and west doors fly open, releasing two [[DATABASE/monster/Vargouille|vargouilles]] into the room. All creatures in the room take 2d6 electricity damage (DC 18 basic Reflex save). The trap then rolls initiative.

---
**Routine** (1 action) On its initiative, the trap exerts a strong magnetic pull on the doors, causing the north and west doors to open if they're closed, or causing the south and east doors to close if they're open. A character can open or close a door against this pull with a successful DC 18 [[DATABASE/skill/Athletics|Athletics]] check to [[DATABASE/action/Force Open|Force Open]] the door. At the same time, any character in the room who wears primarily metal armor must attempt a DC 18 Reflex save (characters in medium metal armor suffer a –1 circumstance penalty to this save, and characters in heavy metal armor suffer a –2 circumstance penalty). 
**Critical Success** The PC is unaffected. 
**Success** The PC resists the pull but treats the room as difficult terrain. 
**Failure** The PC treats the room as difficult terrain and is knocked [[DATABASE/condition/Prone|prone]]. A PC who's already prone suffers a critical failure instead. 
**Critical Failure** As failure, but the PC is also pulled 5 feet toward the lodestone. A PC who is adjacent to the lodestone instead becomes stuck to it and is [[DATABASE/condition/Restrained|restrained]] as long as the trap continues its routine ([[DATABASE/action/Escape|Escape]] DC 18).

---
**Reset** At the end of a round in which there are no creatures standing on the floor or stuck to the lodestone, the trap deactivates. The vargouilles return to their alcoves, and the doors close. The trap resets automatically after 1 minute.