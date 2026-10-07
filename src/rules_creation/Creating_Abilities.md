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
- <u>**Resources:**</u> **<a style="color:#c040ff"><i class="fa-solid fa-heart"></i>Health</a>**, **<a style="color:#ffc040"><i class="fa-solid fa-person-running"></i>Stamina</a>**, and/or **<a style="color:#40ff40"><i class="fa-solid fa-bolt"></i>Energy</a>** must be spent before the **Ability** can be utilized. You don't have the capability to spend those **Resources** if you have less than the required amount above the minimum of 0 in that **Resource**.
- <u>**Gear:**</u> The **Ability** consumes specific **Gear** when utilized, either by **Gear Tags** or by name.

### Requirements
**Abilities** with *__Requirements__* will actively ask you for specific **Conditions** to be met before they're allowed to be used. Unlike **Costs**, *__Requirements__* are not actively consumed or destroyed upon use, instead acting moreso as a checklist for it to work at all. Once every **Condition** has been met, you may use the **Ability**. *__Requirements__* can have one or more of the following *Conditions*:
- <u>**Resource Condition:**</u> This **Condition** looks at one or more of your **Resources** and compares them to specific values. *(For example, if your Health is less than half its maximum.)*
- <u>**Gear Condition:**</u> This **Condition** looks at one or more pieces of **Gear** and compares them to specific values. *(For example, if one piece of Gear has the Sword Tag.)*
- <u>**Character Condition:**</u> This **Condition** looks at one or more characters and compares them to specific values. *(For example, if any nearby Characters are Humanoid.)*

### Targets, Frequency, and Duration
An **Ability** has a list of *__Targets__* it affects. While normally listed as a number, *__Targets__* can be one or more of the following:
- <u>**Characters:**</u> One or more characters are targetable by this **Ability**.
- <u>**Objects:**</u> One or more objects are targetable by this **Ability**. *(Gear, Terrain, and non-living characters are considered objects.)*
- <u>**Groups:**</u> One or more groups are targetable by this **Ability**. *(All Allies, All Enemies, and All are considered groups.)*

An **Ability's** *__Frequency__* determines how often you can use it. *(For example, a Frequency of once per round means you can only use it once until the start of the next Round.)*

An **Ability's** *__Duration__* determines how long it remains active. While in combat, an **Ability** with a *__Duration__* higher than 0 rounds only triggers once per **Round**, either at the start or end of its targets' **Turns** at the user's discretion. *(For example, a Duration of 5 rounds means whatever effects are active remain that way until the turn order goes around five times.)*

## Buying Abilities
*__Buying Abilities__* you make for yourself during the *Leveling Up* process involves spending **Ability Points** gained during that process. *Ability Properties* either increase or decrease the **Ability Point Cost** of the **Ability** in question.

When *__Buying Abilities__*, each **Ability Property** has specific **Ability Point Cost** values, listed below. Positive **Ability Point Costs** must be paid, while negative **Ability Point Costs** grant extra **Ability Points** you can spend. You can only gain a total of extra **Ability Points** equal to your current **Level** from all additions and changes made this way each time you *__Buy Abilities__*.

If a new **Ability** would be created, you must give it a unique name.

| *__Type Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| Active | 0 | This **Ability** must be activated manually before taking effect and can only be activated if its **Ability Properties** are satisfied. Requires at least one **Alternative Cost** over 0 on this **Ability**. |
| Innate | +1 | This **Ability** may initially activate only once each **Turn**. This **Ability** activates if its **Ability Properties** are satisfied and remains active for its **Duration**. Requires at least one **Requirement** on this **Ability**. |

<br />

| *__Prerequisite Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| Level | -1 per X | This **Ability** can only be learned at **Level** **\[X\]** or higher. **\[X\]** *(\[X\] begins at 0, Minimum of 0, Maximum of Current Level.)* |
| Aptitude | -1 per X, -1 per Y over 1 | This **Ability** can only be learned with **\[Y\]** matching **Aptitudes** at **\[5X\]** or higher. *(Each Aptitude may have a different \[X\]. \[X\] begins at 0, Minimum of +0, Maximum of +10. \[Y\] begins at 1, Minimum 1.)* |
| Natural **Base Stats** | -1 per X, -1 per Y over 1 | This **Ability** can only be learned with **\[Y\]** matching **Base Stats** naturally at **\[5X\]** or higher. *(Each Natural Base Stat may have a different \[X\]. \[X\] begins at 0, Minimum 0. \[Y\] begins at 1, Minimum 1, Maximum 3)* |

<br />

| *__Alternative Cost Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| <i class="fa-solid fa-gem"></i>Action Points | -2 per X over 1, +4 if X is 0 | This **Ability** costs **\[X\]** **<i class="fa-solid fa-gem"></i>Action Points** to utilize it. **Abilities** that cost 0 **Action Points** must either have another *__Alternative Cost__* or a **Frequency** above 0. *(\[X\] begins at 1, Minimum of 0, Maximum of 3.)* |
| Resources | -0.2 per X, -1 per Y over 1 | This **Ability** costs **\[X\]** from **\[Y\]** matching **Resources**. *(Each Resource Alternative Cost may have a different \[X\]. X begins at 1, Minimum 1. Y begins at 0, Minimum 0.)* |
| Gear | -1 per X, -1 per Y over 1 | This **Ability** costs **\[X\]** pieces of **Gear** with **\[Y\]** matching **Gear Tags**. **Gear** consumed this way is not consumed until this **Ability** resolves. Requires at least one **Gear Tag** on this **Ability**. *(Each Gear Alternative Cost may have a different \[X\]. \[X\] begins at 0, Minimum 0. \[Y\] begins at 1, Minimum 1.)* |

<br />

| *__Requirement Condition Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| **Resource** Conditions | -0.2 per X, -1 per Y over 1 | This **Ability** can only be utilized if **\[Y\]** matching **Resources** are less than or equal to **\[10X\]%** of their maximum values. *(Each Resource Condition may have a different \[X\]. Each \[X\] may be mirrored instead to check whether those Resources are less than or equal to the flip of that value. For example, less than or equal to 20% mirrored becomes greater than or equal to 80%. \[X\] begins at 0, Minimum 0, Maximum 10. \[Y\] begins at 1, Minimum 1, Maximum 3.)* |
| User **Tag** Conditions | -1 per X over 1 | This **Ability** can only be activated with **Gear** or by characters that have up to **\[X\]** matching **Tags**. Requires at least one **Tag** on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Target **Tag** Conditions | -1 per X | This **Ability** can only target characters that have at least **\[X\]** matching **Race Tags**. Requires at least one **Race Tag** on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |

<br />

| *__Other Property Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| Fast | +6 | This **Ability's** **Frequency** and **Duration** use **Turns** instead of **Rounds** as it enters the *Stack*. Requires **Frequency** over 0 and/or **Duration** over 0 on this **Ability**. |
| Frequency | -1 per X | This **Ability** can only be activated once every **\[X\]** rounds. **Frequency** immediately applies once this **Ability** enters the *Stack*. *(\[X\] begins at 0, Minimum 0, Maximum 10.)* |
| Duration | +1 per X | This **Ability** lingers for **\[X\]** rounds. A **Duration** of 0 causes the ability to stop existing once it resolves. *(\[X\] begins at 0, Minimum 0, Maximum 20.)* |
| Targets | +1 per X over 1, +4 if X is All, +6 if X is All Allies or All Enemies. | This **Ability** affects at least 1 target and up to **\[X\]** targets within reach. *(\[X\] begins at 1, Minimum 1. \[X\] can be All Allies, All Enemies, or All instead of a number.)* |
| Can Target Self | 0 | This **Ability** may target its user. |
| Has **Base Stat** | +2 per X over 1 | This **Ability** can only utilize the user’s **\[X\]** listed **Base Stats** when referencing any of them. *(\[X\] begins at 1, Minimum 1, Maximum 3.)* |
| Has Critical Range | -2 | This **Ability** can **Critical Success** and **Critical Failure**. Each range may have one or more **Effects**. Requires *Has Failure Range* on this **Ability**. **Critical Failure** must affect the user negatively in some fashion at the GM's discretion. |
| Has **Element Tags** | +1 per X over 1 | This **Ability** has **\[X\]** listed **Element Tags** that may determine its effectiveness when it resolves. *(\[X\] begins at 0, Minimum 0.)* |
| Has Failure Range | -1 | This **Ability** has a **Contested d% Check** and can **Succeed** or **Fail**. Each range may have one or more **Effects**. **Failure** must affect the user negatively in some fashion at the GM's discretion. |
| Has **Gear Tags** | +1 per X over 1 | This **Ability** has **\[X\]** listed **Gear Tags** that may determine its effectiveness when it resolves. *(\[X\] begins at 0, Minimum 0.)* |
| Has **Race Tags** | +1 per X over 1 | This **Ability** has **\[X\]** listed **Race Tags** that may determine its effectiveness when it resolves. *(\[X\] begins at 0, Minimum 0.)* |
| Has Random Range | -2 per X | This **Ability** has **\[X\]** extra ranges that are applied at random to it that may determine its effectiveness when it resolves. Each range may have one or more **Effects**. *(If \[X\] is above 0, roll 1d(\[X\]+1) to determine which range to use. \[X\] begins at 0, Minimum 0.)* |
| Has Reach | +2 per X over 1 | This **Ability** can reach up to **\[X\] Rows** away. *(\[X\] begins at 1, Minimum 1, Maximum 3.)* |

## Effects
The *__Effects__* of each **Ability** can get really complex, enough so that this guide can't cover every instance. Both to stay with the active theme of *Simplicity First* and to ease you into the creative process a bit more, the following list of *__Effects__* will be basic building blocks that you can utilize in further ways:

| *__Effect Type__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| :-: | :-: | --- |
| Activate **Ability** | 0 | This **Ability** activates one new **Ability** during its resolution. **Abilities** created this way can only have unique **Tags**, **Duration**, **Effect Ranges**, **Targets**, **Base Stats**, and **Reach**, their **Ability Point Costs** are added to this **Ability**, they have **Frequency** 0, and they don't enter the *Stack*, instead fully resolving in FIFO order as an **Effect** when they activate. Requires at least one **Alternative Cost** and/or **Frequency over 0 on this **Ability**. |
| Affects **Gear** | 0 | This **Ability** applies Damage, Recovery, or **Tags** to its targets' **Gear** instead. The user decides what **Gear** it hits for each target. |
| Change **Aptitude** | +1 per X | This **Ability** either increases or decreases one **Aptitude** of its targets by **\[5X\]**. You choose whether it increases or decreases when **Buying Abilities**. This **Effect** can be taken multiple times, each time choosing a different **Aptitude**. *(\[X\] begins at 0, Minimum 0, Maximum 10.)* |
| Change **Base Stat** | +2 per X, +2 per Y over 1. | This **Ability** either increases or decreases the listed **\[Y\]** **Base Stats** of its targets by **\[5X\]**. *(Each Base Stat may have a different \[X\]. \[X\] begins at 0, Minimum 0. \[Y\] begins at 1, Minimum 1.)* |
| Change Damage Input | +1 per X | This **Ability** either increases or decreases its targets' damage input by **\[X\]**. Requires at least one **Element Tag** and **Duration** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Change Damage Output | +1 per X | This **Ability** either increases or decreases its targets' damage output by **\[X\]**. Requires at least one **Element Tag** and **Duration** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Change **<i class="fa-solid fa-person-falling"></i>Evasion** | +1 per X | This **Ability** either increases of decreases its targets' **<i class="fa-solid fa-person-falling"></i>Evasion** by **\[5X\]**. *(\[X\] begins at 0, Minimum 0, Maximum 10.)* |
| Change **Initiative** | +2 per X | This **Ability** either increases or decreases its targets' **Initiative** by **\[5X\]**. *(\[X\] begins at 0, Minimum 0.)* |
| Change Recovery Input | +1 per X | This **Ability** either increases or decreases its targets' recovery input by **\[X\]**. Requires at least one **Element Tag** and **Duration** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Change Recovery Output | +1 per X | This **Ability** either increases or decreases its targets' recovery output by **\[X\]**. Requires at least one **Element Tag** and **Duration** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Change **Row** | +2 if Swapping, +1 if Forced, 0 if neither | This **Ability** allows the user to shift its targets' positions within their party's combat formation, either swapping between the **Front** and **Back Rows** or forcibly moving to either **Row**. Requires **Duration** 0 on this **Ability**. |
| Change **Size** | +4 per X | This **Ability** scales its targets' **Size** by **\[X\]** steps, recalculating their **Heft**, **<i class="fa-solid fa-person-falling"></i>Evasion**, and maximum **<a style="color:#c040ff"><i class="fa-solid fa-heart"></i>Health</a>**. Requires **Duration** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Change **Tags** | +2 per X | This **Ability** grants its targets **\[X\]** different **Tags**. If a **Tag** is an **Element Tag**, choose either **Resistance** or **Weakness** for that **Tag** when **Buying Abilities**. If a **Tag** is a **Gear Tag**, choose either *Adept* or *Inept* when **Buying Abilities**. If a **Tag** is a **Gear Slot Tag**, choose either to add or subtract 1 from its *Count* when **Buying Abilities**. Requires at least one **Tag** on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Confuse | +6 | This **Ability** confuses its targets, making them choose their **Abilities** and targets randomly during their **Turns**. Requires *Has Failure Range* and **Duration** over 0 on this **Ability**. |
| Create Character | +1 per X over 1, +3 per Y, +1 per Z | This **Ability** creates **\[X\]** copies of **\[Y\]** new characters within range at **Level \[Z\]** that dissipate after its **Duration** ends, placing them next to the **Ability's** targets in a **Row** of your choosing. This may cause that enemy group to become **Surrounded**. Characters created this way share your **Initiative** and **Action Points**, and are under your control. When **Buying Abilities**, you also **Buy Abilities** for characters created this way using their **Level** to calculate their **Ability Points**. *(\[X\] begins at 1, Minimum 1. \[Y\] and \[Z\] begin at 0, Minimum 0.)* |
| Create **Gear** | +1 | This **Ability** creates one piece of **Gear** for each of the **Ability's** targets that dissipates after its **Duration** ends. The created **Gear** must have one **Gear Slot Tag** of either *Head*, *Body*, *Foot*, *Hand*, or *Accessory*. It has 0 **Heft** and **Density**, has **Durability** equal to 5 plus your **Level** x 5, and may have one new **Ability** with an **Ability Point Cost** equal to your **Level** or lower. **Abilities** created this way have their **Ability Point Costs** added to this **Ability**. Requires at least one **Gear Tag** on this **Ability**. This **Effect** can be taken multiple times to create more **Gear**, each one potentially choosing a new **Gear Tag** available within this **Ability**. |
| Damage **Resource** | +1 per X, +1 per Y over 1, +1 per Z | This **Ability** deals **\[X\]d\[2Y\]+\[Z\]** damage to each of its targets' specific **Resource(s)** when it resolves. Requires at least one **Element Tag** on this **Ability**. This **Effect** can be taken multiple times, each time choosing a different **Element Tag** and potentially choosing a different **Resource** to affect. *(\[X\] begins at 0, Minimum 0. \[Y\] begins at 1, Minimum 1, Maximum 6. \[Z\] begins at 0, Minimum 0.)* |
| Destroy | ? | This **Ability** destroys its targets, completely vaporizing them. Requires **Duration** 0 on this **Ability**. |
| Dispel **Ability** | +4 | This **Ability** dispels one of its targets' active **Abilities**, removing its **Effects** from those targets when it resolves. |
| End Turn | +2 | This **Ability** immediately ends its targets' current **Turns**. If it's not their **Turn**, nothing happens. Requires **Duration** 0 on this **Ability**. |
| Flank | +4 | This **Ability** allows its targets to shift **Rows** into another allied group of characters. This may cause one or more enemy groups to become **Surrounded** or **Ambushed**. If another allied group of characters doesn't exist, create a new one with this **Ability's** targets. Requires *Change Row* at +2, *End Turn*, **Can Target Self**, **Targets** Allies, and **Duration** 0. |
| Gain **<i class="fa-solid fa-shield-halved"></i>Conditional Defense** | +1 per X | This **Ability** grants its targets' **\[X\]** **<i class="fa-solid fa-shield-halved"></i>Conditional Defense**. Requires at least one **Tag** on this **Ability**. *(\[X\] begins at 0, Minimum 0)*. |
| Gain **<i class="fa-solid fa-shield-halved"></i>Global Defense** | +4 per X | This **Ability** grants its targets' **\[X\]** **<i class="fa-solid fa-shield-halved"></i>Global Defense**. *(\[X\] begins at 0, Minimum 0)*. |
| Gain Temporary **<i class="fa-solid fa-gem"></i>Action Points** | ? | This **Ability** grants **\[X\]** temporary **<i class="fa-solid fa-gem"></i>Action Points** to its targets. Temporary **<i class="fa-solid fa-gem"></i>Action Points** are lost upon ending your **Turn**. |
| Invert Damage When **Resistance** | ? | Instead of dealing damage, This **Ability** recovers its targets equal to the damage's **Effective** value when that damage is **Resisted** or **Absorbed**, ignoring **Elemental Effectiveness**. |
| Invert Recovery When **Weakness** | ? | Instead of recovering damage, This **Ability** deals damage to its targets equal to that recovery's **Effective** value when that recovery is **Weak** or **Severe**, ignoring **Elemental Effectiveness**. |
| Kill | ? | This **Ability** kills its targets. Requires **Duration** 0 on this **Ability**. |
| Provoke | +2 | This **Ability** forces its targets' **Abilities** to target this **Ability's** user if applicable. If any targets of this **Ability** are already under another *Provoke* **Effect**, replace the old instance with this one. Requires **Duration** over 0 on this **Ability**. |
| Randomly Targets | -2 | This **Ability** randomly selects its' targets within reach if applicable. |
| Recover **Resource** | +1 per X, +1 per Y, +1 per Z | This **Ability** recovers each of its targets specific **Resource(s)** by **\[X\]d\[2Y\]+\[Z\]** when it resolves. Requires at least one **Element Tag** on this **Ability**. This **Effect** can be taken multiple times, each time choosing a different **Element Tag** and potentially choosing a different **Resource** to affect. Requires **Frequency** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0. \[Y\] begins at 0, Maximum 6. \[Z\] begins at 0, Minimum 0.)* |
| Repel | +6 | This **Ability** grants its targets a barrier that reflects damage and recovery of the associated **Element Tags** back to its caster. Damage and Recovery reflected this way can only be reflected once. This **Ability** supercedes **Elemental Effectiveness**. Requires at least one **Element Tag** and **Duration** over 0 on this **Ability**. |
| Restrict **Effects** | +2 per X | This **Ability** restricts its targets, preventing the listed **\[X\] Effects** from resolving. **Abilities** with any of the listed **Effects** still resolve, skipping the listed **Effects** outright. Requires at least **\[X\]** different **Effects** and **Duration** over 0 on this **Ability**. **Abilities** with this **Effect** can't prevent the *Activate Ability*, *Damage Resource*, or *Recover Resource* **Effects**. *(\[X\] begins at 0, Minimum 0.)*
| Restrict **Tags** | +2 | This **Ability** restricts its targets, preventing them from activating **Abilities** that have at least one of the listed **Tags** unless those targets have at least one of the listed **Tags**. Requires at least one **Tag** and **Duration** over 0 on this **Ability**. *(\[X\] begins at 0, Minimum 0.)* |
| Revive | +12 | This **Ability** revives unconscious, dying, or dead targets when it resolves, setting their *__<a style="color:#c040ff"><i class="fa-solid fa-heart"></i>Health</a>__* to 1 and they stablize, no longer unconscious, dying, or dead. Requires **Type Active**, **Frequency** over 0, and **Duration** 0 on this **Ability**. **Abilities** that have this **Effect** can't have **Fast**. |
| Skip Next Turn | +10 | This **Ability** forcibly skips its targets' next **Turns**. Requires *Has Failure Range* and **Duration** over 0 on this **Ability**. |
| Steal | +6 | This **Ability** takes its targets, putting them under your control. Characters targeted and affected by this **Ability** that **Fail** the **Contested d% Check** are considered Allies to the user for its **Duration**, entering the same **Row** as the user. Upon its **Duration** finishing, characters by this **Ability** return to their original allied group of characters in the closest **Row** available. Requires *Has Failure Range* and, if *Affects Gear* is on this **Ability**, **Duration** 0 on this **Ability**. |
| Stun | +4 | This **Ability** stuns its targets', only allowing them to use a single **Ability** during their **Turns**. Requires *Has Failure Range* and **Duration** over 0 on this **Ability**. |

> [!NOTE]
> *__Effects__* with an **Ability Point Cost** of **?** can't be purchased by player characters if they make their own **Abilities**. The GM may utilize these *__Effects__* and grant them to player **Abilities**.

## Element Tags
An **Ability's Effects** utilize and reference a number of *__Element Tags__*. Like **Gear Tags**, *__Element Tags__* are used as a form of restriction and classification of what your **Abilities** can offer you. The following *__Element Tag__* list is what this SRD utilizes in all of its content, but feel to make your own:
- Slashing
- Piercing
- Bludgeoning
- Fire
- Cold
- Earth
- Air
- Lightning
- Life
- Metal
- Radiant
- Umbral
- Age
- Cosmic
- Mental
- Spirit

## Elemental Effectiveness
Whenever you activate an **Ability**, that **Ability's** *__Elemental Effectiveness__* takes into consideration all **Element Tags** related to it. An **Ability** can be **Absorbed**, **Resisted**, **Effective**, **Powerful**, or **Severe**. Characters and objects may have one or more **Resistances** or **Weaknesses** related to specific **Element Tags**.

The following order of operations is used to determine the final result of the *__Elemental Effectiveness__*:
1. If the **Ability's** targets fully **Resist** all **Element Tags** from it, that **Ability** is **Absorbed**, doing absolutely nothing. Otherwise, continue.
2. If the **Ability's** targets **Resist** some, *but not all* **Element Tags** from it and aren't **Weak** to any of its **Element Tags**, that **Ability** is **Resisted**, halfing its *__Effectiveness__* rounded up. Otherwise, continue.
3. If the **Ability's** targets **Resist** none of its **Element Tags** from it and aren't **Weak** to any of its **Element Tags**, that **Ability** is **Effective** and works normally. Otherwise, continue.
4. If the **Ability's** targets are **Weak** to some, *but not all*, **Element Tags** from it, even if they would **Resist** some of them, that **Ability** is **Powerful** and has double its normal *__Effectiveness__*. Otherwise, continue.
5. If the **Ability's** targets are **Weak** to all **Element Tags** from it, that **Ability** is **Severe** and has *quadruple* its normal *__Effectiveness__*.
