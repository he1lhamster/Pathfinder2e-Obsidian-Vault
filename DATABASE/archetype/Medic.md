---
id: '69'
level: '2'
name: Medic
prerequisite: Trained in [[DATABASE/skill/Medicine|Medicine]] ; [[DATABASE/feat/Battle
  Medicine|Battle Medicine]]
rarity: Common
source: '[[DATABASE/source/Advanced Player''s Guide|Advanced Player''s Guide]]'
type: Archetype

---
# Medic

**Source** [[DATABASE/source/Advanced Player's Guide|Advanced Player's Guide]] 
You've studied countless techniques for providing medical aid, making you a peerless doctor and healer.

## [[DATABASE/feat/Medic Dedication|Medic Dedication]] <span class="item-type">Feat 2</span>

<span class="item-trait">Archetype</span><span class="item-trait">Dedication</span>
**Source** [[DATABASE/source/Advanced Player's Guide|Advanced Player's Guide]] 
**Archetype** [[DATABASE/archetype/Medic|Medic]]
**Prerequisites** trained in [[DATABASE/skill/Medicine|Medicine]]; [[DATABASE/feat/Battle Medicine|Battle Medicine]]

---
You become an expert in [[DATABASE/skill/Medicine|Medicine]]. When you succeed with [[DATABASE/feat/Battle Medicine|Battle Medicine]] or [[DATABASE/action/Treat Wounds|Treat Wounds]], the target regains 5 additional HP at DC 20, 10 HP at DC 30, or 15 HP at DC 40. Once per day, you can use Battle Medicine on a creature that's temporarily immune. If you're a master in Medicine, you can do so once per hour.
**Special** You can't select another dedication feat until you gain two other feats from the medic archetype.

## [[DATABASE/feat/Doctor's Visitation|Doctor's Visitation]] <span class="action-icon">1</span> or <span class="action-icon">2</span> <span class="item-type">Feat 4</span>

<span class="item-trait">Archetype</span><span class="item-trait">Flourish</span>
**Source** [[DATABASE/source/Advanced Player's Guide|Advanced Player's Guide]] 
**Archetype** [[DATABASE/archetype/Medic|Medic]]
**Prerequisites** [[DATABASE/feat/Medic Dedication|Medic Dedication]]

---
You move to provide immediate care to those who need it. Stride, then use one of the following: [[DATABASE/feat/Battle Medicine|Battle Medicine]] or [[DATABASE/action/Treat Poison|Treat Poison]]. You can spend a second action to instead Stride and then [[DATABASE/action/Administer First Aid|Administer First Aid]] or [[DATABASE/feat/Treat Condition|Treat a Condition]] (if you have it).

## [[DATABASE/feat/Treat Condition|Treat Condition]] <span class="action-icon">2</span> <span class="item-type">Feat 4</span>

<span class="item-trait">Archetype</span><span class="item-trait">Healing</span><span class="item-trait">Manipulate</span><span class="item-trait">Skill</span>
**Source** [[DATABASE/source/Advanced Player's Guide|Advanced Player's Guide]] 
**Archetype** [[DATABASE/archetype/Medic|Medic]]
**Prerequisites** [[DATABASE/feat/Medic Dedication|Medic Dedication]]
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]], or you are wearing them and have a hand free.

---
You treat an adjacent creature in an attempt to reduce the [[DATABASE/condition/Clumsy|clumsy]], [[DATABASE/condition/Enfeebled|enfeebled]], or [[DATABASE/condition/Sickened|sickened]] condition. If a creature has multiple conditions from this list, choose one. Attempt a counteract check against the condition, using your [[DATABASE/skill/Medicine|Medicine]] modifier as your counteract modifier and the condition's source to determine the DC. You can't treat a condition that came from an artifact or effect above 20th level unless you have [[DATABASE/feat/Legendary Medic|Legendary Medic]]; even if you do, the counteract DC increases by 10. Treating a Condition that is continually applied under certain circumstances (for instance, the enfeebled condition a good character gains from carrying an [[DATABASE/equipment/Unholy|unholy]] weapon) has no effect as long as the circumstances continue.
**Critical Success** Reduce the condition value by 2.
**Success** Reduce the condition value by 1.
**Critical Failure** Increase the condition value by 1.

## [[DATABASE/feat/Holistic Care|Holistic Care]] <span class="item-type">Feat 6</span>

<span class="item-trait">Archetype</span><span class="item-trait">Skill</span>
**Source** [[DATABASE/source/Advanced Player's Guide|Advanced Player's Guide]] 
**Archetype** [[DATABASE/archetype/Medic|Medic]]
**Prerequisites** trained in [[DATABASE/skill/Diplomacy|Diplomacy]]; [[DATABASE/feat/Treat Condition|Treat Condition]]

---
You provide emotional and spiritual care. Add [[DATABASE/condition/Frightened|frightened]], [[DATABASE/condition/Stupefied|stupefied]], and [[DATABASE/condition/Stunned|stunned]] to the list of conditions you can reduce with [[DATABASE/feat/Treat Condition|Treat Condition]]. If the stunned condition has a duration instead of a value, you can't use Treat Condition to reduce it.

## [[DATABASE/feat/Preventative Treatment|Preventative Treatment]] <span class="item-type">Feat 8</span>

<span class="trait-uncommon item-trait">Uncommon</span><span class="item-trait">Archetype</span><span class="item-trait">Secret</span>
**Source** [[DATABASE/source/Knights of Lastwall|Knights of Lastwall]]
**Archetype** [[DATABASE/archetype/Medic|Medic]]
**Prerequisites** [[DATABASE/feat/Medic Dedication|Medic Dedication]]; [[DATABASE/feat/Treat Condition|Treat Condition]]
**Access** Knights of Lastwall have access to this feat.

---
You provide preventative remedies and care to help your patient fight off future maladies. You Treat a Condition the target doesn't yet have, naming any condition you could normally treat with Treat Condition. The counteract check gains the secret trait, so the GM rolls it secretly. The next time within the next minute the creature would be affected by that condition, your treatment immediately attempts to reduce the condition value with the effects of Treat Condition, using the secret roll result for the check. Preventative Treatment lasts on a creature for 1 minute, until the treatment is used, or until you use Preventative Treatment again on that creature, whichever comes first.

## [[DATABASE/feat/Resuscitate|Resuscitate]] <span class="action-icon">3</span> <span class="item-type">Feat 16</span>

<span class="item-trait">Archetype</span><span class="item-trait">Healing</span><span class="item-trait">Manipulate</span>
**Source** [[DATABASE/source/Advanced Player's Guide|Advanced Player's Guide]] 
**Archetype** [[DATABASE/archetype/Medic|Medic]]
**Prerequisites** [[DATABASE/feat/Medic Dedication|Medic Dedication]]; legendary in [[DATABASE/skill/Medicine|Medicine]]
**Requirements** You are holding [[DATABASE/equipment/Healer's Tools|healer's tools]] or are wearing them and have a hand free. Also, the target's body is mostly intact.

---
You can use [[DATABASE/skill/Medicine|Medicine]] to resuscitate the dead. Attempt a DC 40 Medicine check to revive a dead creature that has been dead for no more than 3 rounds. If you succeed, the target returns to life with the effects of [[DATABASE/spell/Raise Dead|raise dead]], except it still has the [[DATABASE/condition/Wounded|wounded]] condition it had before [[DATABASE/condition/Dying|dying]], increased by 1 (or wounded 1 if it wasn't wounded before dying). Whether you succeed or fail, the target is temporarily immune to Resuscitate for 1 day.