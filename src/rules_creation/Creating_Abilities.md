# Creating Abilities
This page lists a large set of information related to *__Creating Abilities__*. When *__Creating Abilities__*, you'll want to conceptualize how the **Ability** will actively function. Once you have the **Ability** you want in mind, this page may help you to figure out how to piece it together.

> [!Warning]
> **Creating Abilities** is a time-consuming process; You'll be building **Abilities** *piece by piece* to get the desired effect. I recommend starting small and simple, building things up slowly over time as you **Level Up**. Once you get the hang of it, feel free to make your **Abilities** more complex and interesting.

## Ability Properties
As mentioned under the **Core Rules** page, **Abilities** have various *__Ability Properties__* that define basic information about how to utilize them. *__Ability Properties__* explain potential restrictions and interactions the **Ability** they're associated with has. They are listed and explained below:

### Type
The *__Type__* of an **Ability** is either *Active* or *Innate*; *Active* **Abilities** require you to meet their restrictions and manually activate them before they can take effect, while *Innate* **Abilities** automatically activate themselves based on other *__Ability Property__* restrictions.

### Prerequisites
The **Ability** can't be learned unless the character learning it meets its *__Prerequisites__*. *__Prerequisites__* can be one or more of the following:
- <u>**Level:**</u> The **Ability** can only be learned at this **Level** or higher.
- <u>**Aptitude:**</u> The **Ability** can only be learned if you have a number of listed **Aptitudes** at their listed value or higher.
- <u>**Natural Base Stats:**</u> The **Ability** can only be learned if the listed **Base Stats** naturally, before *Gear*, *Boosts*, and *Penalties*, are at the listed values or higher.

### Alternative Costs
The *__Alternative Costs__* of an **Ability** list what it consumes before it can be utilized. You can't spend what you don't have. *__Alternative Costs__* can be one or more of the following:
- <u>**<i class="fa-solid fa-gem"></i>Action Points:**</u> The **Ability** requires you to spend this many **<i class="fa-solid fa-gem"></i>Action Points** before it can be utilized.
- <u>**Resources:**</u> **<a style="color:#ff4040"><i class="fa-solid fa-heart"></i>Health</a>**, **<a style="color:#40ff40"><i class="fa-solid fa-person-running"></i>Stamina</a>**, and/or **<a style="color:#4040ff"><i class="fa-solid fa-bolt"></i>Energy</a>** must be spent before the **Ability** can be utilized. You don't have the capability to spend those **Resources** if you have less than the required amount above the minimum of 0 in that **Resource**.
- <u>**Gear:**</u> The **Ability** consumes specific **Gear** when utilized, either by **Gear Tags** or by name.

### Requirements
**Abilities** with *__Requirements__* will actively ask you for specific **Conditions** to be met before they're allowed to be used. Unlike **Costs**, *__Requirements__* are not actively consumed or destroyed upon use, instead acting moreso as a checklist for it to work at all. Once every **Condition** has been met, you may use the **Ability**. *__Requirements__* can have one or more of the following *Conditions*:
- <u>**Resource Condition:**</u> This **Condition** looks at one or more of your **Resources** and compares them to specific values. *(For example, if your Health is less than half its maximum.)*
- <u>**Gear Condition:**</u> This **Condition** looks at one or more pieces of **Gear** and compares them to specific values. *(For example, if one piece of Gear has the Sword Tag.)*
- <u>**Character Condition:**</u> This **Condition** looks at one or more characters and compares them to specific values. *(For example, if any nearby Characters are considered Allies.)*

### Targets, Frequency, and Duration
An **Ability** has a list of *__Targets__* it affects. *__Targets__* can be one or more of the following:
- <u>**Characters:**</u> One or more characters with specific qualities are targetable by this **Ability**.
- <u>**Objects:**</u> One or more objects with specific qualities are targetable by this **Ability**. *(Gear, Terrain, and non-living characters are considered objects.)*
- <u>**Groups:**</u> One or more groups of something with specific qualities are targetable by this **Ability**. *(Allies, Enemies, and All are considered groups.)*

An **Ability's** *__Frequency__* determines how often you can use it. *(For example, a Frequency of once per round means you can only use it once until the turn order goes around once.)*

An **Ability's** *__Duration__* determines how long it remains active. *(For example, a Duration of 5 rounds means whatever effects are active remain that way until the turn order goes around five times.)*

## Buying Abilities
*__Buying Abilities__* you make for yourself during the *Leveling Up* process involves spending **Ability Points** gained during that process. *Ability Properties* either increase or decrease the **Ability Point** cost of the **Ability** in question.

When *__Buying Abilities__*, each *Ability Property* has specific **Ability Point Cost** values, listed below. Positive **Ability Point Costs** must be paid, while negative **Ability Point Costs** grant extra **Ability Points** you can spend. You can only gain a total of extra **Ability Points** equal to your *Current Level x 2* from all additions and changes made this way each time you *__Buy Abilities__*.

If a new **Ability** would be created, you must give it a unique name.

| *__Type Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| *Active* | 0 | This **Ability** must be activated manually within its **Requirements'** restrictions before taking effect. |
| *Innate* | +2 if one or more **Requirements**, otherwise +6 | This **Ability** is always active if its **Requirements** are met. |

<br />

| *__Prerequisite Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| **Level** | -1 per X | This **Ability** can only be learned at **Level** **\[X\]** or higher. **\[X\]** *(Minimum of 0, Maximum of Current Level.)* |
| **Aptitude** | -1 per 5X, -1 per Y over 1 | This **Ability** can only be learned with **\[Y\]** matching **Aptitudes** at **\[X\]** or higher. *(Each Aptitude may have a different \[X\]. Minimum of +5, Maximum of +50.)* |
| **Natural Base Stats** | -1 per 5X, -1 per Y over 1 | This **Ability** can only be learned with **[\Y\]** matching **Base Stats** naturally at **\[X\]** or higher. *(Each Natural Base Stat may have a different \[X\]. Y begins at 0, Minimum 0.)* |

<br />

| *__Alternative Cost Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| **<i class="fa-solid fa-gem"></i>Action Points** | -2 per X over 1, +6 if X is 0 | This **Ability** costs **\[X\]** **<i class="fa-solid fa-gem"></i>Action Points** to utilize it. **Abilities** that cost 0 **Action Points** must either have another *__Alternative Cost__* or a **Frequency** above 0. *(X begins at 1, Minimum of 0, Maximum of 3.)* |
| **Resources** | -0.2 per X, -1 per Y over 1 | This **Ability** costs **\[X\]** from **\[Y\]** matching **Resources**. *(Each Resource Alternative Cost may have a different \[X\]. X begins at 1, Minimum 1. Y begins at 0, Minimum 0.)* |
| **Gear** | -0.2 per X, -1 per Y over 1 | This **Ability** costs **\[X\]** pieces of **Gear** with **\[Y\]** matching **Gear Tags**. The **Gear** consumed this way stays active until this **Ability** resolves. *(Each Gear Alternative Cost may have a different \[X\]. X begins at 1, Minimum 1. Y begins at 0, Minimum 0.)* |

<br />

| *__Requirement Condition Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| **Resource** Conditions | -0.1 per 10X, -1 per Y over 1 | This **Ability** can only be utilized if **\[Y\]** matching **Resources** are greater than or equal to **\[X\]** of their maximum values. *(Each Resource Condition may have a different \[X\]. Each \[X\] may be mirrored instead to check whether those Resources are less than or equal to the flip of that value. For example, greater than or equal to 20% mirrored becomes less than or equal to 80%. Minimum 10%, Maximum 100%.)* |
| **Gear** Conditions | -1 per X | This **Ability** can only be utilized with **Gear** that has **\[X\]** matching *Tags*. *(Minimum 0.)* |
| Character Conditions | -1 per X, -2 per Y over 1, -1 if also targeted | This **Ability** can only be utilized when **\[Y\]** different characters that have **\[X\]** matching properties are either just nearby or are nearby and also targeted. *(X begins at 0, Minimum 0. Y begins at 1, Minimum 1.)* |

<br />

| *__Other Property Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| *Frequency* | -0.5 per X | This **Ability** can only be used once every **\[X\]** rounds. *(Minimum 0.)* |
| *Duration* | +0.5 per X | This **Ability** lingers for a Duration of **\[X\]** rounds. *(X begins at 0, Minimum 0, Maximum 20. If X is 20, this Ability is permanent.)* |
| *Targets* | +1 per X over 1, +2 if X is All, +4 if X is Allies or Enemies. | This **Ability** hits **\[X\]** targets within reach. *(X begins at 1, Minimum 1, Maximum 4. X can also be Allies, Enemies, or All.)* |

## Effects
The *__Effects__* of each **Ability** can get really complex, enough so that this guide can't cover every instance. Both to stay with the active theme of *Simplicity First* and to ease you into the creative process a bit more, the following list of *__Effects__* will be basic building blocks that you can utilize in further ways:

| *__Effect Type__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| Activate Ability | +2 per X over 1 | This **Ability** activates **\[X\]** **Abilities** when it resolves. You may choose their order. Extra **Abilities** created this way have their **Ability Point Costs** added to this **Ability**. *(X begins at 0, Minimum 0.)* |
| Change Aptitude | +1 per 5X, +1 per Y over 1. | This **Ability** either increases or decreases the listed **\[Y\]** **Aptitudes** of its targets by **\[X\]**. You choose whether it increases or decreases when **Buying Abilities**. *(Each Aptitude may have a different \[X\]. X begins at 0, Minimum 0. Y begins at 1, Minimum 1.)* |
| Change Row | +2 if swap, +1 if fixed, 0 if neither | This **Ability** allows you to shift your position within your party's combat formation, either swapping between the **Front** and **Back Rows** or forcibly moving you to either **Row**. |
| Change Base Stat | +2 per 5X, +2 per Y over 1. | This **Ability** either increases or decreases the listed **\[Y\]** **Base Stats** of its targets by **\[X\]**. *(Each Base Stat may have a different \[X\]. X begins at 0, Minimum 0. Y begins at 1, Minimum 1.)* |
| Create Character | +1 per X over 1, +2 per Y, +1 per Z | This **Ability** creates **\[X\]** copies of **\[Y\]** unique characters at **Level \[Z\]**, placing them next to the **Ability's** target or targets of your choosing. *(X begins at 1, Minimum 1. Y and Z begin at 0, Minimum 0.)* |
| Create Gear | +1 | This **Ability** creates a piece of Gear near the **Ability's** target or targets that crumbles after its **Duration** ends. Requires at least one **Gear Tag** on the **Ability** to take this. |
| Is Illusory | -2 | This **Ability** is an illusion to its targets and requires a **d% Check** to determine whether or not it is fake. |
| Damage Resource | +2 per X over 1, +1 per 2Y over 2, +1 per Z over 1 | This **Ability** deals **\[X\]d\[Y\]** damage to each of its targets' listed **\[Z\] Resources** when it resolves. *(Each Damage may have a different \[X\]. X begins at 0, Minimum 0. Y begins at 2, Maximum of 12. Z begins at 1, Minimum 1, Maximum 3.)* |
| Destroy | \* | This **Ability** destroys its targets, completely vaporizing them. |
| Gain Temporary **<i class="fa-solid fa-gem"></i>Action Points** | \* | This **Ability** grants **\[X\]** temporary **<i class="fa-solid fa-gem"></i>Action Points** to its targets. Temporary **<i class="fa-solid fa-gem"></i>Action Points** are lost upon ending your **Turn** or changing your **Initiative**. |
| Has Base Stat | +6 if X is 3, +3 if X is 2, 0 if X is 1 | This **Ability** can only utilize the user's **\[X\]** listed **Base Stats** when referencing any of them. *(X begins at 1, Minimum 1, Maximum 3.)* |
| Has Element Tag | +1 per X over 1 | This **Ability** has **\[X\]** listed **Element Tags** that may determine its effectiveness when it resolves. *(X begins at 1, Minimum 1.)* |
| Has Gear Tag | +1 per X | This **Ability** has **\[X\]** listed **Gear Tags** that may determine its effectiveness when it resolves. *(X begins at 0, Minimum 0.)* |
| Has Success Range | -1 if it can Fail, -2 if it can't Critical Success, +2 if it can't Critical Failure | This **Ability** has a **d% Check** and can Suceed or Fail, either Critically or not. Each range may have one or more **Effects**. |
| Has Random Range | -1 per X | This **Ability** has **\[X\]** extra ranges that are applied at random to it that may determine its effectiveness when it resolves. Each range may have one or more **Effects**. *(X begins at 0, Minimum 0.)* |
| Has Reach | +2 per X over 1 | This **Ability** can reach up to **\[X\] Rows** away. *(X begins at 1, Minimum 1, Maximum 3.)* |
| Kill | \* | This **Ability** kills its targets. |
| Recover Resource | +2 per X over 1, +0.2 per 2Y over 2, +1 per Z over 1 | This **Ability** has each of its targets recover the listed **\[Z\] Resources** by **\[X\]d\[Y\]** when it resolves. *(Each Recovery may have a different \[X\]. X begins at 0, Minimum 0. Y begins at 2, Maximum 12. Z begins at 1.)* |

*__Effects__* with an **Ability Point Cost** of \* can't be purchased by player characters.

## Element Tags
An **Ability's Effects** utilize and reference a number of *__Element Tags__*. Like **Gear Tags**, *__Element Tags__* are used as a form of restriction and classification of what your **Abilities** can offer you. The following *__Element Tag__* list is what this SRD utilizes in all of its content, but feel to make your own:
- Slashing
- Piercing
- Bludgeoning
- Fire
- Water
- Ice
- Earth
- Air
- Lightning
- Poison
- Life
- Metal
- Radiant
- Umbral
- Aging
- Cosmic
- Mental
- Spirit
- Void

## Elemental Effectiveness
Whenever you activate an **Ability**, that **Ability's** *__Elemental Effectiveness__* takes into consideration all **Element Tags** related to it. An **Ability** can be **Absorbed**, **Resisted**, **Effective**, **Powerful**, or **Severe**. Characters and objects may have one or more **Resistances** or **Weaknesses** related to specific **Element Tags**.

The following order of operations is used to determine the final result of the *__Elemental Effectiveness__*:
1. If the **Ability's** targets fully **Resist** all **Element Tags** from it, that **Ability** is **Absorbed**, doing absolutely nothing. Otherwise, continue.
2. If the **Ability's** targets **Resist** some, *but not all* **Element Tags** from it and aren't **Weak** to any of its **Element Tags**, that **Ability** is **Resisted**, halfing its *__Effectiveness__* rounded up. Otherwise, continue.
3. If the **Ability's** targets **Resist** none of its **Element Tags** from it and aren't **Weak** to any of its **Element Tags**, that **Ability** is **Effective** and works normally. Otherwise, continue.
4. If the **Ability's** targets are **Weak** to some, *but not all*, **Element Tags** from it, even if they would **Resist** some of them, that **Ability** is **Powerful** and has double its normal *__Effectiveness__*. Otherwise, continue.
5. If the **Ability's** targets are **Weak** to all **Element Tags** from it, that **Ability** is **Severe** and has *quadruple* its normal *__Effectiveness__*.
