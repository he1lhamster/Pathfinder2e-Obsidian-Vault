---
actions: '[two-actions]'
cost: null
element: null
frequency: null
id: '54'
name: Administer First Aid
rarity: Common
requirement: You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]]
  , or you are wearing themand have a hand free
rus_type_level: null
school: null
source: '[[DATABASE/source/Core Rulebook|Core Rulebook]]'
trait:
- '[[DATABASE/trait/Manipulate|Manipulate]]'
trigger: null
type: Action

---
# Administer First Aid <span class="action-icon">2</span>

<span class="item-trait">Manipulate</span>
**Source** [[DATABASE/source/Core Rulebook|Core Rulebook]] 
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]], or you are wearing them and have a hand free

---
You perform first aid on an adjacent creature that is dying or bleeding. If a creature is both dying and bleeding, choose which ailment you’re trying to treat before you roll. You can Administer First Aid again to attempt to remedy the other effect.

* **Stabilize** Attempt a Medicine check on a creature that has 0 Hit Points and the dying condition. The DC is equal to 5 + that creature’s recovery roll DC (typically 15 + its dying value). 
* **Stop Bleeding** Attempt a Medicine check on a creature that is taking [[DATABASE/condition/Persistent Damage|persistent]] bleed damage, giving them a chance to make another flat check to remove the persistent damage. The DC is usually the DC of the effect that caused the bleed.
**Success** If you’re trying to stabilize, the creature loses the dying condition (but remains unconscious). If you’re trying to stop bleeding, the creature attempts a flat check to end the bleeding.
**Critical Failure** If you were trying to stabilize, the creature’s dying value increases by 1. If you were trying to stop bleeding, it immediately takes an amount of damage equal to its persistent bleed damage.