---
{"dg-publish":true,"permalink":"/3-mechanics/cli/classes/sorcerer/","tags":["ttrpg-cli/class/sorcerer","ttrpg-cli/compendium/src/5e/phb"],"noteIcon":""}
---

# Sorcerer
*Source: Player's Handbook p. 99. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

> [!tldr] Class and Feature Progression
> 
> <table class="class-progression">
> <thead>
> <tr><th colspan='6'></th><th colspan='9'>Spell Slots per Spell Level</th></tr>
> <tr class="class-progression"><th class="level">Level</th><th class="pb">PB</th><th class="feature">Features</th><th class="value">Sorcery Points</th><th class="value">Cantrips Known</th><th class="value">Spells Known</th><th class="spellSlot">1st</th><th class="spellSlot">2nd</th><th class="spellSlot">3rd</th><th class="spellSlot">4th</th><th class="spellSlot">5th</th><th class="spellSlot">6th</th><th class="spellSlot">7th</th><th class="spellSlot">8th</th><th class="spellSlot">9th</th></tr>
> </thead><tbody>
> <tr class="class-progression"><td class="level">1st</td><td class="pb">+2</td><td class="feature"><a href='#Spellcasting (Level 1)' class='internal-link'>Spellcasting</a>, <a href='#Sorcerous Origin (Level 1)' class='internal-link'>Sorcerous Origin</a></td><td class="value">⏤</td><td class="value">4</td><td class="value">2</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">2nd</td><td class="pb">+2</td><td class="feature"><a href='#Font of Magic (Level 2)' class='internal-link'>Font of Magic</a></td><td class="value">2</td><td class="value">4</td><td class="value">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">3rd</td><td class="pb">+2</td><td class="feature"><a href='#Metamagic (Level 3)' class='internal-link'>Metamagic</a>, <a href='#Metamagic Options (Level 3)' class='internal-link'>Metamagic Options</a></td><td class="value">3</td><td class="value">4</td><td class="value">4</td><td class="spellSlot">4</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">4th</td><td class="pb">+2</td><td class="feature"><a href='#Ability Score Improvement (Level 4)' class='internal-link'>Ability Score Improvement</a>, <a href='#Sorcerous Versatility (Level 4)' class='internal-link'>Sorcerous Versatility</a></td><td class="value">4</td><td class="value">5</td><td class="value">5</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">5th</td><td class="pb">+3</td><td class="feature"><a href='#Magical Guidance (Level 5)' class='internal-link'>Magical Guidance</a></td><td class="value">5</td><td class="value">5</td><td class="value">6</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">6th</td><td class="pb">+3</td><td class="feature"><a href='#Sorcerous Origin feature (Level 6)' class='internal-link'>Sorcerous Origin feature</a></td><td class="value">6</td><td class="value">5</td><td class="value">7</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">7th</td><td class="pb">+3</td><td class="feature"></td><td class="value">7</td><td class="value">5</td><td class="value">8</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">8th</td><td class="pb">+3</td><td class="feature"><a href='#Ability Score Improvement (Level 8)' class='internal-link'>Ability Score Improvement</a></td><td class="value">8</td><td class="value">5</td><td class="value">9</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">9th</td><td class="pb">+4</td><td class="feature"></td><td class="value">9</td><td class="value">5</td><td class="value">10</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">10th</td><td class="pb">+4</td><td class="feature"><a href='#Metamagic (Level 10)' class='internal-link'>Metamagic</a></td><td class="value">10</td><td class="value">6</td><td class="value">11</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">11th</td><td class="pb">+4</td><td class="feature"></td><td class="value">11</td><td class="value">6</td><td class="value">12</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">12th</td><td class="pb">+4</td><td class="feature"><a href='#Ability Score Improvement (Level 12)' class='internal-link'>Ability Score Improvement</a></td><td class="value">12</td><td class="value">6</td><td class="value">12</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">13th</td><td class="pb">+5</td><td class="feature"></td><td class="value">13</td><td class="value">6</td><td class="value">13</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">14th</td><td class="pb">+5</td><td class="feature"><a href='#Sorcerous Origin feature (Level 14)' class='internal-link'>Sorcerous Origin feature</a></td><td class="value">14</td><td class="value">6</td><td class="value">13</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">15th</td><td class="pb">+5</td><td class="feature"></td><td class="value">15</td><td class="value">6</td><td class="value">14</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">16th</td><td class="pb">+5</td><td class="feature"><a href='#Ability Score Improvement (Level 16)' class='internal-link'>Ability Score Improvement</a></td><td class="value">16</td><td class="value">6</td><td class="value">14</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">⏤</td></tr>
> <tr class="class-progression"><td class="level">17th</td><td class="pb">+6</td><td class="feature"><a href='#Metamagic (Level 17)' class='internal-link'>Metamagic</a></td><td class="value">17</td><td class="value">6</td><td class="value">15</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class="level">18th</td><td class="pb">+6</td><td class="feature"><a href='#Sorcerous Origin feature (Level 18)' class='internal-link'>Sorcerous Origin feature</a></td><td class="value">18</td><td class="value">6</td><td class="value">15</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class="level">19th</td><td class="pb">+6</td><td class="feature"><a href='#Ability Score Improvement (Level 19)' class='internal-link'>Ability Score Improvement</a></td><td class="value">19</td><td class="value">6</td><td class="value">15</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> <tr class="class-progression"><td class="level">20th</td><td class="pb">+6</td><td class="feature"><a href='#Sorcerous Restoration (Level 20)' class='internal-link'>Sorcerous Restoration</a></td><td class="value">20</td><td class="value">6</td><td class="value">15</td><td class="spellSlot">4</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">3</td><td class="spellSlot">2</td><td class="spellSlot">2</td><td class="spellSlot">1</td><td class="spellSlot">1</td></tr>
> </tbody></table>
{ #class-progression}


## Hit Points

- **Hit Dice**: 1d6 per Sorcerer level
- **Hit Points at First Level:** 6 + CON
- **Hit Points at Higher Levels:** add 4 OR 1d6 + CON  (minimum of 1)

## Starting Sorcerer

- **Saving Throws**: Charisma, Constitution
- **Armor**: none
- **Weapons**: [daggers](3-Mechanics/CLI/items/dagger.md), [darts](3-Mechanics/CLI/items/dart.md), [slings](3-Mechanics/CLI/items/sling.md), [quarterstaffs](3-Mechanics/CLI/items/quarterstaff.md), [light crossbows](3-Mechanics/CLI/items/light-crossbow.md)
- **Tools**: none
- **Skills**: choose 2 from [Arcana](3-Mechanics/CLI/rules/skills.md#Arcana), [Deception](3-Mechanics/CLI/rules/skills.md#Deception), [Insight](3-Mechanics/CLI/rules/skills.md#Insight), [Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation), [Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion), and [Religion](3-Mechanics/CLI/rules/skills.md#Religion)

You start with the following items, plus anything provided by your background.

- (a) a [light crossbow](3-Mechanics/CLI/items/light-crossbow.md) and [20 bolts](3-Mechanics/CLI/items/crossbow-bolts-20.md) or (b) any simple weapon
- (a) a [component pouch](3-Mechanics/CLI/items/component-pouch.md) or (b) an [arcane focus](3-Mechanics/CLI/items/arcane-focus.md)
- (a) a [dungeoneer's pack](3-Mechanics/CLI/items/dungeoneers-pack.md) or (b) an [explorer's pack](3-Mechanics/CLI/items/explorers-pack.md)
- Two [daggers](3-Mechanics/CLI/items/dagger.md)

Alternatively, you may start with 3d4 × 10 gp to buy your own equipment.

## Multiclassing Sorcerer

**Ability Score Minimum:** Charisma 13

## Sorcerer

Golden eyes flashing, a human stretches out her hand and unleashes the dragonfire that burns in her veins. As an inferno rages around her foes, leathery wings spread from her back and she takes to the air.

Long hair whipped by a conjured wind, a half-elf spreads his arms wide and throws his head back. Lifting him momentarily off the ground, a wave of magic surges up in him, through him, and out from him in a mighty blast of lightning.

Crouching behind a stalagmite, a halfling points a finger at a charging troglodyte. A blast of fire springs from her finger to strike the creature. She ducks back behind the rock formation with a grin, unaware that her wild magic has turned her skin bright blue.

Sorcerers carry a magical birthright conferred upon them by an exotic bloodline, some otherworldly influence, or exposure to unknown cosmic forces. One can't study sorcery as one learns a language, any more than one can learn to live a legendary life. No one chooses sorcery; the power chooses the sorcerer.

### Raw Magic

Magic is a part of every sorcerer, suffusing body, mind, and spirit with a latent power that waits to be tapped. Some sorcerers wield magic that springs from an ancient bloodline infused with the magic of dragons. Others carry a raw, uncontrolled magic within them, a chaotic storm that manifests in unexpected ways.

The appearance of sorcerous powers is wildly unpredictable. Some draconic bloodlines produce exactly one sorcerer in every generation, but in other lines of descent every individual is a sorcerer. Most of the time, the talents of sorcery appear as apparent flukes. Some sorcerers can't name the origin of their power, while others trace it to strange events in their own lives. The touch of a demon, the blessing of a dryad at a baby's birth, or a taste of the water from a mysterious spring might spark the gift of sorcery. So too might the gift of a deity of magic, exposure to the elemental forces of the Inner Planes or the maddening chaos of Limbo, or a glimpse into the inner workings of reality.

Sorcerers have no use for the spellbooks and ancient tomes of magic lore that wizards rely on, nor do they rely on a patron to grant their spells as warlocks do. By learning to harness and channel their own inborn magic, they can discover new and staggering ways to unleash that power.

### Unexplained Powers

Sorcerers are rare in the world, and it's unusual to find a sorcerer who is not involved in the adventuring life in some way. People with magical power seething in their veins soon discover that the power doesn't like to stay quiet. A sorcerer's magic wants to be wielded, and it has a tendency to spill out in unpredictable ways if it isn't called on.

Sorcerers often have obscure or quixotic motivations driving them to adventure. Some seek a greater understanding of the magical force that infuses them, or the answer to the mystery of its origin. Others hope to find a way to get rid of it, or to unleash its full potential. Whatever their goals, sorcerers are every bit as useful to an adventuring party as wizards, making up for a comparative lack of breadth in their magical knowledge with enormous flexibility in using the spells they know.

### Creating a Sorcerer

The most important question to consider when creating your sorcerer is the origin of your power. As a starting character, you'll choose an origin that ties to a draconic bloodline or the influence of wild magic, but the exact source of your power is up to you to decide. Is it a family curse, passed down to you from distant ancestors? Or did some extraordinary event leave you blessed with inherent magic but perhaps scarred as well?

How do you feel about the magical power coursing through you? Do you embrace it, try to master it, or revel in its unpredictable nature? Is it a blessing or a curse? Did you seek it out, or did it find you? Did you have the option to refuse it, and do you wish you had? What do you intend to do with it? Perhaps you feel like you've been given this power for some lofty purpose. Or you might decide that the power gives you the right to do what you want, to take what you want from those who lack such power. Perhaps your power links you to a powerful individual in the world—the fey creature that blessed you at birth, the dragon who put a drop of its blood into your veins, the lich who created you as an experiment, or the deity who chose you to carry this power.

#### Quick Build

You can make a sorcerer quickly by following these suggestions. First, Charisma should be your highest ability score, followed by Constitution. Second, choose the hermit background. Third, choose the [light](3-Mechanics/CLI/spells/light.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md), and [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md) cantrips, along with the 1st-level spells [shield](3-Mechanics/CLI/spells/shield.md) and [magic missile](3-Mechanics/CLI/spells/magic-missile.md).

> [!quote] A quote from Hennet, scion of Tiamat  
> 
> Practice and study are for amateurs. True power is a birthright.

When it comes to drawing forth their abilities in times of need, sorcerers have it easy compared to other characters. Their power not only rests within them, but it likely takes some effort to keep it at bay. Every sorcerer is born to the role, or stumbles into it through cosmic chance. Unlike other characters, who must actively learn, embrace, and pursue their talents, sorcerers have their power thrust upon them.

Because the idea of an innately magical being traveling among them does not sit well with many folk, sorcerers tend to breed mistrust and suspicion in others they come across. Nonetheless, many sorcerers succeed in overcoming that prejudice through deeds that benefit their less magically gifted contemporaries.

Sorcerers are often defined by the events surrounding the manifestation of their power. For those who receive it as an expected birthright, its appearance is a cause for celebration. Other sorcerers are treated as outcasts, banished from their homes after the sudden, terrifying arrival of their abilities.

Playing a sorcerer character can be as rewarding as it is challenging. The sections below offer suggestions on how to flesh out and personalize your persona.

## Arcane Origins
_Source: Xanathar's Guide to Everything_

Some sorcerers understand where their power came from, based on how their abilities manifested. Others can only speculate, since their powers came to them in a way that suggests no particular cause.

Does your character know the source of your magical power? Does it tie back to some distant relative, a cosmic event, or blind chance? If your sorcerer doesn't know where their power arose from, your DM can use this table (or select an origin) and reveal it to you when the information plays a role in the campaign.

**Arcane Origins**

`dice: [](sorcerer.md#^arcane-origins)`

| dice: d6 | Origin |
|----------|--------|
| 1 | Your power arises from your family's bloodline. You are related to some powerful creature, or you inherited a blessing or a curse. |
| 2 | You are the reincarnation of a being from another plane of existence. |
| 3 | A powerful entity entered the world. Its magic changed you. |
| 4 | Your birth was prophesied in an ancient text, and you are foretold to use your power for terrible ends. |
| 5 | You are the product of generations of careful, selective breeding. |
| 6 | You were made in a vat by an alchemist. |{ #arcane-origins}


## Reaction
_Source: Xanathar's Guide to Everything_

When a new sorcerer enters the world, either at birth or later when one's power becomes evident, the consequences of that event depend greatly on how its witnesses react to what they have seen.

When your sorcerer's powers appeared, how did the world around you respond? Were other people supportive, fearful, or somewhere in between?

**Reactions**

`dice: [](sorcerer.md#^reactions)`

| dice: d6 | Reaction |
|----------|----------|
| 1 | Your powers are seen as a great blessing by those around you, and you are expected to use them in service to your community. |
| 2 | Your powers caused destruction and even a death when they became evident, and you were treated as a criminal. |
| 3 | Your neighbors hate and fear your power, causing them to shun you. |
| 4 | You came to the attention of a sinister cult that plans on exploiting your abilities. |
| 5 | People around you believe that your powers are a curse levied on your family for a past transgression. |
| 6 | Your powers are believed to be tied to an ancient line of mad kings that supposedly ended in a bloody revolt over a century ago. |{ #reactions}


## Supernatural Mark
_Source: Xanathar's Guide to Everything_

A sorcerer at rest is almost indistinguishable from a normal person; it's only when their magic flies forth that sorcerers reveal their true nature. Even so, many sorcerers have a subtle but telling physical trait that sets them apart from other folk.

If your sorcerer has a supernatural mark, it might be one that's easily concealed, or it could be a source of pride that you keep on constant display.

**Supernatural Marks**

`dice: [](sorcerer.md#^supernatural-marks)`

| dice: d6 | Mark |
|----------|------|
| 1 | Your eyes are an unusual color, such as red. |
| 2 | You have an extra toe on one foot. |
| 3 | One of your ears is noticeably larger than the other. |
| 4 | Your hair grows at a prodigious rate. |
| 5 | You wrinkle your nose repeatedly while you are chewing. |
| 6 | A red splotch appears on your neck once a day, then vanishes after an hour. |{ #supernatural-marks}


## Signs of Sorcery
_Source: Xanathar's Guide to Everything_

As the world well knows, some sorcerers are better than others at controlling their spellcasting. Sometimes a wild display of magic gone awry emanates from a sorcerer who casts a spell. But even when one's magic goes off as planned, the act of casting is often accompanied by a telltale sign that makes it clear where that magical energy came from.

When your sorcerer character casts a spell, does the effort reveal itself in a sign of sorcery? Is this sign tied to your origin or some other aspect of who you are, or is it a seemingly random phenomenon?

**Signs of Sorcery**

`dice: [](sorcerer.md#^signs-of-sorcery)`

| dice: d6 | Sign |
|----------|------|
| 1 | You deliver the verbal components of your spells in the booming voice of a titan. |
| 2 | For a moment after you cast a spell, the area around you grows dark and gloomy. |
| 3 | You sweat profusely while casting a spell and for a few seconds thereafter. |
| 4 | Your hair and garments are briefly buffeted about, as if by a breeze, whenever you call forth a spell. |
| 5 | If you are standing when you cast a spell, you rise six inches into the air and gently float back down. |
| 6 | Illusory blue flames wreathe your head as you begin your casting, then abruptly disappear. |{ #signs-of-sorcery}


## Class Features

### Spellcasting (Level 1)

An event in your past, or in the life of a parent or ancestor, left an indelible mark on you, infusing you with arcane magic. This font of magic, whatever its origin, fuels your spells. See "chapter 10" for the general rules of spellcasting and "chapter 11" for the sorcerer spell list.

#### Cantrips

At 1st level, you know four cantrips of your choice from the sorcerer spell list. You learn an additional sorcerer cantrip of your choice at 4th level and another at 10th level.

#### Spell Slots

The Sorcerer table shows how many spell slots you have to cast your sorcerer spells of 1st level and higher. To cast one of these sorcerer spells, you must expend a slot of the spell's level or higher. You regain all expended spell slots when you finish a long rest.

For example, if you know the 1st-level spell [burning hands](3-Mechanics/CLI/spells/burning-hands.md) and have a 1st-level and a 2nd-level spell slot available, you can cast [burning hands](3-Mechanics/CLI/spells/burning-hands.md) using either slot.

#### Spells Known of 1st Level and Higher

You know two 1st-level spells of your choice from the sorcerer spell list.

You learn an additional sorcerer spell of your choice at each level except 12th, 14th, 16th, 18th, 19th, and 20th. Each of these spells must be of a level for which you have spell slots. For instance, when you reach 3rd level in this class, you can learn one new spell of 1st or 2nd level.

Additionally, when you gain a level in this class, you can choose one of the sorcerer spells you know and replace it with another spell from the sorcerer spell list, which also must be of a level for which you have spell slots.

#### Spellcasting Ability

Charisma is your spellcasting ability for your sorcerer spells, since the power of your magic relies on your ability to project your will into the world. You use your Charisma whenever a spell refers to your spellcasting ability. In addition, you use your Charisma modifier when setting the saving throw DC for a sorcerer spell you cast and when making an attack roll with one.

<span class='abilityDc'>**Spell save DC**: 8 + your proficiency bonus + your Charisma modifier</span>

<span class='abilityAttackMod'>**Spell attack modifier**: your proficiency bonus + your Charisma modifier</span>

#### Spellcasting Focus

You can use an [arcane focus](3-Mechanics/CLI/items/arcane-focus.md) as a spellcasting focus for your sorcerer spells.

### Sorcerous Origin (Level 1)

Choose a sorcerous origin, which describes the source of your innate magical power, from the list of available origins.

Your choice grants you features when you choose it at 1st level and again at 6th, 14th, and 18th level.

### Font of Magic (Level 2)

At 2nd level, you tap into a deep wellspring of magic within yourself. This wellspring is represented by sorcery points, which allow you to create a variety of magical effects.

### Sorcery Points (Level 2)

You have 2 sorcery points, and you gain one additional point every time you level up, to a maximum of 20 at level 20. You can never have more sorcery points than shown on the table for your level. You regain all spent sorcery points when you finish a long rest.

### Flexible Casting (Level 2)

You can use your sorcery points to gain additional spell slots, or sacrifice spell slots to gain additional sorcery points. You learn other ways to use your sorcery points as you reach higher levels.

#### Creating Spell Slots

You can transform unexpended sorcery points into one spell slot as a bonus action on your turn. The created spell slots vanish at the end of a long rest. The Creating Spell Slots table shows the cost of creating a spell slot of a given level. You can create spell slots no higher in level than 5th.

**Creating Spell Slots**

| Spell Slot Level | Sorcery Point Cost |
|------------------|--------------------|
| 1st | 2 |
| 2nd | 3 |
| 3rd | 5 |
| 4th | 6 |
| 5th | 7 |{ #creating-spell-slots}


#### Converting a Spell Slot to Sorcery Points

As a bonus action on your turn, you can expend one spell slot and gain a number of sorcery points equal to the slot's level.

### Metamagic (Level 3)

At 3rd level, you gain the ability to twist your spells to suit your needs. You gain two of the following Metamagic options of your choice. You gain another one at 10th and 17th level.

You can use only one Metamagic option on a spell when you cast it, unless otherwise noted.

- [Careful Spell](3-Mechanics/CLI/optional-features/careful-spell.md)  
- [Distant Spell](3-Mechanics/CLI/optional-features/distant-spell.md)  
- [Empowered Spell](3-Mechanics/CLI/optional-features/empowered-spell.md)  
- [Extended Spell](3-Mechanics/CLI/optional-features/extended-spell.md)  
- [Heightened Spell](3-Mechanics/CLI/optional-features/heightened-spell.md)  
- [Quickened Spell](3-Mechanics/CLI/optional-features/quickened-spell.md)  
- [Subtle Spell](3-Mechanics/CLI/optional-features/subtle-spell.md)  
- [Twinned Spell](3-Mechanics/CLI/optional-features/twinned-spell.md)  

### Metamagic Options (Level 3)
_Source: Tasha's Cauldron of Everything p. 65_

*3rd-level sorcerer [optional feature](3-Mechanics/CLI/rules/variant-rules/optional-class-features-tce.md)*

When you choose Metamagic options, you have access to the following additional options.

### Ability Score Improvement (Level 4)

When you reach 4th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Sorcerous Versatility (Level 4)
_Source: Tasha's Cauldron of Everything p. 65_

*4th-level sorcerer [optional feature](3-Mechanics/CLI/rules/variant-rules/optional-class-features-tce.md)*

Whenever you reach a level in this class that grants the Ability Score Improvement feature, you can do one of the following, representing the magic within you flowing in new ways:

- Replace one of the options you chose for the Metamagic feature with a different [Metamagic option](3-Mechanics/CLI/lists/list-optfeaturetype-mm.md) available to you.  
- Replace one cantrip you learned from this class's Spellcasting feature with another cantrip from the sorcerer spell list.  

### Magical Guidance (Level 5)
_Source: Tasha's Cauldron of Everything p. 65_

*5th-level sorcerer [optional feature](3-Mechanics/CLI/rules/variant-rules/optional-class-features-tce.md)*

You can tap into your inner wellspring of magic to try to conjure success from failure. When you make an ability check that fails, you can spend 1 sorcery point to reroll the `d20`, and you must use the new roll, potentially turning the failure into a success.

### Sorcerous Origin feature (Level 6)

At 6th level, you gain a feature granted by your Sorcerous Origin.

### Ability Score Improvement (Level 8)

When you reach 8th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Metamagic (Level 10)

At 10th level, you learn an additional metamagic option.

### Ability Score Improvement (Level 12)

When you reach 12th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Sorcerous Origin feature (Level 14)

At 14th level, you gain a feature granted by your Sorcerous Origin.

### Ability Score Improvement (Level 16)

When you reach 16th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Metamagic (Level 17)

At 17th level, you learn an additional metamagic option.

### Sorcerous Origin feature (Level 18)

At 18th level, you gain a feature granted by your Sorcerous Origin.

### Ability Score Improvement (Level 19)

When you reach 19th level, you can increase one ability score of your choice by 2, or you can increase two ability scores of your choice by 1. As normal, you can't increase an ability score above 20 using this feature.

If your DM allows the use of feats, you may instead take a feat.

### Sorcerous Restoration (Level 20)

At 20th level, you regain 4 expended sorcery points whenever you finish a short rest.

## Optional Features

> [!example]- Optional Features: Metamagic
> ![Metamagic](3-Mechanics/CLI/lists/list-optfeaturetype-mm.md#Metamagic)
^list-optfeature-mm