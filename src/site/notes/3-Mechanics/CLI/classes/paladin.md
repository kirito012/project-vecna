---
{"dg-publish":true,"permalink":"/3-mechanics/cli/classes/paladin/","tags":["ttrpg-cli/class/paladin","ttrpg-cli/compendium/src/5e/phb"],"noteIcon":""}
---

# Paladin
*Source: Player's Handbook p. 82. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='3'></th><th colspan='5'>Spell Slots per Spell Level</th></tr>
> <tr class="class-progression"><th class="level">Level</th><th class="pb">PB</th><th class="feature">Features</th><th class="spellSlot">1st</th><th class="spellSlot">2nd</th><th class="spellSlot">3rd</th><th class="spellSlot">4th</th><th class="spellSlot">5th</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class="level">1st</td><td class="pb">+2</td><td class="feature"><a href='#Divine Sense (Level 1)' class='internal-link'>Divine Sense</a>, <a href='#Lay on Hands (Level 1)' class='internal-link'>Lay on Hands</a></td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">2nd</td><td class="pb">+2</td><td class="feature"><a href='#Divine Smite (Level 2)' class='internal-link'>Divine Smite</a>, <a href='#Fighting Style (Level 2)' class='internal-link'>Fighting Style</a>, <a href='#Spellcasting (Level 2)' class='internal-link'>Spellcasting</a></td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">3rd</td><td class="pb">+2</td><td class="feature"><a href='#Divine Health (Level 3)' class='internal-link'>Divine Health</a>, <a href='#Sacred Oath (Level 3)' class='internal-link'>Sacred Oath</a></td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">4th</td><td class="pb">+2</td><td class="feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a>, <a href='#Martial Versatility (Level 4)' class='internal-link'>Martial Versatility</a></td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">5th</td><td class="pb">+3</td><td class="feature"><a href='#Extra Attack (Level 5)' class='internal-link'>Extra Attack</a></td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">6th</td><td class="pb">+3</td><td class="feature"><a href='#Aura of Protection (Level 6)' class='internal-link'>Aura of Protection</a></td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">7th</td><td class="pb">+3</td><td class="feature"><a href='#Sacred Oath feature (Level 7)' class='internal-link'>Sacred Oath feature</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">8th</td><td class="pb">+3</td><td class="feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">9th</td><td class="pb">+4</td><td class="feature"></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">10th</td><td class="pb">+4</td><td class="feature"><a href='#Aura of Courage (Level 10)' class='internal-link'>Aura of Courage</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">11th</td><td class="pb">+4</td><td class="feature"><a href='#Improved Divine Smite (Level 11)' class='internal-link'>Improved Divine Smite</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">12th</td><td class="pb">+4</td><td class="feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">13th</td><td class="pb">+5</td><td class="feature"></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">14th</td><td class="pb">+5</td><td class="feature"><a href='#Cleansing Touch (Level 14)' class='internal-link'>Cleansing Touch</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">15th</td><td class="pb">+5</td><td class="feature"><a href='#Sacred Oath feature (Level 15)' class='internal-link'>Sacred Oath feature</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">16th</td><td class="pb">+5</td><td class="feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">17th</td><td class="pb">+6</td><td class="feature"></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class="level">18th</td><td class="pb">+6</td><td class="feature"><a href='#Aura improvements (Level 18)' class='internal-link'>Aura improvements</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class="level">19th</td><td class="pb">+6</td><td class="feature"><a href='#Ability Score Improvement (Level 19)' class='internal-link'>Ability Score Improvement</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td></tr>
> <tr class="class-progression"><td class="level">20th</td><td class="pb">+6</td><td class="feature"><a href='#Sacred Oath feature (Level 20)' class='internal-link'>Sacred Oath feature</a></td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td></tr>
> </tbody></table>
{ #class-progression}


## Hit Points

- **Hit Dice**: 1d10 per Paladin level
- **Hit Points at First Level:** 10 + CON
- **Hit Points at Higher Levels:** add 6 OR 1d10 + CON  (minimum of 1)

## Starting Paladin

- **Saving Throws**: Charisma, Wisdom
- **Armor**: [light armor](3-Mechanics/CLI/rules/item-types.md#Light%20Armor), [medium armor](3-Mechanics/CLI/rules/item-types.md#Medium%20Armor), [heavy armor](3-Mechanics/CLI/rules/item-types.md#Heavy%20Armor), [shields](3-Mechanics/CLI/items/shield.md)
- **Weapons**: simple weapons, martial weapons
- **Tools**: none
- **Skills**: choose 2 from [Athletics](3-Mechanics/CLI/rules/skills.md#Athletics), [Insight](3-Mechanics/CLI/rules/skills.md#Insight), [Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation), [Medicine](3-Mechanics/CLI/rules/skills.md#Medicine), [Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion), and [Religion](3-Mechanics/CLI/rules/skills.md#Religion)

You start with the following items, plus anything provided by your background.

- (a) a martial weapon and a [shield](3-Mechanics/CLI/items/shield.md) or (b) two martial weapons
- (a) five [javelins](3-Mechanics/CLI/items/javelin.md) or (b) any simple melee weapon
- (a) a [priest's pack](3-Mechanics/CLI/items/priests-pack.md) or (b) an [explorer's pack](3-Mechanics/CLI/items/explorers-pack.md)
- [Chain mail](3-Mechanics/CLI/items/chain-mail.md) and a [holy symbol](3-Mechanics/CLI/items/holy-symbol.md)

Alternatively, you may start with 5d4 × 10 gp to buy your own equipment.

## Multiclassing Paladin

**Ability Score Minimum:** Charisma 13, Strength 13

When you gain a level in a class other than your first, you gain only some of that class's starting proficiencies.

- **Armor**: [light armor](3-Mechanics/CLI/rules/item-types.md#Light%20Armor), [medium armor](3-Mechanics/CLI/rules/item-types.md#Medium%20Armor), [shields](3-Mechanics/CLI/items/shield.md)
- **Weapons**: simple weapons, martial weapons

## Paladin

Clad in plate armor that gleams in the sunlight despite the dust and grime of long travel, a human lays down her sword and shield and places her hands on a mortally wounded man. Divine radiance shines from her hands, the man's wounds knit closed, and his eyes open wide with amazement.

A dwarf crouches behind an outcrop, his black cloak making him nearly invisible in the night, and watches an orc war band celebrating its recent victory. Silently, he stalks into their midst and whispers an oath, and two orcs are dead before they even realize he is there.

Silver hair shining in a shaft of light that seems to illuminate only him, an elf laughs with exultation. His spear flashes like his eyes as he jabs again and again at a twisted giant, until at last his light overcomes its hideous darkness.

Whatever their origin and their mission, paladins are united by their oaths to stand against the forces of evil. Whether sworn before a god's altar and the witness of a priest, in a sacred glade before nature spirits and fey beings, or in a moment of desperation and grief with the dead as the only witness, a paladin's oath is a powerful bond. It is a source of power that turns a devout warrior into a blessed champion.

### The Cause of Righteousness

A paladin swears to uphold justice and righteousness, to stand with the good things of the world against the encroaching darkness, and to hunt the forces of evil wherever they lurk. Different paladins focus on various aspects of the cause of righteousness, but all are bound by the oaths that grant them power to do their sacred work. Although many paladins are devoted to gods of good, a paladin's power comes as much from a commitment to justice itself as it does from a god.

Paladins train for years to learn the skills of combat, mastering a variety of weapons and armor. Even so, their martial skills are secondary to the magical power they wield: power to heal the sick and injured, to smite the wicked and the undead, and to protect the innocent and those who join them in the fight for justice.

### Beyond the Mundane Life

Almost by definition, the life of a paladin is an adventuring life. Unless a lasting injury has taken him or her away from adventuring for a time, every paladin lives on the front lines of the cosmic struggle against evil. Fighters are rare enough among the ranks of the militias and armies of the world, but even fewer people can claim the true calling of a paladin. When they do receive the call, these warriors turn from their former occupations and take up arms to fight evil. Sometimes their oaths lead them into the service of the crown as leaders of elite groups of knights, but even then their loyalty is first to the cause of righteousness, not to crown and country.

Adventuring paladins take their work seriously. A delve into an ancient ruin or dusty crypt can be a quest driven by a higher purpose than the acquisition of treasure. Evil lurks in dungeons and primeval forests, and even the smallest victory against it can tilt the cosmic balance away from oblivion.

### Creating a Paladin

The most important aspect of a paladin character is the nature of his or her holy quest. Although the class features related to your oath don't appear until you reach 3rd level, plan ahead for that choice by reading the oath descriptions at the end of the class. Are you a devoted servant of good, loyal to the gods of justice and honor, a holy knight in shining armor venturing forth to smite evil? Are you a glorious champion of the light, cherishing everything beautiful that stands against the shadow, a knight whose oath descends from traditions older than many of the gods? Or are you an embittered loner sworn to take vengeance on those who have done great evil, sent as an angel of death by the gods or driven by your need for revenge? Appendix B lists many deities worshiped by paladins throughout the multiverse, such as Torm, Tyr, Heironeous, Paladine, Kiri-Jolith, Dol Arrah, the Silver Flame, Bahamut, Athena, Re-Horakhty, and Heimdall.

How did you experience your call to serve as a paladin? Did you hear a whisper from an unseen god or angel while you were at prayer? Did another paladin sense the potential within you and decide to train you as a squire? Or did some terrible event—the destruction of your home, perhaps—drive you to your quests? Perhaps you stumbled into a sacred grove or a hidden elven enclave and found yourself called to protect all such refuges of goodness and beauty. Or you might have known from your earliest memories that the paladin's life was your calling, almost as if you had been sent into the world with that purpose stamped on your soul.

As guardians against the forces of wickedness, paladins are rarely of any evil alignment. Most of them walk the paths of charity and justice. Consider how your alignment colors the way you pursue your holy quest and the manner in which you conduct yourself before gods and mortals. Your oath and alignment might be in harmony, or your oath might represent standards of behavior that you have not yet attained.

#### Quick Build

You can make a paladin quickly by following these suggestions. First, Strength should be your highest ability score, followed by Charisma. Second, choose the [noble](3-Mechanics/CLI/backgrounds/noble.md) background.

> [!quote] A quote from Isteval  
> 
> The true worth of a paladin is measured not in foes defeated or dungeons plundered. It is measured in lives saved and hearts turned to the causes of mercy and justice.

A paladin is a living embodiment of an oath—a promise or a vow made manifest in the person of a holy warrior who has the skill and the determination to see the cause through to the end. Some paladins devote themselves expressly to protecting the innocent and spreading justice in the world, while others resolve to attain that goal by conquering those who stand defiant and bringing them under the rule of law.

Although no paladin in the world could be described as typical, a number of them are narrow-minded do-gooders who refuse to tolerate even the smallest deviation from their own outlook. Paladins who take up the adventuring life, however, rarely remain so rigid in their attitudes—if only to keep from alienating their companions.

You can flesh out your paladin character by using the suggestions below. It's important to keep in mind that most paladins aren't robots. They have doubts and prejudices and harbor contradictory thoughts just as any other character does. Some are compelled by an internal motivation that might sometimes be at odds with the principles of their oaths.

## Personal Goal
_Source: Xanathar's Guide to Everything_

The precepts of a paladin's oath provide purpose to the character and dictate an ultimate goal or an overall intent that the paladin abides by and advances. Aside from that, some paladins are driven by a personal goal that either complements or transcends the dictates of their oaths. Paladins who swear different oaths might have the same personal goal, differing only in how they apply that goal to their actions when upholding their oaths.

If your paladin character has a personal goal, it might be drawn from some life event and thus not directly tied to the oath.

**Personal Goal**

`dice: [](paladin.md#^personal-goal)`

| dice: d6 | Personal Goal |
|----------|---------------|
| 1 | Peace. You fight so that future generations will not have to. |
| 2 | Revenge. Your oath is the vehicle through which you will right an ancient wrong. |
| 3 | Duty. You will live up to what you have sworn to do, or die trying. |
| 4 | Leadership. You will win a great battle that bards will sing about, and in so doing, you will become an example to inspire others. |
| 5 | Faith. You know your path is righteous, or else the gods would not have set you upon it. |
| 6 | Glory. You will lead the world into a grand new era, one that will be branded with your name. |{ #personal-goal}


## Symbol
_Source: Xanathar's Guide to Everything_

Paladins are mindful of the influence of symbols, and many of them adopt or design an artistic device that bears a distinctive image. Your symbol exemplifies the oath you have taken and communicates that message to those around you, friend and foe alike.

Your symbol might be displayed on a banner, a flag, or your clothing for all to see. Or it could be less obvious, such as a trinket or a token that you carry concealed on your person.

**Symbol**

`dice: [](paladin.md#^symbol)`

| dice: d6 | Symbol |
|----------|--------|
| 1 | A dragon, emblematic of your nobility in peace and your ferocity in combat |
| 2 | A clenched fist, because you are always ready to fight for your beliefs |
| 3 | An upraised open hand, indicating your preference for diplomacy over combat |
| 4 | A red heart, showing the world your commitment to justice |
| 5 | A black heart, signifying that emotions such as pity do not sway your dedication to your oath |
| 6 | An unblinking eye, meaning that you are ever alert to all threats against your cause |{ #symbol}


## Nemesis
_Source: Xanathar's Guide to Everything_

Their adherence to a sacred oath demands that paladins take an active stance in carrying their beliefs into the world. This activity naturally leads to conflict with creatures or entities that oppose those beliefs. Among those opponents, one often stands out as a paladin's most persistent or most formidable foe—a nemesis whose presence or influence is a constant factor in a paladin's life.

Your paladin character might have an enemy that dates from the days before you took up your path. Or you could be a target because when you became a paladin, you immediately attracted the attention of those that would do you in. If you have a nemesis, who or what is it? Whom among your enemies do you consider to be the biggest threat to achieving your goals?

**Nemesis**

`dice: [](paladin.md#^nemesis)`

| dice: d6 | Nemesis |
|----------|---------|
| 1 | A mighty orc war chief who threatens to overrun and destroy everything you hold sacred |
| 2 | A fiend or a celestial, the agent of a power of the Outer Planes, who has been charged with corrupting or redeeming you, as appropriate |
| 3 | A dragon whose servants dog your steps |
| 4 | A high priest who sees you as a misguided fool and wants you to abandon your religion |
| 5 | A rival paladin who trained with you but became an oath-breaker and holds you responsible |
| 6 | A vampire who has sworn revenge against all paladins after being defeated by one |{ #nemesis}


## Temptation
_Source: Xanathar's Guide to Everything_

Although paladins are dedicated to their oaths, they are mortals, and thus they are flawed. Many of them exhibit a type of behavior or hold to an attitude that is not in keeping with the highest ideals of their calling.

What is the temptation that your character succumbs to or finds it difficult to resist?

**Temptation**

`dice: [](paladin.md#^temptation)`

| dice: d6 | Temptation |
|----------|------------|
| 1 | Fury. When your anger is roused, you have trouble thinking straight, and you fear you might do something you'll regret. |
| 2 | Pride. Your deeds are noteworthy, and no one takes note of them more often than you. |
| 3 | Lust. You can't resist an attractive face and a pleasant smile. |
| 4 | Envy. You are mindful of what some famous folk have accomplished, and you feel inadequate when your deeds don't compare to theirs. |
| 5 | Despair. You consider the great strength of the enemies you must defeat, and at times you see no way to achieve final victory. |
| 6 | Greed. Regardless of how much glory and treasure you amass, it's never enough for you. |{ #temptation}


## Class Features

### Divine Sense (Level 1)

The presence of strong evil registers on your senses like a noxious odor, and powerful good rings like heavenly music in your ears. As an action, you can open your awareness to detect such forces. Until the end of your next turn, you know the location of any celestial, fiend, or undead within 60 feet of you that is not behind total cover. You know the type (celestial, fiend, or undead) of any being whose presence you sense, but not its identity (the vampire Count Strahd von Zarovich, for instance). Within the same radius, you also detect the presence of any place or object that has been consecrated or desecrated, as with the [hallow](3-Mechanics/CLI/spells/hallow.md) spell.

You can use this feature a number of times equal to 1 + your Charisma modifier. When you finish a long rest, you regain all expended uses.

### Lay on Hands (Level 1)

Your blessed touch can heal wounds. You have a pool of healing power that replenishes when you take a long rest. With that pool, you can restore a total number of hit points equal to your paladin level × 5.

As an action, you can touch a creature and draw power from the pool to restore a number of hit points to that creature, up to the maximum amount remaining in your pool.

Alternatively, you can expend 5 hit points from your pool of healing to cure the target of one disease or neutralize one poison affecting it. You can cure multiple diseases and neutralize multiple poisons with a single use of Lay on Hands, expending hit points separately for each one.

This feature has no effect on undead and constructs.

### Divine Smite (Level 2)

Starting at 2nd level, when you hit a creature with a melee weapon attack, you can expend one spell slot to deal radiant damage to the target, in addition to the weapon's damage. The extra damage is `2d8` for a 1st-level spell slot, plus `1d8` for each spell level higher than 1st, to a maximum of `5d8`. The damage increases by `1d8` if the target is an undead or a fiend, to a maximum of `6d8`.

### Fighting Style (Level 2)

At 2nd level, you adopt a particular style of fighting as your specialty. Choose one of the following options. You can't take the same Fighting Style option more than once, even if you get to choose again.

- [Defense](3-Mechanics/CLI/optional-features/defense.md)  
- [Dueling](3-Mechanics/CLI/optional-features/dueling.md)  
- [Great Weapon Fighting](3-Mechanics/CLI/optional-features/great-weapon-fighting.md)  
- [Protection](3-Mechanics/CLI/optional-features/protection.md)  

### Spellcasting (Level 2)

By 2nd level, you have learned to draw on divine magic through meditation and prayer to cast spells as a cleric does. See "chapter 10" for the general rules of spellcasting and "chapter 11" for the paladin spell list.

#### Preparing and Casting Spells

The Paladin table shows how many spell slots you have to cast your paladin spells. To cast one of your paladin spells of 1st level or higher, you must expend a slot of the spell's level or higher. You regain all expended spell slots when you finish a long rest.

You prepare the list of paladin spells that are available for you to cast, choosing from the paladin spell list. When you do so, choose a number of paladin spells equal to your Charisma modifier + half your paladin level, rounded down (minimum of one spell). The spells must be of a level for which you have spell slots.

For example, if you are a 5th-level paladin, you have four 1st-level and two 2nd-level spell slots. With a Charisma of 14, your list of prepared spells can include four spells of 1st or 2nd-level, in any combination. If you prepare the 1st-level spell [cure wounds](3-Mechanics/CLI/spells/cure-wounds.md), you can cast it using a 1st-level or a 2nd-level slot. Casting the spell doesn't remove it from your list of prepared spells.

You can change your list of prepared spells when you finish a long rest. Preparing a new list of paladin spells requires time spent in prayer and meditation: at least 1 minute per spell level for each spell on your list.

#### Spellcasting Ability

Charisma is your spellcasting ability for your paladin spells, since their power derives from the strength of your convictions. You use your Charisma whenever a spell refers to your spellcasting ability. In addition, you use your Charisma modifier when setting the saving throw DC for a paladin spell you cast and when making an attack roll with one.

<span class='abilityDc'>**Spell save DC**: 8 + your proficiency bonus + your Charisma modifier</span>

<span class='abilityAttackMod'>**Spell attack modifier**: your proficiency bonus + your Charisma modifier</span>

#### Spellcasting Focus

You can use a [holy symbol](3-Mechanics/CLI/items/holy-symbol.md) as a spellcasting focus for your paladin spells.

### Divine Health (Level 3)

By 3rd level, the divine magic flowing through you makes you immune to disease.

### Sacred Oath (Level 3)

When you reach 3rd level, you swear the oath that binds you as a paladin forever. Up to this time you have been in a preparatory stage, committed to the path but not yet sworn to it. Now you choose from the list of available oaths.

Your choice grants you features at 3rd level and again at 7th, 15th, and 20th level. Those features include oath spells and the Channel Divinity feature.

#### Oath Spells

Each oath has a list of associated spells. You gain access to these spells at the levels specified in the oath description. Once you gain access to an oath spell, you always have it prepared. Oath spells don't count against the number of spells you can prepare each day.

If you gain an oath spell that doesn't appear on the paladin spell list, the spell is nonetheless a paladin spell for you.

### Channel Divinity (Level 3)

Your oath allows you to channel divine energy to fuel magical effects. Each Channel Divinity option provided by your oath explains how to use it.

When you use your Channel Divinity, you choose which option to use. You must then finish a short or long rest to use your Channel Divinity again.

Some Channel Divinity effects require saving throws. When you use such an effect from this class, the DC equals your paladin spell save DC.

### Channel Divinity: Harness Divine Power (Level 3)
_Source: Tasha's Cauldron of Everything p. 52_

*3rd-level paladin [optional feature](3-Mechanics/CLI/rules/variant-rules/optional-class-features-tce.md)*

You can expend a use of your Channel Divinity to fuel your spells. As a bonus action, you touch your holy symbol, utter a prayer, and regain one expended spell slot, the level of which can be no higher than half your proficiency bonus (rounded up). The number of times you can use this feature is based on the level you've reached in this class: 3rd level, once; 7th level, twice; and 15th level, thrice. You regain all expended uses when you finish a long rest.

> [!note] Breaking Your Oath
> 
> A paladin tries to hold to the highest standards of conduct, but even the most virtuous paladin is fallible. Sometimes the right path proves too demanding, sometimes a situation calls for the lesser of two evils, and sometimes the heat of emotion causes a paladin to transgress his or her oath.
> 
> A paladin who has broken a vow typically seeks absolution from a cleric who shares his or her faith or from another paladin of the same order. The paladin might spend an all-night vigil in prayer as a sign of penitence, or undertake a fast or similar act of self-denial. After a rite of confession and forgiveness, the paladin starts fresh.
> 
> If a paladin willfully violates his or her oath and shows no sign of repentance, the consequences can be more serious. At the DM's discretion, an impenitent paladin might be forced to abandon this class and adopt another, or perhaps to take the Oathbreaker paladin option that appears in the Dungeon Master's Guide.{ #breaking-your-oath}


### Ability Score Improvement (Level 4)

When you reach 4th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Martial Versatility (Level 4)
_Source: Tasha's Cauldron of Everything p. 52_

*4th-level paladin [optional feature](3-Mechanics/CLI/rules/variant-rules/optional-class-features-tce.md)*

Whenever you reach a level in this class that grants the Ability Score Improvement feature, you can replace a [fighting style](3-Mechanics/CLI/lists/list-optfeaturetype-fs-p.md) you know with another fighting style available to paladins. This replacement represents a shift of focus in your martial practice.

### Extra Attack (Level 5)

Beginning at 5th level, you can attack twice, instead of once, whenever you take the [Attack](3-Mechanics/CLI/rules/actions.md#Attack) action on your turn.

### Aura of Protection (Level 6)

Starting at 6th level, whenever you or a friendly creature within 10 feet of you must make a saving throw, the creature gains a bonus to the saving throw equal to your Charisma modifier (with a minimum bonus of +1). You must be conscious to grant this bonus.

At 18th level, the range of this aura increases to 30 feet.

### Sacred Oath feature (Level 7)

At 7th level, you gain a feature granted to you by your Sacred Oath.

### Ability Score Improvement (Level 8)

When you reach 8th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Aura of Courage (Level 10)

Starting at 10th level, you and friendly creatures within 10 feet of you can't be [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) while you are conscious.

At 18th level, the range of this aura increases to 30 feet.

### Improved Divine Smite (Level 11)

By 11th level, you are so suffused with righteous might that all your melee weapon strikes carry divine power with them. Whenever you hit a creature with a melee weapon, the creature takes an extra `1d8` radiant damage.

### Ability Score Improvement (Level 12)

When you reach 12th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Cleansing Touch (Level 14)

Beginning at 14th level, you can use your action to end one spell on yourself or on one willing creature that you touch.

You can use this feature a number of times equal to your Charisma modifier (a minimum of once). You regain expended uses when you finish a long rest.

### Sacred Oath feature (Level 15)

At 15th level, you gain a feature granted to you by your Sacred Oath.

### Ability Score Improvement (Level 16)

When you reach 16th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Aura improvements (Level 18)

At 18th level, the range of your Aura of Protection increases to 30 feet.

### Ability Score Improvement (Level 19)

When you reach 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Sacred Oath feature (Level 20)

At 20th level, you gain a feature granted to you by your Sacred Oath.

## Optional Features

> [!example]- Optional Features: Fighting Style, Paladin
> ![Fighting Style, Paladin](3-Mechanics/CLI/lists/list-optfeaturetype-fs-p.md#Fighting%20Style,%20Paladin)
^list-optfeature-fs-p