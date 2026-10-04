# Combat Rules
This page lists the basic *__Combat Rules__* utilized by this system.

## Row System
Unlike other more noteworthy TTRPGs, this system uses a derivative of range bands, better known as the *__Row System__*. The *__Row System__* grants all combat parties a set of two **Rows**; One in the **Front**, one in the **Back**. Each character can normally only reach up to one **Row** away both forward and backward unless otherwise stated.

The *__Row System__* at its core is designed to allow for simpler combat structure while maintaining some minor positional complexity; Groups of characters can directly **Attack** another *or* they can **Surround** or **Ambush** unsuspecting victims to gain an advantage. Regardless of how the main group engages, the defending group always gets to choose which **Row** they start in first.
- When **Attacking** a specific group of characters, the enemy group appears from the front, attacking their **Front Row**.
- When **Surrounding** a specific group of characters, they are placed in the middle of two enemy groups on both sides of their formation.
- When **Ambushing** a specific group of characters, the enemy group appears from behind, attacking their **Back Row**.

> [!TIP]
> A GM chooses when to reveal whether or not their group of characters is **Attacking**, **Surrounding**, or **Ambushing** before combat initiates. Once combat is finished initiating, you must reveal where characters are in relation to the players.

## Initiating Combat
Before *__Initiating Combat__*, each party entering **Combat** must determine their starting **Rows** using one of the above methods. Once all participants have chosen where to start, the attackers mention how they're engaging their enemies, then each combat participant rolls a **d% Check** of **<a style="color:#ffff40">Ego</a>** + **Aptitude** + **d%**. The results of these rolls, called *__Initiative__*, determines the **Round Order**, with the highest values acting before lower values. If there's a tie, those characters perform additional **d% Checks** until there aren't any, repositioning themselves before or after other characters they were rolling off with.

## Turns and Rounds
*__Turns and Rounds__* are ways to keep track of time passing throughout dangerous situations. A *__Round__* is comprised of all characters' *__Turns__* and lasts a total of 6 seconds. A single character's *__Turn__* is comprised of what they can do within their alloted time within a *__Round__*.

At the start of a character's *__Turn__*, that character fully recovers their **Action Points**. Their *__Turn__* ends when they run out of **Action Points**.

> [!WARNING]
> The GM may decide to end your turn early if you take an exceedingly long time. Be reasonable!

Once all characters have ended their *__Turns__*, the current *__Round__* ends and proceeds to the next.

## Basic Abilities
Each character has the following *__Basic Abilities__* at their disposal at any time:

| *__Ability Name__* | *__Properties__* | *__Effects__* |
| :-: | :-: | --- |
| Unarmed Strike | *Active*;<br />**Cost:** 1<i class="fa-solid fa-gem"></i>;<br />**Targets:** 1; | Roll a **Contested d% Check** against each target of **<a style="color:#ff4040">Physique</a>** + **Aptitude** + **d%**.<br />*__Success:__* This **Ability** deals 1d4 Bludgeoning damage to each of its targets' **<a style="color:#c040ff"><i class="fa-solid fa-heart"></i>Health</a>**.<br />*__Failure:__* This **Ability** deals 1 Bludgeoning damage. |
| Defend | *Active*;<br />**Cost:** 1<i class="fa-solid fa-gem"></i>;<br />**Targets:** 1; | This **Ability** grants its user **<i class="fa-solid fa-shield-halved"></i>Global Defense** equal to their Current **Level** + 1 until the start of their next **Turn**. Their current **Turn** ends. |
| Run Away | *Active*;<br />**Cost:** 2<i class="fa-solid fa-gem"></i>;<br />**Targets:** All Enemies; | Roll a **Contested d% Check** against each target of **<a style="color:#4040ff">Instinct</a>** + **<i class="fa-solid fa-person-falling"></i>Evasion** + **d%**. Count each **Success** as +1 and each **Failure** as +0 for the result.<br />If the result is greater than or equal to half the available enemies contested against, this **Ability** causes its user to disengage from combat by running away. |
| Postpone | *Active*;<br />**Cost:** 0<i class="fa-solid fa-gem"></i>;<br />**Targets:** 1; | This **Ability** grants its user a lower **Initiative** of their choice, to a minimum of 1. Once it resolves, the user must wait for their **Turn** again. |
| Pass | *Active*;<br />**Cost:** 2<i class="fa-solid fa-gem"></i>;<br />**Targets:** 1; | This **Ability** grants its target 1 Temporary **<i class="fa-solid fa-gem"></i>Action Point**. The user's current **Turn** ends. |

## Ending Combat
When all enemies of a specific group of characters either dies or fully disengages, those groups *__End Combat__* with one another. All characters, including those that are dead, gain **Experience** equal to the total enemy **Levels** multiplied by a bonus based on the following tables:

| *__Combat Difficulty__* | *__Level Difference__* | *__Experience Multiplier__* |
| :-: | :-: | :-: |
| Trivial | -8 to -7 | 25% |
| Beginner | -6 to -5 | 50% |
| Easy | -4 to -3 | 75% |
| Moderate | -2 to +0 | 100% |
| Hard | +1 to +2 | 150% |
| Very Hard | +3 to +4 | 200% |
| Super Hard | +5 to +6 | 250% |
| Extreme | +7 to +8 | 300% |

To further explain the above table, the **Level Difference** uses the total **Levels** of each character in a group compared to that group's enemies to determine the **Combat Difficulty**. For example, if four characters in one group are **Level** 4 and they're fighting 3 **Level** 5 enemies from another group, that Combat Encounter is considered a *Moderate* combat encounter and grants 100% of its **Experience** to the first group. *(4 + 4 + 4 + 4 = 16, 5 + 5 + 5 = 15, 15 - 16 = -1.)* For the second group, however, this is considered a *Hard* combat encounter instead, granting that group 150% of its total **Experience**. *(5 + 5 + 5 = 15, 4 + 4 + 4 + 4 = 16, 16 - 15 = 1.)*

| *__Character Rank__* | *__Base Stat Multiplier__* | *__Experience Multiplier__* |
| :-: | :-: | :-: |
| Minion | 100% | 100% |
| Elite| 150% | 200% |
| Boss | 200% | 400% |
| Legend | 300% | 800% |

To further explain this other table, the GM can create characters with a **Character Rank**. For example, if a character has the **Character Rank** of *Boss* at **Level** 5, its **Base Stats** are multiplied by 200% and the **Experience Multiplier** is then itself multiplied by 400% for the party that defeats them. When that *Boss* would then be defeated, its **Level** is also multiplied by the **Base Stat Multiplier** value for the **Combat Difficulty**. *(5 x 200% = 10.)* Using this new value, against four **Level** 3 player characters, it would be a *Moderate* combat encounter, granting 400% of its total **Experience**. *(3 + 3 + 3 + 3 = 12, 12 - 10 = -2. 100% x 400% = 400%.)*

**Experience** gained this way is gained all at once; As mentioned in *Character Creation*, **Experience** gained is reduced by your current **Level**, to a minimum of 1. Additionally, **Experience** is given to each member of the group equally without splitting it.

Finally, any **Gear** dropped on the battlefield by defeated targets may be picked up by any survivors.
