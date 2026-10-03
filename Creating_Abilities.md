# Creating Abilities
This page lists a large set of information related to *__Creating Abilities__*. When *__Creating Abilities__*, you'll want to conceptualize how the **Ability** will actively function. Once you have the **Ability** you want in mind, this page may help you to figure out how to piece it together.

> [!Warning]
> **Creating Abilities** is a time-consuming process; You'll be building **Abilities** *piece by piece* to get the desired effect. I recommend starting small and simple, building things up slowly over time as you **Level Up**. Once you get the hang of it, feel free to make your **Abilities** more complex and interesting.

## Ability Properties
As mentioned under the **Core Rules** page, **Abilities** have various *__Ability Properties__* that define basic information about how to utilize them. *__Ability Properties__* explain potential restrictions and interactions the **Ability** they're associated with has. They are listed and explained below:

- *Type:* The *Type* of an **Ability** is either *Active* or *Innate*; *Active* **Abilities** require you to specifically activate them before they can take effect, while *Innate* **Abilities** automatically activate themselves based on other *__Ability Property__* restrictions.
- *Prerequisites:* The **Ability** can't be learned unless the character learning it meets its *Prerequisites*. *Prerequisites* can be one or more of the following:
  - *Level:* The **Ability** can only be learned at this *Level* or higher.
  - *Aptitude:* The **Ability** can only be learned if you have this *Aptitude* at the listed value or higher.
  - *Natural Base Stats:* The **Ability** can only be learned if the listed *Base Stats* before *Gear* and **Ability** *Boosts* and *Penalties* are at the listed values or higher.
- *Alternative Costs:* The *Alternative Costs* of an **Ability** list what it consumes before it can be utilized. You can't spend what you don't have. *Alternative Costs* can be one or more of the following:
  - *Action Points:* The **Ability** requires you to spend this many *Action Points* before it can be utilized.
  - *Resources:* **Health**, **Stamina**, and/or **Energy** must be spent before the **Ability** can be utilized. You don't have the *Resources* to spend if you have less than the required amount above the minimum of 0 in that *Resource*.
  - *Gear:* The **Ability** consumes specific *Gear* when utilized, either by *Tags* or by *Gear* name.
- *Requirements:* **Abilities** with *Requirements* will actively ask you for specific *Conditions* to be met before they're allowed to be used. Unlike *Costs*, *Requirements* are not actively consumed or destroyed upon use, instead acting moreso as a checklist for it to work at all. Once every *Condition* has been met, you may use the **Ability**. *Requirements* can have one or more of the following *Conditions*:
  - *Resource Conditional Check:* This *Conditional Check* looks at one or more of your *Resources* and compares them to specific values. *(For example, if your Health is less than half its maximum.)*
  - *Tag Conditional Check:* This *Conditional Check* looks at one or more *Tags* of *Gear* and compares them to specific values. *(For example, if one piece of Gear has the Sword Tag.)*
  - *Character Conditional Check:* This *Conditional Check* looks at one or more *Characters* and compares them to specific values. *(For example, if any nearby Characters are considered Allies.)*
- *Targets:* The **Ability** has a list of *Targets* it affects.
  - *Characters:* One or more *Characters* with specific qualities are targetable by this **Ability**.
  - *Objects:* One or more *Objects* with specific qualities are targetable by this **Ability**.
- *Frequency:* An **Ability's** *Frequency* determines how often you can use it. *(For example, a Frequency of once per round means you can only use it once until the turn order goes around once.)*
- *Duration:* An **Ability's** *Duration* determines how long it remains active. *(For example, a Duration of 5 rounds means whatever effects are active remain that way until the turn order goes around five times.)*
- *Effects:* An **Ability's** *Effects* determine what the **Ability** actually does while it's active.

## Buying Abilities
*__Buying Abilities__* you make for yourself during the *Leveling Up* process involves spending **Ability Points** gained during that process. *Ability Properties* either increase or decrease the **Ability Point** cost of the **Ability** in question.

When *__Buying Abilities__*, each *Ability Property* has specific **Ability Point Cost** values, listed below. Positive **Ability Point Costs** must be paid, while negative **Ability Point Costs** grant extra **Ability Points** you can spend. You can only gain a total of extra **Ability Points** equal to your *Current Level x 2* from all additions and changes made this way each time you *__Buy Abilities__*.

| *__Type Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| --- | --- | --- |
| Active | -2 | This **Ability** must be activated manually within its *Requirements'* restrictions before taking effect. |
| Innate | 0 | This **Ability** is always active if its *Requirements* are met. |

| *__Prerequisite Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| --- | --- | --- |
| Level | -1 per X | This **Ability** can only be learned at *Level* **\[X\]** or higher. **\[X\]** *(Minimum of 0, Maximum of Current Level.)* |
| Aptitude | -0.2 per X in increments of +5, -1 per Y over 1 | This **Ability** can only be learned with **\[Y\]** matching **Aptitudes** at **\[X\]** or higher. *(Each Aptitude may have a different \[X\]. Minimum of +5, Maximum of +50.)* |
| Natural Base Stats | -0.2 per X in increments of +5, -1 per Y over 1 | This **Ability** can only be learned with **[\Y\]** matching **Base Stats** naturally at **\[X\]** or higher. *(Each Natural Base Stat may have a different \[X\]. Minimum of +5.)* |

| *__Alternative Cost Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| --- | --- | --- |
| Action Points | -2 per X over 1, +2 if X is 0 | This **Ability** costs **\[X\]** **Action Points** to utilize it. *(X begins at 1, Minimum of 0, Maximum of 3.)* |
| Resources | -0.2 per X, -1 per Y over 1 | This **Ability** costs **\[X\]** from **\[Y\]** matching **Resources**. *(Each Resource Cost may have a different \[X\]. X begins at 1, Minimum 1.)* |
| Gear | -0.2 per X, -1 per Y over 1 | This **Ability** costs **\[X\]** pieces of **\[Y\]** matching **Gear**. *(Each Gear Cost may have a different \[X\]. Minimum 1.)* |

| *__Requirement Conditional Values__* | *__Ability Point Costs__* | *__Effect Explanation__* |
| --- | --- | --- |
| Resource Checks | -0.1 per X in increments of 10%, -1 per Y over 1 | This **Ability** can only be utilized if **\[Y\]** matching **Resources** are greater than or equal to **\[X\]** of their maximum values. *(Each Resource Check may have a different \[X\]. Each \[X\] may be mirrored instead to check whether those Resources are less than or equal to the flip of that value. For example, greater than or equal to 20% mirrored becomes less than or equal to 80%. Minimum 10%, Maximum 100%.)* |
| Tag Checks | -1 per X | This **Ability** can only be utilized with **Gear** that has **\[X\]** matching *Tags*. *(Minimum 0.)* |
| Character Checks | -1 per X, -2 per Y over 1 | This **Ability** can only be utilized with **\[Y\]** different characters that have **\[X\]** matching properties. *(Y begins at 1.)* |

