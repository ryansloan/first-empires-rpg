# Game Master Tools

## Something Happens!
In some RPGs, a failed roll means nothing happens: the status quo is maintained. In First Empires, this is not the case: **something always changes after dice are rolled**. This means:

* **Only roll when it counts**. Don't call for a roll if there's no meaningful consequence of failure. They just do it – _especially_ if it's core to the character's fantasy. 
* **Share the lore**. Knowledge checks are hard to devise consequences for, if a player asks a question someone in the party might reasonably know, _just tell them_. If it's important to gatekeep the information, then give them an action-oriented way to find out: a library to search, a person to talk to, or a lost inscription to quest for.
* **Mixed success is still success**. Don't use a mixed success as an opportunity to make a character look foolish, or completely undermine their intended goal. Instead, 
* **Embrace failing-forward**. Sometimes, a character can achieve their immediate goal with failed roll, but in doing so find themselves in a desperate position.
* **Not all consequences are immediately visible**. A flubbed roll to sneak into the goblin war camp might seem fine at first. Little do the players know, the goblins are arming themselves. 
* **Telegraph threats**. Enemies don't get turns, so players shouldn't be surprised to learn that the monster is attacking them. (Unless it's a narrative surprise attack!)

## Clocks
In most cases, obstacles and enemies can be overcome with one successful action. Most doors are no match for a seasoned lockpick, and zombies can only withstand so much bonking. But sometimes, you’ll encounter a nut that’s harder to crack: a complex locking mechanism, elaborate magical wards, or an enemy with enhanced strength. In those cases, the GM creates a clock with a number of segments corresponding to the difficulty of the task. 

In general, **limited effect fills one segment**, **standard effect fills two segments**, and **great effect fills three or four**. You can think of a run-of-the-mill obstacle (like a goon or ordinary lock) as a clock with only two segments. 

### Obstacle Clocks
Obstacle clocks represent complex problems to be solved with many rolls: sneaking into the evil priest’s unholy sanctum, evading the evil king’s guards in a crowd. 

### Health Clocks
Most enemies are _goons_ that can be overcome with one successful action. But some enemies are more powerful, and have their health represented as a clock. If you need to account for an NPC’s armor, include it in their health clock instead of managing armor ratings. 

### Danger Clocks
Obstacle Clocks and Health Clocks track the party’s progress toward their goals, but sometimes the GM may need to track progress for non-player characters in the form of danger clocks. Danger clocks represent danger getting closer: the guards are becoming aware of sneaking intruders, the arcanometer is overloaded and about to explode. In these cases, the GM creates a clock and ticks segments when the party fails.

A failed roll in a risky position may result in two ticks to a danger clock, whereas a failed roll in a desperate position may result in four. 

#### Harm vs. Serious Harm
When a character suffers "serious harm" (because they are in a desperate position), the damage is rolled with advantage (roll twice, keep the highest). For example, if the monster attacking normally deals 1d4 damage, roll 2d4 and keep the highest.

## Tags
Sometimes, scenarios, objects, or creatures will have **tags** associated with them, representing unique properties that player characters can use to their advantage. For example, creating an advantage by throwing fire at an enemy might give them the “ablaze” tag. The next party member to act can invoke the “ablaze” status to gain +1d. 

Most tags can only be invoked once, but some abilities may create a **sticky tag**. Sticky tags persist until circumstances would cause them to be removed. In general, a sticky tag ends with the current Scene.

## Campaigns, Quests, Sessions and Scenes
The structures and rhythms of gameplay are hierarchical:
* Campaign – series of Quests with shared characters.
* Quest – adventure undertaken to solve a large problem or achieve a goal. Typically spans multiple Sessions of play. After a quest, characters take a break to recuperate. 
* Session – out-of-game time when the players gather to play, consists of multiple Scenes.
* Scene – a period of time when the party is focused on a single goal. Every scene should focus on a dramatic question: will the party defeat The Blob? Will they be able to sneak into the Evil King’s fortress?
* Action – an individual character’s attempt to change something about the current Scene. 

## Bestiary
### Creature properties
* Creature Category – Every creature has one of these properties indicating its type.
    * Construct - A synthetic creature. Golems, automatons, and living clockwork.
    * Person - A humanoid creature, including elves, gnomes, goblins, etc.
    * Plant - Plants fall into this category even if they are intelligent.
    * Undead - The reanimated dead. Zombies, skeletons, and ghosts are in this category.
    * Elemental [X] - a living creature composed of element X
    * Monster - A creature that does not fall into any other creature category
* Goon – This is a simple creature, dispatched with one harm. Most of the enemies a party faces will be Goons serving a more powerful foe.
* Brute [X] – the creature is ferocious, and deals X more harm than usual. 
* Flying - the creature can fly skillfully
* Swimming - the creature can swim skillfully
* Incorporeal - the creature can move through objects and other creatures.
* Immune [X] – the creature is immune to damage from sources described in X
* Mindless – the creature is incapable of reason or communication, acting only on its most basic natural instinct
* Vulnerable [X] - attacks described in X are with increased effect

### Special Monster Features
Monsters may have special features more complex than a property. Some features are specific to a given creature, but others are common across monsters:

* Health Clock [X] – This creature has a Health Clock with X segments. 
* Sweeping Attack [X/Y] - A creature with a sweeping attack can inflict harm on many creatures at once. Start a Danger clock with X segments. When the clock is filled, the creature’s Sweeping Attack is triggered, and all creatures within its zone suffer Y harm.
* Arcane Reflection [X] - A magical attack on this creature is reflected back on its caster, who takes equal damage. After this is triggered, it cannot be used again. Start a Danger Clock with X segments. Mark a segment when the creature is hit with magic. When the clock is full, the creature can use this ability again.
* Consume - when a character fails an action targeting this creature within the same zone, they suffer harm and are pulled inside the monster, creating a desperate situation.
* Grapple [X] - when a character fails an action within this creature’s zone, the creature grabs them. The character is unable to move of their own accord. They can attempt to escape with an action, or other characters can attempt to pull them free. The creature can have X characters grappled at once. 
* Surprise Attack - if the characters are unaware of this creature, it can initiate combat with a surprise attack, in which all characters fail their readiness roll. 
* Death Throes [X] - when this creature is killed, it deals X damage to other creatures within its zone.

Example Monsters
* Red Dragon: Monster, Health Clock [12], Brute [2], Immune [Fire], Fire Breath Sweeping Attack [6, 5], Flying
* Guard Drake: Monster, Goon, Immune [Fire]
* Archwizard: Person, Health Clock [4], Arcane Reflection [4], Fireball Sweeping Attack [4, 2]
* Slime: Monster, Mindless, Goon, Vulnerable [Slashing]
* Big Blob: Monster, Mindless, Vulnerable [Slashing], Health Clock [4], Consume
* Cyclops: Person, Health Clock [6], Brute [2], Flailing Club Sweeping Attack [4, 3]
* Giant Spider: Beast, Health Clock [4], Surprise Attack, Grapple
    * Web Burst [4]: When this 4-segment danger clock is completed, the Giant Spider shoots sticky webbing all over its current zone, which gains the “enwebbed” tag. While enwebbed, the zone is extra flammable, and characters move through it with reduced effect.
* Animated Armor: Construct, Mindless, Goon, Brute [1]
* Animated Statue: Construct, Mindless, Health Clock [6], Brute [2]
* Living Earth: Monster, Health Clock [6], Brute [2], Seismic Wave Sweeping Attack [4, 2]
* Animated Pyre: Monster, Immune [Fire], Health Clock [4], Consume, Flare Sweeping Attack [4, 1]
* Living Tsunami: Monster, Immune [Fire], Health Clock [4], Consume, Water Surge Sweeping Attack [4, 1]
* Medusa: Monster, Health Clock [6].
    * Petrifying Gaze [6]: When this six-segment danger clock is completed, all creatures who can see the Medusa gain the “petrifying” trouble. If a creature ends its next turn within the Medusa’s zone, it becomes “petrified”. “Petrified” is a curse that prevents the creature from moving or acting until removed.
* Giant Squid: Beast, Health Clock [8], Whirl of Tentacles Sweeping Attack [3, 1], Grappler [8], Swimming
* War Chief: Person, Health Clock [4], Brute [2]
* Werewolf: Monster, Immune [physical attacks with materials other than silver], Brute [1]
    * Lycanthropic Curse: a creature who suffers harm from the werewolf must succeed on a Charm roll or be cursed with lycanthropy. 
* Troll: Monster, Vulnerable [Fire], Health Clock [8], Brute [2]
* Mimic: Monster, Health Clock [4], Surprise Attack, Grapple [4]
    * Hide in plain sight: the mimic perfectly disguises itself as an inanimate object. It is impossible to know the mimic’s true form through mundane means. Unless characters know of its true form, the Mimic can use Surprise Attack
* Armored Skeleton: Undead, Health Clock [4], Brute [1]
* Ghost: Undead, Goon, Immune [Physical attacks], Surprise Attack, Incorporeal
* Banshee: Undead, Immune [Physical attacks], Surprise Attack, Incorporeal, Shrieking Sweeping Attack [4, 2]
* Zombie: Undead, Goon
* Dire Wolf: Beast, Goon, Brute [1]
