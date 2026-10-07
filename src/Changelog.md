# Changelog
Changes to the SRD are found here, with more recent changes appearing near the top.

## October 6, 2026
> [!CAUTION]
> I ended up using ChatGPT to find whether or not there were infinite loops or triggers with Abilities, so this update fixes most of the Ability oversights found this way.
### Additions
- Added **Ability** First-In-Last-Out *Stack* resolution rules to *Introduction.md*.
- Added the following **Effects** to *Creating_Abilities.md*.
  - Restrict **Effects**
  - Restrict **Tags**
- Added the following **Ability Properties** to *Creating_Abilities.md*.
  - Fast
- Added **Effect** First-In-First-Out **Ability** resolution rules to *Introduction.md.*
- Added mention of characters from Create Character **Effect** dissipating when its **Ability's Duration** ends.
### Changes
- Changed *Duration* **Ability Property** to specify when an **Ability** ends when it's **Duration** is 0.
- Changed *Innate* **Abilities** to only activate once each turn and to stay active once initially activated for their **Duration**.
- Changed *Frequency* **Ability Property** to apply immediately upon **Abilities** being put in the *Stack*.
- Changed Repel **Effect** to supercede **Elemental Effectiveness**.
- Changed Revive **Effect** to have **Ability Point Cost** 12, require **Type Active**, **Frequency** over 0, and **Duration** 0, and an **Ability** with the Revive **Effect** can't have the Fast **Effect**.
- Changed Damage Resource **Effect** to not always use dice and its **Ability Point Cost** for extra dice from +2 to +1.
- Changed Recover Resource **Effect** to not always use dice and it now requires **Frequency** over 0.
- Changed the following **Effects** to **Ability Properties**.
  - Can Target Self
  - Has **Base Stat**
  - Has Critical Range
  - Had **Element Tags**
  - Has Failure Range
  - Has **Gear Tags**
  - Has **Race Tags**
- Changed Gear Conditions **Ability Property** to User **Tag** Conditions.
- Changed Character Conditions **Ability Property** to Target **Tag** Conditions.
- Changed Provoke **Effect** to always replace old instances when a new one is applied.
- Changed Has Element Tags **Ability Property's Ability Point Cost** from +1 per X to +1 per X over 1.
- Changed Activate Ability **Effect** to have only certain **Ability Properties** be allowed.
- Changed Invert Damage When Absorbed **Effect** to Invert Damage When Resistance, increasing its possible Effectiveness Range.
- Changed Invert Recovery When Severe **Effect** to Invert Recovery When Weakness, increasing its possible Effectiveness Range.
- Gave quite a few **Effects** a required **Duration** value.
- Fixed some wording issues.
### Removals
- Removed Is Illusion **Effect**. You can get a similar effect with Has Failure Range instead.

## October 5, 2026
### Additions
- Added the following **Effects** to *Creating_Abilities.md*.
  - Confuse
  - Flank
  - Repel
  - Steal
  - Stun
- Added the necessity to **Buy Abilities** for characters created from the Create Character **Effect** in *Creating_Abilities.md*.
### Changes
- Further fleshed out the Create Gear **Effect** in *Creating_Abilities.md*.
- Changed the Affects Gear **Effect** to cause that **Ability** to only hit its targets' **Gear**.
- Changed the Affects Gear **Effect** to allow the user to choose what **Gear** it hits instead of the GM.
- The following **Effects** in *Creating_Abilities.md* now require at least one **Element Tag**.
  - Change Damage Input
  - Change Damage Output
  - Change Recovery Input
  - Change Recovery Output
  - Damage **Resource**
  - Randomly Targets
  - Recover **Resource**
- Changed how the variables listed in *Creating_Abilities.md* are calculated to make them more clear (hopefully).
- Reworked the *Dispel Ability* **Effect** in *Creating_Abilities.md*.
  - It no longer prevents **Ability** activation and resolution.
- Changed *Targets* **Ability Property** in *Creating_Abilities.md* to always affect a minimum of 1 target.
- Changed *Active* and *Innate Type* **Ability Properties** slightly in *Creating_Abilities.md*.
- Changed *Duration* **Ability Property** in *Creating_Abilities.md* to allow the user of that **Ability** to determine when its once per **Round** effect goes off.
- Changed *Change Row* **Effect** so that it works on enemy targets properly.

## October 4, 2026
### Additions
- Added Character **Tags** in *Character_Creation.md*.
- Added the following **Race Tags** to *Character_Creation.md*.
  - Alien
  - Angel
  - Animal
  - Avatar
  - Abberation
  - Arachnid
  - Beast
  - Bird
  - Celestial
  - Construct
  - Deity
  - Demon
  - Dragon
  - Entity
  - Fey
  - Horror
  - Humanoid
  - Insect
  - Otherworldly
  - Reptile
  - Seacreature
  - Serpent
  - Spirit
  - Vampire
  - Wereanimal
- Added mention of how **Experience** is acquired from combat in *Combat_Rules.md*.
- Added the following **Effects** to *Creating_Abilities.md*.
  - Affects **Gear**
  - Can Target Self
  - Change Damage Input
  - Change Damage Output
  - Change **<i class="fa-solid fa-person-falling"></i>Evasion**
  - Change Recovery Input
  - Change Recovery Output
  - Change Size
  - Change Tags
  - Dispel **Ability**
  - End Turn
  - Gain **<i class="fa-solid fa-shield-halved"></i>Conditional Defense**
  - Gain **<i class="fa-solid fa-shield-halved"></i>Global Defense**
  - Has Critical Range
  - Has **Race Tag**
  - Invert Damage When **Absorbed**
  - Invert Recovery When **Severe**
  - Provoke
  - Revive
  - Skip Next Turn
- Added a new set of **Effects** to the *Pass* **Basic Ability** found in *Combat_Rules.md*.
  - The old version of *Pass* was renamed to *Postpone*, and then renamed to *Wait*.
- Added a Tip about how the GM can utilize the **Row System** to *Combat_Rules.md*.
- Added more details to *__Turns and Rounds__* in *Combat_Rules.md*.
- Added forced movement from the **Back Row** to the **Front Row** if every actively fighting character is sitting in the **Back Row** at the start of the **Round** in *Combat_Rules.md*.
  - This doesn't apply to **Surrounded** groups.
- Added *Reposition* **Basic Ability** in *Combat_Rules.md*.
- Added a **Character Ranks Experience Multiplier** table to *Combat_Rules.md*.
### Changes
- Changed *Unarmed Strike* **Basic Ability** in *Combat_Rules.md*.
  - Deals 1d2 Bludgeoning damage on Success, otherwise it deals 1 Bludgeoning damage.
  - Renamed it from *Unarmed Strike* to *Attack*.
- Reworked how **Gear Slots** are calculated and utilzed.
  - Characters now have a number of **Gear Slot Tags** with *Counts* determining how many pieces can be equipped of that **Gear Slot** category.
- Renamed the following **Effects** in *Creating_Abilities.md*.
  - Is Illusory -> Is Illusion
  - Has Success Range -> Has Failure Range
- Reworked Damage **Resource** and Recover **Resource** so that they can accept flat values.
- Some **Effects** now actively mention that they can be taken repeatedly.
- Reduced initial maximum **<i class="fa-solid fa-gem"></i>Action Points** from 3 to 2.
- Changed the Ice **Element Tag** to Cold in *Creating_Abilities.md*.
- Changed Negative **Ability Point Cost** point gain maximum from current **Level** x 2 to just current **Level** in *Creating_Abilities.md*.
- Changed how *__<a style="color:#40ff40"><i class="fa-solid fa-bolt"></i>Energy</a>__* is actively reduced when attempting to stabilize while either unconscious or dying.
- Changed how big **Titanic** and **Astronomic** characters are.
- Renamed the *Run Away* **Basic Ability** to *Escape* in *Combat_Rules.md*.
### Removals
- Removed the following **Element Tags** from *Creating_Abilties.md*.
  - Water
  - Poison
  - Void
- Removed permanent **Duration** at 20 **Rounds** of **Duration**.

## October 3, 2026
### Additions
- Added *Combat_Rules.md*.
  - It's a work-in-progress.
- Added **Effects**, **Element Tags** and **Elemental Effectiveness** to *Creating_Abilities.md*.
### Changes
- Reformated the entire SRD to utilize [MdBook](https://rust-lang.github.io/mdBook/) instead.
  - This was an extensive undertaking, so there will be a lot of undocumented changes in this update.
- Changed **Evasion's** value range.
- Added *FontAwesome* icons to various **Resources**.
- Colored **Base Stats** and their **Resources**.

## October 2, 2026
### Additions
- Added *Effects* to *__Ability Properties__* in *Creating_Abilities.md*.
- Added *__Buying Abilities__* to *Creating_Abilities.md*.
  - It's currently unfinished.
### Changes
- Changed how many **Ability Points** you get in *Character_Creation.md*.
  - Also included an example of how the scaling works.
- Renamed **Heft Power** to **Heft** in *Character_Creation.md*. It does the same thing.
- Renamed *__Actions and Action Points__* to *__Abilities and Action Points__* in *Core_Rules.md*. They were the same thing.
- Added some text to the **Ability Points** section found in *Character_Creation.md* mentioning the ability to add or change your **Abilities**.
- Moved the "Attention" box found under *__Experience and Leveling Up__* related the the campaign's *Level* range in *Character_Creation.md*.

## August 8, 2026
### Additions
- Added *__Creating Abilities__* to *Creating_Abilities.md*.
- Added *__Ability Properties__* to *Creating_Abilities.md*.
### Changes
- Applied typo and phrasing fixes to both *Core_Rules.md* and *Character_Creation.md*
- Adjusted **Abilities** phrasing under *__Major Properties__* in *Character_Creation.md*.

## August 7, 2026
### Additions
- Fleshed out *__Major Properties__* in *Character_Creation.md*.
  - Added *Astronomic* **Size** variant.
  - Added **Heft Power** section. Each **Size** now has a **Heft Power** multiplier.
  - Added **Aptitudes** section.
  - Added **Gear** section.
  - Added **Abilities** section.
- Added *__Experience and Leveling Up__* to *Character_Creation.md*.
- Created *Creating_Abilities.md* and *Creating_Gear.md*.
### Changes
- *Gargantuant* and *Titanic* **Sizes** now have **Level** restrictions.
- **Evasion** cleaned up a bit as it was mentioned in **Size** variants.
- Cleaned up *Core_Rules.md* and made it look a bit better.

## August 6, 2026
### Additions
- Created *Character_Creation.md*.
- Added *__Base Stats__* to *Character_Creation.md*.
- Added *__Major Properties__* to *Character_Creation.md*.
### Changes
- Minor phrasing change for how **Energy** works when hitting the negative maximum.

## August 5, 2026
### Additions
- Added *__The Main Three Stats__* to *Core_Rules.md*.
- Added *__Health, Stamina, and Energy__* to *Core_Rules.md*.
- Added *__Aptitudes__* to *Core_Rules.md*.
- Added *__Contested d% Checks__* to *Core_Rules.md*.
- Added *__Actions and Action Points__* to *Core_Rules.md*.
- Added *__Defense__* to *Core_Rules.md*.
- Added *__Evasion__* to *Core_Rules.md*.

## August 4, 2026
### Additions
- Added *__Aptitudes__* to *Introduction.md*.
- Added URL linking to the front page of the SRD in the About section displayed on the Github source page.
- Created *Core_Rules.md*.
### Changes
- Cleaned up **d% Checks** description.
- Made **Defense** and **Evasion** descriptions more vague.
- Changed the URL found within *CNAME*.
- Prettied up *Changelog.md*.
- Updated description of *README.md*.
- Renamed the three major Stats the system uses.
  - **Body** -> **Physique**
  - **Mind** -> **Ego**
  - **Soul** -> **Instinct**
### Removals
- Removed a couple of sections found under **Clear Expectations** in *Introduction.md*.

## August 3, 2026
### Additions
- Created the repository via Github Pages.
- Cleaned up some of the template tutorial files.
- Added *Introduction.md* page.
### Changes
- Changed the template's fonts to *Jersey 10* and *Jersey 20* from Google Fonts.
