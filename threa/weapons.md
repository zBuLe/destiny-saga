---
title: Weapons of Threa
---
# Weapons

## Properties

### Build

**Type:** The fundamental weapon class. A Type defines the cultural origin of the weapon, its core handling philosophy, and its default interaction patterns. Each Type is the Weapon of Choice of a specific people and establishes baseline expectations for form, use, and combat role.

**Variant:** A specific archetypal configuration of a weapon Type. Variants represent design intent rather than craftsmanship quality, indicating how the weapon is meant to be used (speed, reach, power, prestige, etc.). Variants determine available components, stat tendencies, and inherent effects. Each Variant can be described by one or more archetypes.

| Tag | Archetype    | Description                                                                                                                                                     |
|:---:|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ⭐  | **Base**     | The fundamental archetype of a weapon Type. Represents the intended baseline form. All other variants are deviations from the Base.                             |
| 🔹  | **Simple**   | Designed for ease of manufacture and mass production. Simple variants use fewer components, lower material cost, and reduced complexity.                        |
| ✨  | **Enhanced** | An improvement over the Base variant. Enhanced variants exhibit superior balance, materials, or construction, resulting in broadly improved performance.        |
| 🌟  | **Prestige** | High-performance and complex, this variant maxes multiple stats and often adds powerful effects. Only skilled crafters can pull it off                          |
| 🎭  | **False**    | An attempted Prestige variant crafted by an insufficiently skilled smith. Appears complex but lacks true refinement—often unstable, inefficient, or incomplete. |
| 📏  | **Reach**    | Optimized for striking at greater distance than the Base variant. Typically trades speed, maneuverability, or close-quarters control for extended reach.        |
| ⚡  | **Speed**    | Optimized for rapid handling and quick techniques. Speed variants often sacrifice raw power, reach, or defense to enable faster attacks and recovery.           |
| 🪨  | **Heavy**    | Built for mass and impact. Heavy variants emphasize blunt force, momentum, and single powerful strikes. Often slower, with higher durability and defense.       |
| 👐  | **Dual**     | Designed to be wielded alongside another weapon of the same or compatible Type. Grants additional effects or bonuses when dual-wielded.                         |
| ✂️  | **Slash**    | Focused on slash damage. These variants enhance cutting effectiveness and often improve bleed-related interactions at the cost of pierce or blunt capability.   |
| 📌  | **Pierce**   | Focused on pierce damage. These variants emphasize thrusting, penetration, and armor defeat, often at the expense of slash breadth or blunt force.              |
| 🔨  | **Blunt**    | Focused on blunt damage. These variants concentrate mass and force to disrupt balance, armor, or posture, frequently sacrificing speed or edge effectiveness.   |
| 🎯  | **Range**    | Optimized for throwing or projection. Improves effective range, accuracy, or thrown effects. Not available to weapon Types not intended to be thrown.           |

**Typical progression:** Base → Enhanced → Prestige. Simple is a cost-reduced branch. False marks an attempted Prestige variant that failed due to insufficient skill. Focus archetypes (Reach/Speed/Heavy/etc.) emphasize one property, usually at the expense of others.

**Components:** The physical parts that make up the weapon. Each component may have multiple options and material choices. Components determine stat ranges, enable or restrict variants, introduce optional effects, and influence crafting cost, durability, and inventory properties. Some components are functional; others are decorative.

### Rating System

A 5-star visual system with 9 tiers, mapped to an internal 0–255 point scale. Used for all rated properties (stats).

| Rating    | Points (0–255) | Label       | Stars   |
|-----------|----------------|-------------|---------|
| None      | 0              | No Stars    | [☆☆☆☆☆] |
| Weak      | 1–33           | Dull Star   | [✦☆☆☆☆] |
| Low       | 34–68          | One Star    | [★☆☆☆☆] |
| Fair      | 69–105         | Two Stars   | [★★☆☆☆] |
| Good      | 106–144        | Three Stars | [★★★☆☆] |
| Great     | 145–181        | Four Stars  | [★★★★☆] |
| High      | 182–216        | Five Stars  | [★★★★★] |
| Excellent | 217–249        | Shine Star  | [★★★★✷] |
| Epic      | 250–255        | All Shines  | [✷✷✷✷✷] |

☆ = Empty star  
✦ = Dull star  
★ = Full star  
✷ = Shine star  

Example: “The sharpness of this blade is great.” Here, *sharpness* refers to **Slash**, and the weapon’s Slash rating falls between **145 and 181**.

### Damage Profile

**Slash:** Damage inflicted by sharp edges through cutting or slicing motions. Slash is most effective against exposed targets and flexible materials. Successful slash strikes may inflict **Bleed**, reducing the target’s attack capability over time. This property is rated.

**Pierce:** Damage inflicted by hard points or narrow edges through thrusting or puncturing motions. Pierce excels at penetrating armor and dense materials. Successful pierce strikes may inflict **Breach**, reducing the target’s defensive capability. This property is rated.

**Blunt:** Damage inflicted by solid mass through impact. Blunt transfers force through armor and disrupts balance. Successful blunt strikes may inflict **Daze**, reducing the target’s agility and reaction speed. This property is rated.

### Performance Profile

**Reach:** The effective distance at which the weapon can strike a target in melee. Reach determines engagement spacing, initiative interactions, and which opponents can be threatened without repositioning. This property is rated.

**Range:** The effective distance a weapon can travel when thrown or projected. Range is only listed for weapon Types or Variants intended to be thrown; if omitted, it defaults to **Low**. This property is rated.

**Speed:** How quickly the weapon can be wielded, affecting attack execution, recovery, and technique timing. Speed influences how often a wielder can act and how easily they can adapt during combat. This property is rated.

**Defense:** The weapon’s ability to absorb or deflect incoming attacks when used for blocking or parrying. Defense determines how much force the weapon can mitigate and influences breakage and shatter outcomes. This property is rated.

**Wield:** Indicates how the weapon is handled: **1H** (one-handed) or **2H** (two-handed). Wield affects available techniques, mobility, dual-wield eligibility, and interaction with anatomy-specific rules.

### Craft

**Durability:** The weapon’s structural endurance—effectively its hit points. Durability is primarily determined by materials and component construction. Higher durability allows the weapon to withstand more use and damage before failure. Maintenance lowers the rate of wear. Durability can be restored by repairing the weapon.

**Condition:** The current state of the weapon, expressed as a percentage of its durability. Condition directly modifies weapon performance:

| Condition | Range   | Effect       |
|-----------|---------|--------------|
| Pristine  | 100%    | +5%          |
| Good      | 50–99%  | Normal stats |
| Worn      | 25–49%  | −10%         |
| Damaged   | 1–24%   | −25%         |
| Broken    | 0%      | Unusable     |

Once durability falls **below 0**, the weapon is destroyed. A destroyed weapon can either be **broken** or **shattered**. A broken weapon cannot be used until repaired. A shattered weapon is lost and unusable.

**Quality:** The craftsmanship tier of the weapon, determined by the skill level of the smith who crafted it. Quality modifies the final stat values:

| Quality  | Tier |
|----------|------|
| Shoddy   | −3   |
| Crude    | −2   |
| Rough    | −1   |
| Basic    | 0    |
| Refined  | 1    |
| Superior | 2    |
| Master   | 3    |
| Mythic   | 4    |

**Effects:** A list of inherent effects tied directly to the weapon or variant. These effects apply whenever the weapon is wielded and are independent of techniques, materials, or external modifiers. Effects may be unconditional or require specific triggers (e.g., charge, parry, throw).

| Format                     | Example                 | Meaning                                                      |
|----------------------------|-------------------------|--------------------------------------------------------------|
| effect;                    | Splash;                 | Applies while the source is equipped.                        |
| trigger: effect;           | Parry: Stagger;         | Applies when the trigger condition occurs.                   |
| trigger: effect, effect;   | Dual: Speed+, Defense+; | Multiple effects apply from the same trigger.                |
| effect                     | Bleed                   | Applies when its conditions are met; bypasses chance checks. |
| effect+; effect-; effect++ | Daze+;                  | Effect magnitude is modified.                                |
| effect%+; effect%--        | Breach%-;               | Effect chance is modified.                                   |

### Inventory

**Volume:** The physical space the item occupies in inventory. Volume determines whether an item can be carried at all, based on inventory capacity. Items exceeding available volume cannot be added unless mitigated by special containers or sheaths.

**Weight:** The mass of the item, primarily determined by materials and construction. Weight contributes to total carry weight and affects mobility. Exceeding carry thresholds results in penalties ranging from reduced speed to complete immobility.

---

## Razor

Type: **Razor — Weapon of Choice of the Lor**

Description: The Razor is a three-edged razorplate. The handle is embedded along the inner edge near one point. The edge sharing this point is the outer edge. The remaining edge is the top edge. The outer and top edges are sharpened; the inner edge may be left dull.

|  Tag   | Variant  | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects                                              |
| :----: | -------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | ---------------------------------------------------- |
|   ⭐   | Base     | Good  | Fair   | None  | Fair  | Fair  | Good    | 1H    |                                                      |
|   🔹   | Straight | Fair  | Low    | Low   | Fair  | Fair  | Fair    | 1H    |                                                      |
|   ✨   | Saber    | Good  | Good   | None  | Fair  | Good  | Good    | 1H    | Parry: Stagger;                                      |
|  ⚡📌  | Rapier   | Fair  | Good   | None  | Good  | Good  | Low     | 1H    | Breach Rate+; Charged Pierce: Breach+;               |
|  🔨🪨  | Claymore | Good  | Weak   | Fair  | Fair  | Low   | Great   | 2H    | Charged: Slash+;                                     |
| 🔹👐⚡ | Dagger   | Fair  | Fair   | None  | Low   | Great | Low     | 1H    | Dual: Speed+; Concealable;                           |
|  🌟👐  | Honor    | Great | Good   | None  | Good  | Good  | Good    | 1H    | Dual: Speed+, Defense+; Charged Dual: Bleed; Bleed+; |

**Components:*- Razorplate, Handle, [Tassel], [Edge Etching]

Component descriptions

- Razorplate: A solid plate forming the Razor’s edges. Curvature, bevel, and which edges are sharpened determine its handling emphasis.
- Handle: A solid piece wrapped in fabric, attached along the inner edge for handling and comfort.
- [Tassel] (Optional): Decorative strings attached to the base of the handle.
- [Edge Etching] (Optional): The inner edge can be etched as ornamentation.

Variant Descriptions

- Base: The inner and outer edges curve away from the wielder; the top edge curves inward. The outer edge is the longest edge.
- Straight: Cheap to build. Eliminates the top edge; the inner edge is straight. Due to low production quality, the razorplate stays thick, increasing mass. Mass-fielded to armies.
- Saber: Enhanced variant. Inner and outer edges curve in parallel and match in length; the top edge is short and gently curved.
- Rapier: Fast, with a focus on piercing. The top edge is collapsed. The outer edge runs straight, curves near the handle, then straightens to meet the inner edge, forming a point.
- Claymore: Heavy, with a focus on blunt performance and guarded handling. Inner and outer edges curve inward with the same gentle arc and length, flaring at the end; the handle on the inner edge is longer. The top edge curves outward, concentrating mass toward the top; edges may use a wider bevel for added mass.
- Dagger: Cheap, fast, and suitable for dual wielding. Much shorter razorplate. No top edge; inner edge is straight; outer edge curves back into the inner edge. The handle covers roughly half the inner edge due to smaller size. Common among peasants as both tool and weapon.
- Honor: A prestigious dual-wieldable Razor carried by those trusted by the King. The outer edge has a pronounced outward curve; the top edge curves deeply inward, creating sharp points. A fourth edge is added, splitting the bottom point in two. Tassels add flair; edge ornamentation tells the wielder’s story. Often seen among important officers and nobles.

Additional Notes

- Concealable: Can be quickly equipped without a weapon sheath, fitting into pockets, beneath a belt, or other discreet locations.

---

## Boomerang

Type: **Boomerang — Weapon of Choice of the Aria**

Description: The boomerang is a curved airfoil designed to return when thrown.

|  Tag   | Variant | Slash | Pierce | Blunt | Reach | Range | Speed | Defense | Wield | Effects                                                      |
| :----: | ------- | ----- | ------ | ----- | ----- | ----- | ----- | ------- | ----- | ------------------------------------------------------------ |
|   ⭐   | Base    | Good  | Fair   | None  | Low   | Good  | Good  | Fair    | 1H    |                                                              |
|   🔹   | Stick   | None  | None   | Good  | Low   | Fair  | Fair  | Fair    | 1H    |                                                              |
| ✨👐🎯 | Winged  | Fair  | Fair   | Fair  | Low   | High  | High  | Fair    | 1H    | dual: slash+;                                                |
|   ✂️   | Ring    | Great | None   | Low   | Low   | Great | Good  | Fair    | 1H    | slash: bleed%+;                                              |
|   🔨   | Disc    | Great | None   | Great | Low   | Great | Good  | Good    | 1H    | block: stagger;                                              |
|   📌   | Cross   | Fair  | Great  | None  | Low   | Great | Good  | Fair    | 1H    | critical%+;                                                  |
|   🪨   | Thunder | Great | Fair   | Great | Good  | Low   | Low   | Great   | 2H    | charge: unblockable, splash; throw: stagger;                 |
|  ⚡👐  | Zephyr  | Fair  | None   | None  | Weak  | High  | High  | Weak    | 1H    | dual: speed+; first: stagger; throw: stagger%+; concealable; |
|   🌟   | Silence | High  | Great  | Good  | Low   | High  | High  | Good    | 1H    | stealth: unblockable, undetectable, critical, critical+;     |

Components: Elbow, Airfoil, [Jewel]

Component descriptions

- Elbow: The bend point that defines the boomerang’s geometry and stabilizes its flight.
- Airfoil: The shaped body that generates lift and controls return behavior.
- [Jewel] (Optional): Decorative inlay set into the body.

Variant Descriptions

- Base: A V-shaped airfoil with a sharp edge.
- Stick: Cheap to make and more common; a slightly bent airfoil with no sharp edge.
- Winged: Enhanced, dual-wieldable. A W-shaped airfoil that offers longer range.
- Ring: A circular, slash-focused variant, sometimes with an optional bar for a handle. Lacking points, it does not deal pierce damage.
- Disc: A solid circle whose additional mass enables blunt damage. Like Ring, it has no pierce damage.
- Cross: Features four points, providing improved piercing capability.
- Thunder: Heavy, large airfoil that doesn’t travel as far but excels in close combat.
- Zephyr: Speed-focused. Two elbows form a Z-shaped airfoil; intended to pummel and restrict movement.
- Silence: Prestigious. Two elbows form an S-shaped airfoil; silent in flight, difficult to detect until impact.

Additional Notes

- return: When thrown, the weapon returns to its wielder.
- unblockable: Forces the opponent out of a defensive stance before the hit is resolved.
- undetectable: Does not cause alert (even if seen) until it hits.
- stealth: User is in a stealth state (crawling, sneaking, hidden, not yet detected).
- first: First successful strike triggers the listed effect.
- concealable: Can be equipped without a weapon sheath (fits discreet carry locations).

---

## Rifle

Type: **Rifle — Weapon of Choice of the Dis Com**

Description: The rifle is a melee weapon that balances all three damage types. It is made of two major parts: the carriage and the blade. The carriage consists of the guard, grip, and buttstock. The buttstock provides the primary blunt surface, the grip supports maneuvering, and the guard provides defensive capability. The blade is embedded in the guard; it has a long edge for reliable slash damage and ends in a sturdy point for pierce damage.

|  Tag   | Variant  | Slash | Pierce | Blunt     | Reach | Speed | Defense | Wield | Effects                                                                             |
| :----: | -------- | ----- | ------ | --------- | ----- | ----- | ------- | ----- | ----------------------------------------------------------------------------------- |
|   ⭐   | Base     | Good  | Good   | Good      | Good  | Good  | Good    | 2H    |                                                                                     |
| 👐🔹⚡ | Pistol   | Fair  | Fair   | Low       | Low   | Great | Low     | 1H    | dual: speed+;                                                                       |
| 👐✂️⚡ | Carbine  | Great | Fair   | Low       | Fair  | High  | Fair    | 1H    | bleed+; dual: bleed%+;                                                              |
|  🔨👐  | Shotgun  | Fair  | Fair   | High      | Good  | Fair  | Great   | 1H    | stagger+; daze+; dual: stagger%+;                                                   |
|  🌟📌  | Sniper   | Good  | High   | Good      | High  | Good  | Great   | 2H    | critical%+; critical+; breach+;                                                     |
| 🌟🪨🔨 | Launcher | Fair  | Fair   | Excellent | Good  | Low   | High    | 2H    | strike: splash; splash+; splash: unblockable;                                       |
|   🌟   | Assault  | High  | High   | High      | Good  | Good  | Great   | 2H    | breach%+; daze%+; bleed%+; stealth: critical+; block: stagger%+; parry: speedburst; |

Components: Carriage (Guard, Grip, Buttstock), Blade, [Sling], [Tag]

Component descriptions

- Carriage: A composite frame that provides structural integrity.

  - Guard: A strong component that absorbs strikes and provides a blunt surface. The blade is embedded in the guard.
  - Grip: Where the wielder controls maneuvering. The guard connects to the front side of the grip; it also supports the blade.
  - Buttstock: Rear mass for stability and the primary blunt striking surface, connected to the rear of the grip.
- Blade: Embedded in the guard and supported by the grip. Long sharp edge with a sturdy point; primary attack surface.
- [Sling] (Optional): Strap attached to the carriage. Acts as its own sheath: enables quick-equip and negates volume in inventory.
- [Tag] (Optional): Identification marker for inventory, ownership, informational, or decorative purposes.

Variant Descriptions

- Base: Standard design with a blade that curves to a point. Balanced in all aspects.
- Pistol: Simple to produce, fast to use, and dual-wieldable. Essentially just the grip with a minimal guard, no buttstock, and a short blade. Commonly used as a sidearm.
- Carbine: Slash- and speed-focused. Shorter than the base rifle, sacrificing reach for faster strikes.
- Shotgun: Blunt-focused. Thicker, heavier carriage with a short guard; the blade is mostly embedded in the guard. Can be dual-wielded to gain extra stagger emphasis on blunt strikes.
- Sniper: Prestigious, pierce-focused. Longer, sturdier guard supports an extended, sharply curved blade with a fine tip.
- Launcher: Prestigious heavy weapon. Extremely heavy buttstock and guard. Thick blade adds mass with only a small edge exposed. Preferred by Juggernauts.
- Assault: Pinnacle of the Dis Com armory. Prestigious close-quarters weapon. All damage types have increased infliction chances on their status effects, plus situational awareness bonuses.

Additional Notes

- The blade can be detached from the carriage for maintenance and customization.

---

## Spear

Type: **Spear — Weapon of Choice of the Ma Hir**

Description: The spear is a weapon that excels at pierce damage. It is basically a point on a stick. Simple, elegant, rude.

|  Tag   | Variant | Slash | Pierce | Blunt | Reach | Range | Speed | Defense | Wield | Effects                                                           |
| :----: | ------- | ----- | ------ | ----- | ----- | ----- | ----- | ------- | ----- | ----------------------------------------------------------------- |
|   ⭐   | Base    | Fair  | Good   | Fair  | Great | Good  | Good  | Good    | 2H    | —                                                                 |
| 🔹👐⚡ | Short   | Low   | Fair   | Low   | Fair  | Fair  | Great | Low     | 1H    | dual: critical%+;                                                 |
|  ✨📏  | Long    | Fair  | Great  | Fair  | High  | Good  | Fair  | Good    | 2H    | critical%+;                                                       |
|  🪨🔨  | Heavy   | Weak  | Fair   | Great | Good  | Fair  | Low   | Great   | 2H    | charge: splash; breach%+;                                         |
|   ✂️   | Glaive  | Great | Good   | Fair  | Great | Weak  | Fair  | Good    | 2H    | charge: bleed;                                                    |
|  🎯📌  | Harpoon | Fair  | Good   | Weak  | Great | High  | Good  | Fair    | 1H    | recall; throw: breach;                                            |
| 🌟✂️📌 | Halberd | Great | High   | Good  | Great | Low   | Good  | Great   | 2H    | pierce+; critical+; breach+; bleed+; charge: splash, unblockable; |

Components: Tip, Shaft, Grip, Butt, [Flag], [Split], [Bottom Tip], [Tether]

Component descriptions

- Tip: The spear’s primary attack surface. Options commonly used on Base, Short, Long, Heavy, and as a second tip:

  - Standard: breach;
  - Bident: defense+;
  - Trident: speed+;
  - Crescent: slash+; bleed+;
- Shaft: The main length and leverage of the spear. Variant-gated by design (Short uses a short shaft; Long uses a long shaft; Heavy uses a thicker/heavier shaft).
- Grip: Wrapping and balance point for control and comfort.
- Butt: Rear end used for balance and blunt strikes (and as a mounting point for some options).
- [Flag] (Optional): Decorative/identity marker mounted to the shaft.
- [Split] (Optional): Split shaft mechanism that allows the shaft to separate and recombine.
- [Bottom Tip] (Optional): Replaces the butt with a second tip; many butt/bash actions become pierce or slash depending on the tip.
- [Tether] (Optional): A cord for retrieval/control (core to Harpoon builds). If added to anything besides a Harpoon, it imposes a speed- penalty.

Variant Descriptions

- Base: Just a spear tip fitted on a shaft. Classic “stab first, ask later.”
- Short: Easy to produce, fast to use, and dual-wieldable. A tip on a shorter shaft.
- Long: Enhanced with a focus on reach. A tip on a longer shaft.
- Heavy: Heavier build—thicker shaft and heavy tip—meant to carry momentum with each thrust.
- Glaive: Slash-focused; the tip becomes a blade.
- Harpoon: Built for superior throwing. Short shaft with a long, barbed, hooked tip, plus a tether to reel in what it hits.
- Halberd: Prestigious. The head has multiple points and edges, causing damage with every swing.

Additional Notes

- If the spear is split and there is **no*- second tip, the second weapon is effectively a **Quarter Bo Staff**.
- Range is shown here because Spears are meant to be thrown as a weapon family (with Harpoon specializing into it).

---

## Blade

Type: **Blade — Weapon of Choice of the Duga**

Description: The Blade excels in slash and speed. It is a leaf-shaped plate affixed to a handle. The long edges of the plate are sharpened and meet in a point. It serves both as a weapon and a tool for the Duga.

|  Tag   | Variant   | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects                           |
| :----: | --------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | --------------------------------- |
|   ⭐   | Base      | Good  | Fair   | Low   | Fair  | Great | Fair    | 1H    |                                   |
|   🔹   | Field     | Fair  | Low    | Low   | Fair  | Good  | Fair    | 1H    |                                   |
|  🔹🔨  | Shovel    | Fair  | Low    | Good  | Fair  | Good  | Good    | 2H    | charge: daze; charge: stagger;    |
| 🔹⚡👐 | Cutter    | Fair  | Good   | Low   | Low   | High  | Low     | 1H    | dual: speed+;                     |
|  🔨🪨  | Cleaver   | Great | None   | Great | Good  | Good  | Good    | 2H    | charge: unblockable;              |
|  ✂️⚡  | Slicer    | High  | Great  | Fair  | Great | High  | Fair    | 2H    | charge: bleed;                    |
|  🪨🔨  | Anchor    | Great | Good   | High  | Good  | Low   | High    | 2H    | block: stagger; parry: knockdown; |
|   ✨   | Sharp     | Great | Good   | Low   | Fair  | High  | Fair    | 1H    | dual: slash+; dual: defense+;     |
|   🎭   | Lost      | Fair  | Low    | Low   | Good  | Fair  | Low     | 1H    | lost memories;                    |
|   🌟   | Forgotten | High  | Great  | Great | Good  | High  | Great   | 1H    | forgotten memories;               |

Components: Plate, Handle, Rivets, [Joint], [Spine Engraving]

Component descriptions

- Plate: The primary blade surface. Shape and thickness determine damage bias (thin for speed and slash, thick for blunt force).
- Handle: Grip and balance point; determines wield and leverage.
- Rivets: Bind plate to handle; quality affects durability and stability.
- [Joint] (Optional): Enables two blades to be joined at the handles, forming a double blade. Dual effects still apply while joined.
- [Spine Engraving] (Optional): Decorative or mnemonic markings along the spine.

Variant Descriptions

- Base: Just a plate and a handle. All-around fast slashing tool.
- Field: Inexpensive rectangular plate with one sharp edge. Commonly used to clear foliage.
- Shovel: Smaller plate on a longer handle, just sharp enough to pierce dirt. Trades finesse for utility.
- Cutter: Small, cheap, fast, and dual-wieldable. A kitchen tool turned weapon.
- Cleaver: Blunt-focused rectangular plate with one sharp edge. Built for mass and impact.
- Slicer: Enhanced, slash- and speed-focused. Long, curved plate inspired by refined cutting forms.
- Anchor: Heavy triangular plate with the handle affixed inside it. Can be driven into the ground to deny movement.
- Sharp: Enhanced base form—cleaner, sharper, faster.
- Lost: A **False Forgotten**. The first blade a Duga forges alone. Weak on its own, but serves as a mnemonic anchor.
- Forgotten: Prestigious. A flurry of slashes, refined and formidable—yet incomplete without its counterpart.

Additional Notes

- **Lost Memories:*- When dual-wielded with a Forgotten Blade, the Lost Blade gains the performance of the prestige it failed to become.
- **Forgotten Memories:*- When dual-wielded with a Lost Blade, the Forgotten Blade gains enhanced effects; when joined via Joint, it unlocks unique effects.
- Subsequent unskilled attempts to craft a Forgotten Blade result in standard False variants, not Lost Blades.

---

## Bo Staff

Type: **Bo Staff — Weapon of Choice of the Frill**

Description: The Bo Staff is a long, thin stick. Simple in form, demanding in discipline, it emphasizes control, timing, and positional dominance over raw lethality.

|  Tag   | Variant | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects                                                                           |
| :----: | ------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | --------------------------------------------------------------------------------- |
|   ⭐   | Base    | None  | None   | Good  | Great | Good  | Good    | 2H    | —                                                                                 |
|   🔹   | Quarter | None  | None   | Good  | Good  | Great | Fair    | 2H    | —                                                                                 |
| 🔹👐⚡ | Baton   | None  | None   | Good  | Low   | High  | Fair    | 1H    | dual: stun; parry: stagger;                                                       |
|  ✨📏  | Long    | None  | None   | Great | High  | Great | Good    | 2H    | block: stagger;                                                                   |
|   📌   | Pointed | None  | Good   | Great | Great | Great | Good    | 2H    | breach+; critical+;                                                               |
|  🪨🔨  | Pillar  | None  | None   | High  | Great | Fair  | High    | 2H    | block: stagger; parry: knockdown; charge: unblockable;                            |
|  🌟⚡  | Flex    | None  | None   | High  | Great | High  | High    | 2H    | strike: doublehit; block: stagger; breach+;                                       |
|  🌟🪨  | Cane    | None  | None   | Great | Fair  | Great | Great   | 1H    | resist knockback; resist knockdown; stun+; recovery+; critical+; block: defense+; |
|  🌟🪨  | Kane    | None  | None   | Great | Fair  | Great | Great   | 1H    | resist knockback; resist knockdown; stun+; recovery+; critical+; block: defense+; |
|  🌟📌  | Spike   | Good  | Great  | Fair  | Fair  | Great | Great   | 1H    | breach+; bleed+;                                                                  |

Components: Shaft, Grip, Caps, [Handle], [Engravings], [Jewel], [Bottom Cap]

Component descriptions

- Shaft: The primary body of the staff. Length, thickness, and flexibility define reach, speed, and blunt emphasis.
- Grip: Control surface for handling and recovery.
- Caps: Terminal fittings that modify impact behavior.
- [Handle] (Optional): Reinforced grip section; adds resist knockback. Integrated by default in Cane, Kane, and Spike.
- [Engravings] (Optional): Decorative or mnemonic markings.
- [Jewel] (Optional): Decorative inlay.
- [Bottom Cap] (Optional): Alternative cap used on one end; required for Pointed variants.

Variant Descriptions

- Base: A shaft slightly taller than its wielder. Balanced control staff.
- Quarter: Inexpensive and practical. Shaft shortened to shoulder height.
- Baton: Short, fast, dual-wieldable staff. Forearm length.
- Long: Reach-focused staff roughly half a wielder’s height taller than Base.
- Pointed: One end sharpened to allow piercing strikes.
- Pillar: Thick, heavy staff with commanding presence.
- Flex: Prestigious. Flexible shaft rebounds strikes, enabling follow-up hits.
- Cane: Prestigious, elegant staff designed for authority and resilience.
- Kane: Prestigious deceptive staff. Appears identical to a Cane—until it twists.
- Spike: A stiletto concealed within the Kane; revealed by unsheathing.

Additional Notes

- Kane and Spike are crafted together and are dual-wielded when unsheathed (no dual bonus).
- Kane’s shaft is hollow; Spike is attached to the handle.
- Unsheathing the Spike reduces Blunt damage (loss of mass).
- DoubleHit triggers a second strike at half power; it can be blocked if timed.
- Handle may be added to Base, Quarter, Long, Pointed, and Flex; it is integral to Cane and Kane.
- Pointed uses only a bottom cap.

Caps

- Standard: durability+;
- Rough: critical%+;
- Weighted: stun+; blunt+; speed-;
- Pointed: breach%+;
- Traction: resist knockdown; recovery+;
- Hooked: bleed%+;

---

## Scythe

Type: **Scythe — Weapon of Choice of the Mort**

Description: The scythe consists of a long, curved blade attached at a sharp angle to a two-handed shaft (snath). The blade is sharpened along the inner edge, favoring hooking cuts, pulls, and controlled dismemberment.

|  Tag   | Variant  | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects                                                            |
| :----: | -------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | ------------------------------------------------------------------ |
|   ⭐   | Base     | Great | Fair   | Fair  | Good  | Fair  | Fair    | 2H    | grab: reach+;                                                      |
|   🔹   | Sickle   | Good  | Low    | Low   | Low   | Great | Low     | 1H    | bleed+; grab: breach;                                              |
| 🔹👐⚡ | Acute    | Good  | Fair   | Low   | Low   | Great | Fair    | 1H    | dual: bleed;                                                       |
|  ✨📌  | Straight | Great | Great  | Fair  | High  | Good  | Good    | 2H    | breach+;                                                           |
|   🪨   | Crescent | Good  | Fair   | High  | Great | Weak  | Good    | 2H    | grab: hold+; splash: bleed;                                        |
|   ✂️   | Arc      | High  | Good   | Good  | Great | Low   | Great   | 2H    | grab: reach+; bleed+;                                              |
|  🌟🪨  | Halo     | High  | Low    | High  | Great | Low   | Great   | 2H    | grab: hold+; grab: bleed; grab: unblockable;                       |
|   🌟   | Eclipse  | High  | Good   | Good  | Great | Good  | Great   | 2H    | grab: reach+; grab: hold+; grab: unblockable; grab: bleed; bleed+; |

Components: Blade, Snath, Grip, [Toe]

Component descriptions

- Blade: Curved cutting surface sharpened on the inner edge. Length, curvature, and thickness determine slash focus and hook strength.
- Snath: The shaft that defines leverage and reach. Angle and curvature strongly affect grab behavior.
- Grip: Control point for handling and resistance during pulls.
- [Toe] (Optional): Reinforced lower blade section. Increases durability at the cost of reduced piercing efficiency.

Variant Descriptions

- Base: A long blade mounted to a snath. Balanced hook-and-cut weapon.
- Sickle: Short snath with a sickle-shaped blade. Easy to produce and fast in close quarters.
- Acute: Short snath with a compact blade, suitable for dual wielding.
- Straight: Blade mounted upright to emphasize piercing thrusts.
- Crescent: Two heavy blades and a sturdy snath. The unsharpened side is thick and flat, favoring impact and control.
- Arc: Longer, more pronounced curve enhances cutting arcs and pull control.
- Halo: Prestigious. Features a single oversized crescent blade of immense thickness with a razor inner edge. The snath curves gently to support leverage.
- Eclipse: Prestigious. Bent snath with two blades—one on each end—allowing continuous pressure and control.

Additional Notes

- Grab effects represent hook, pull, trap, and control techniques enabled by blade curvature and snath leverage.
- `grab: reach+` extends the distance at which grab techniques can be initiated.
- `grab: hold+` strengthens or prolongs the grab state once established.
- Unblockable grab forces the target out of defensive stance before grab resolution.

---

## Axe

Type: **Axe — Weapon of Choice of the Lauril**
Description: The Axe is a weapon consisting of a heavy axehead mounted on a short haft, no longer than arm’s length. The axehead is a dense mass with a single sharpened edge, built for decisive, committed strikes and relentless forward motion.

|  Tag   | Variant  | Slash | Pierce | Blunt | Reach | Range | Speed | Defense | Wield | Effects                                                   |
| :----: | -------- | ----- | ------ | ----- | ----- | ----- | ----- | ------- | ----- | --------------------------------------------------------- |
|   ⭐   | Base     | Good  | Weak   | Good  | Low   | Fair  | Great | Low     | 1H    | dash;                                                     |
| 🔹👐⚡ | Timber   | Fair  | Weak   | Fair  | Low   | Fair  | Great | Low     | 1H    | dual: dash; throw: stun;                                  |
|  🪨🔨  | Lumber   | Great | Weak   | Great | Good  | Good  | Fair  | Good    | 2H    | dash strike: unblockable;                                 |
|   📌   | Thorn    | Good  | Good   | None  | Low   | Good  | Great | Low     | 1H    | dash; dual: breach;                                       |
|   ✨   | Songbird | Great | Good   | Great | Fair  | Great | High  | Great   | 1H    | dash; agility+; throw: critical;                          |
|   🌟   | Raptor   | High  | Good   | High  | Fair  | Great | High  | Great   | 1H    | pursue; dash strike: unblockable; dash; speed+; agility+; |

Components: Axehead, Haft, Grip, [Lanyard], [Drop]

Component descriptions

- Axehead: Heavy mass with a single sharpened edge. Shape and thickness define slash-to-blunt balance; spikes may be added to the poll for piercing variants.
- Haft: Short handle providing leverage and control. Length is intentionally limited to preserve close-range commitment.
- Grip: Wrapping and balance point for handling and recovery.
- [Lanyard] (Optional): Cord attached to the haft. Improves thrown control and retrieval.
- [Drop] (Optional): Ornamental marker, commonly used to display tribal membership or personal feats.

Variant Descriptions

- Base: A single axehead affixed to a haft. Fast, aggressive, and decisive.
- Timber: Lighter build with a smaller axehead. Suitable for dual wielding and opportunistic throws.
- Lumber: Heavy, two-handed axe with a reinforced haft and massive head. Designed to break lines through unstoppable forward momentum.
- Thorn: Pierce-focused variant. Spikes are added to the poll of the axehead.
- Songbird: Enhanced form. Perfected balance, sharpened edge, and a spiked poll.
- Raptor: Prestigious. Double axehead design built for relentless pursuit and domination.

Additional Notes

- **Dash:*- A short, fast, direction-locked movement. Weapons may be used during Dash, but direction cannot be altered until completion.
- When a weapon is thrown, Dash propels the wielder toward the weapon’s location.
- **Pursue:*- Enables chaining Dash toward a retreating or repositioning target.

Lanyards

- Simple Lanyard: range+;
- Braided Lanyard (Prestigious): range+; strike: doublehit;

---

## Pickhammer

Type: **Pickhammer — Weapon of Choice of the Zeur**

Description: The Pickhammer consists of a sack filled with heavy bulk material. One end is flat, the other tapers to a point. A harness is attached for carrying and wielding. Designed for earthworks, it delivers overwhelming impact at the cost of durability.

|  Tag   | Variant | Slash | Pierce | Blunt     | Reach | Speed | Defense | Wield | Effects                                                                                     |
| :----: | ------- | ----- | ------ | --------- | ----- | ----- | ------- | ----- | ------------------------------------------------------------------------------------------- |
|   ⭐   | Base    | None  | Weak   | Great     | Low   | Low   | Great   | 2H    | heavy: splash;                                                                              |
|   🔹   | Slaker  | None  | None   | Good      | Low   | Fair  | Fair    | 2H    | shatter: splash;                                                                            |
|   📌   | Puncher | None  | Good   | Great     | Low   | Low   | Great   | 2H    | heavy: splash; breach+;                                                                     |
|   🪨   | Slammer | None  | High   | High      | Great | Fair  | Fair    | 2H    | heavy: splash; stagger+;                                                                    |
|   🪨   | Thumper | None  | Fair   | High      | Fair  | Low   | Great   | 2H    | strike: splash; heavy: knockback; charge: breach;                                           |
|  🌟🪨  | Breaker | None  | Great  | Excellent | Good  | Fair  | Great   | 2H    | strike: splash; charge: unblockable, breach; splash: stagger; shatter: splash, unblockable; |

Components: Bulk, Cover, Padding, Tip Cap, Harness, [Filler], [Frame], [Case]

Component descriptions

- Bulk: The primary mass of the weapon. Material choice defines blunt output and durability.
- Cover: Thick fabrics enclosing the bulk; protects structure but degrades quickly.
- Padding: Reinforced fabric on the blunt face; improves impact tolerance.
- Tip Cap: Solid point on the tapered end; enables piercing variants.
- Harness: Used to hold and maneuver the weapon. Acts as a sheath, negates volume, and enables quick equip. Partial detachment alters reach and speed.
- [Filler] (Optional): Loose material (sand, rubble) used instead of or alongside Bulk.
- [Frame] (Optional): Internal structure increasing durability and control.
- [Case] (Optional): Rigid enclosure around the bulk; greatly increases durability.

Variant Descriptions

- Base: Solid bulk wrapped in heavy fabric.
- Slaker: Filled with loose material. Can double as a pack; highly unstable on impact.
- Puncher: Reinforced point for improved penetration.
- Slammer: Harness can be partially detached, allowing extended swings and increased reach.
- Thumper: Internal frame adds strength and durability.
- Breaker: Prestigious. Solid inner case, reinforced frame, and fillable compartment. Designed to fail catastrophically—and take everything nearby with it.

Additional Notes

- Pickhammers have **lower durability*- than most weapons.
- Frame and Case components significantly increase durability.
- Slammer and Breaker Reach/Speed values assume partial harness attachment; fully attached values default to Fair.
- Effects may trigger on **Shatter**, not on Break.
- Male Zeur may dual-wield Pickhammers and other 2H weapons.
- Male Zeur have difficulty wielding 1H weapons.

---

## Whip

Type: **Whip — Weapon of Choice of the Minka**

Description: The whip is a flexible weapon composed of a cord attached to a handle, terminating in a popper. It emphasizes reach, control, and precision, allowing its wielder to strike, ensnare, disarm, and manipulate enemies without committing their own position.

|  Tag   | Variant | Slash | Pierce | Blunt | Reach     | Speed     | Defense | Wield | Effects                                                                             |
| :----: |--- ---- | ----- | ------ | ----- | --------- | --------- | ------- | ----- | ----------------------------------------------------------------------------------- |
|   ⭐   | Base    | Good  | None   | Low   | Great     | Great     | Fair    | 1H    | grab: ensnare;                                                                      |
|   🔹   | Lash    | Fair  | None   | None  | Good      | High      | Low     | 1H    | dual: slash+;                                                                       |
|  📏⚡  | Ribbon  | Fair  | None   | None  | Excellent | Excellent | Weak    | 1H    | grab: reach+; grab+; grab: ensnare;                                                 |
|   🔹   | Belt    | Fair  | None   | Fair  | Good      | Good      | Fair    | 1H    | grab: ensnare; charge: stagger;                                                     |
|   🎯   | Bola    | Fair  | None   | Good  | Fair      | Good      | Fair    | 1H    | grab: ensnare; charge: knockdown;                                                   |
|  🔨🪨  | Chain   | Good  | Fair   | Great | Fair      | Low       | Great   | 1H    | charge: unblockable, knockdown; parry: ensnare;                                     |
|   🌟   | Braided | High  | Good   | Good  | Excellent | High      | Good    | 1H    | grab: reach+; grab+; grab: ensnare; charge: unblockable, knockback; parry: ensnare; |

Components: Handle, Cord, Popper, [Tassel]

Component descriptions

- Handle: Grip and control point. Determines balance and recovery.
- Cord: Flexible striking and control length. Material and construction define reach and speed.
- Popper: Terminal tip used for cutting, cracking, and shock delivery.
- [Tassel] (Optional): Decorative end weight; may subtly alter balance.

Variant Descriptions

- Base: Balanced whip suited for striking and ensnaring.
- Lash: Short, compact cord favored for close-quarters control and dual wielding.
- Ribbon: Long, supple cord designed for entanglement and distance dominance rather than raw damage.
- Belt: Flat, reinforced cord offering balanced speed and stability.
- Bola: Cord tipped with weighted poppers, designed to trip or disable.
- Chain: Heavy linked construction; not of Minka origin, but adapted into their combat style.
- Braided: Prestigious masterwork of interwoven strands, combining flexibility, strength, and control.

Additional Notes

- Whip blocks collapse after absorbing a single strike.
- Grab effects represent entangling, wrapping, binding, and control techniques.
- Ensnare restricts movement and action until resolved.
- Although Chain is not of Minka craftsmanship, it retains full affinity bonuses when wielded by a Minka.

---

## Shield - (to be reviewed)

Type: **Shield — Weapon of Choice of the Murai**
Description: The Shield is both weapon and armor. Worn rather than carried, it emphasizes protection, counter-strikes, and positional dominance over raw offense.

|  Tag   | Variant | Slash | Pierce | Blunt | Reach | Speed     | Defense   | Wield | Effects                            |
| :----: | ------- | ----- | ------ | ----- | ----- | --------- | --------- | ----- | ---------------------------------- |
|   ⭐   | Base    | Weak  | Fair   | Good  | Low   | Great     | Good      | 1H    | dual: defense+;                    |
|   🔹   | Aurora  | None  | None   | Good  | None  | High      | Fair      | 1H    | dual: defense+;                    |
|   ✨   | Nebula  | Fair  | Good   | Good  | Low   | Excellent | Great     | 1H    | dual: defense+;                    |
|   🪨   | Meteor  | None  | None   | High  | Low   | Good      | Great     | 1H    | dual: defense+;                    |
|   ✂️   | Comet   | Good  | None   | Good  | Low   | Good      | Great     | 1H    | dual: defense+;                    |
|  🎯📏  | Galaxy  | Fair  | None   | High  | Great | Fair      | Great     | 1H    | dual: defense+; throw: range fair; |
|  🪨🌟  | Eclipse | Fair  | None   | High  | Low   | Low       | Excellent | 1H    | —                                  |
| 🌟✂️📌 | Nova    | High  | Good   | High  | Fair  | High      | High      | 1H    | dual: defense+;                    |

Components: Shell, Frame, Brace, Lining, Strap, [Grip], [Tether]

Component descriptions

- Shell: The outward-facing surface. Shape defines offensive capability and coverage.
- Frame: Internal structure that distributes impact and determines maximum defense.
- Brace: Forearm anchoring structure; limits hand dexterity while increasing stability.
- Lining: Padding between shell and arm; improves comfort and impact absorption.
- Strap: Secures the shield to the arm and body.
- [Grip] (Optional): Secondary control handle for enhanced striking precision.
- [Tether] (Optional): Retrieval cord; required for Galaxy builds.

Variant Descriptions

- Base: Pointed shell extending forward; back ends at the elbow. Balanced offense and defense.
- Aurora: Small circular shield that does not extend past the forearm.
- Nebula: Forward point with two rear points, improving balance and counter-pressure.
- Meteor: Forward mass concentrates blunt force.
- Comet: Forward edge splits into two blades.
- Galaxy: Large circular shield extending past the forearm; equipped with a tether for controlled throws.
- Eclipse: Massive circular shield roughly half the wielder’s height. Emphasizes immovability.
- Nova: Triple-bladed front with a pointed rear; highly aggressive for a shield.

Additional Notes

- Shields are **worn**, not held. Hands have limited mobility: most actions are possible, but wielding another weapon or performing fine manipulation is not.
- Shields are secured to bracers; they **do not quick-equip**.
- When sheathed, shields contribute to **armor defense**.
- **Aurora*- may be wielded alongside other weapons but cannot be sheathed.
- Galaxy is the only shield variant that supports a tether component.

---

## Tonfa - (to be reviewed)

Type: **Tonfa — Weapon of Choice of the Jin**
Description: A one-handed weapon consisting of a main shaft and a perpendicular grip. Jin Tonfas are traditionally forged in Day and Night classes, gaining additional effects when paired with their counterpart.

|  Tag   | Variant       | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects                                                                                |
| :----: |-------------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | -------------------------------------------------------------------------------------- |
|   ⭐   | Daylight      | Fair  | Fair   | Good  | Low   | High  | Good    | 1H    | sun: blunt+; moon: defense+;                                                           |
|   ⭐   | Nightshine    | Good  | Fair   | Fair  | Low   | Good  | High    | 1H    | moon: slash+; sun: speed+;                                                             |
|   🔹   | Morning Dew   | Low   | Low    | Fair  | Low   | Fair  | Good    | 1H    | sun: blunt+; twilight mist: speed+;                                                    |
|   🔹   | Twilight Mist | Fair  | Low    | Low   | Low   | Good  | Fair    | 1H    | moon: slash+; morning dew: defense+;                                                   |
|   ✨   | High Noon     | None  | None   | Good  | Low   | Fair  | Great   | 1H    | sun: critical+; midnight star: grab+;                                                  |
|   ✨   | Midnight Star | Good  | Good   | None  | Low   | High  | Good    | 1H    | moon: stagger+; high noon: parry+;                                                     |
|   ✨   | Sun Rise      | Good  | Good   | Great | Fair  | Good  | High    | 1H    | sun: ???; moon shadow: ???;                                                            |
|   ✨   | Moon Shadow   | Great | Great  | Good  | Fair  | High  | Good    | 1H    | moon: ???; sun rise: ???;                                                              |
|   🌟   | Day Breaker   | Good  | Good   | Good  | Fair  | High  | Good    | 1H    | moon: defense+; sun: blunt+, block: blunt+; charge: unbreakable; night fall: stagger+; |
|   🌟   | Night Fall    | Good  | Good   | Good  | Fair  | High  | Good    | 1H    | sun: speed+; moon: slash+, pierce+; day breaker: critical+, grab+;                     |

Components: Shaft, Grip, [Joint]

Component descriptions

- Shaft: Primary striking body. Shape and reinforcement determine blunt emphasis and blocking stability.
- Grip: Perpendicular handle used for retention, rotation, and close-quarters control.
- [Joint] (Optional): Added to the grip to enable joined configurations and dual/double-wield behavior.

Variant Descriptions

- Daylight: Base Day-class Tonfa.
- Nightshine: Base Night-class Tonfa.
- Morning Dew: Common Day-class Tonfa.
- Twilight Mist: Common Night-class Tonfa.
- High Noon: Refined Day-class Tonfa with strong defensive posture.
- Midnight Star: Refined Night-class Tonfa with aggressive tempo.
- Sun Rise: Enhanced Day-class Tonfa.
- Moon Shadow: Enhanced Night-class Tonfa.
- Day Breaker: Prestigious Day-class Tonfa.
- Night Fall: Prestigious Night-class Tonfa.

Additional Notes

- Day-class Tonfas: Daylight, Morning Dew, High Noon, Sun Rise, Day Breaker.
- Night-class Tonfas: Nightshine, Twilight Mist, Midnight Star, Moon Shadow, Night Fall.
- Day Tonfas are common among the Jin.
- Night Tonfas are limited and carried by Jin Shadows (a secret protective force).
- Pairing conditions (`sun`, `moon`, and named pair links like `high noon`) represent inherent synergy triggers when wielded alongside the specified counterpart.
- A joint can be added to the grip, allowing joined wielding while preserving dual effects.

---

## Chuck - (to be reviewed)

Type: **Chuck — Weapon of Choice of the Imoh**
Description: —

|  Tag   | Variant    | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects |
| :----: | ---------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | ------- |
|   ⭐   | Base       | None  | None   | Good  | Fair  | Great | Fair    | 1H    | —       |
|   ✨   | Echo       | —     | —      | —     | —     | —     | —       | 1H    | —       |
|   ✨   | Dazzel     | —     | —      | —     | —     | —     | —       | 1H    | —       |
|   🪨   | Heavy      | —     | —      | Great | —     | —     | —       | 1H    | —       |
|   📌   | Spiked     | —     | Great  | —     | —     | —     | —       | 1H    | —       |
|   ✂️   | Hook       | Great | —      | —     | —     | —     | —       | 1H    | —       |
|   🔨   | Reinforced | —     | —      | —     | —     | —     | —       | 1H    | —       |
|   🌟   | Champion   | —     | —      | —     | —     | —     | —       | 1H    | —       |

Components: Stocks, Connector, [Third Segment]

Component descriptions

- Stocks: The striking segments. Material and mass define blunt output and handling.
- Connector: Flexible link between stocks. Length and stiffness define reach, speed, and control behavior.
- [Third Segment] (Optional): Adds a third stock, converting any variant into a “triple chuck.”

Variant Descriptions

- Base: —
- Echo: —
- Dazzel: —
- Heavy: —
- Spiked: —
- Hook: —
- Reinforced: —
- Champion: —

Additional Notes

- **Imoh-Forged:*- Base, Echo, Dazzel, Champion
- **Foreign-Forged:*- Heavy, Spiked, Hook, Reinforced
- Third Segment may be added to any variant to create a triple chuck.

---

## Club - (to be reviewed)

Type: **Club — Weapon of Choice of the Corlee**
Description: —

|  Tag   | Variant    | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects |
| :----: | ---------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | ------- |
|   ⭐   | Base       | None  | None   | Good  | Fair  | Great | Fair    | 1H    | —       |
|   🔹   | Duster     | Weak  | None   | Good  | None  | Good  | None    | 1H    | —       |
|   🔹   | Billy      | —     | —      | —     | —     | —     | —       | 1H    | —       |
|   🪨   | Batson     | —     | —      | —     | —     | —     | —       | 2H    | —       |
|   🔧   | Crowston   | —     | —      | —     | —     | —     | —       | 1H    | —       |
|   🎵   | Piper      | —     | —      | —     | —     | —     | —       | 1H    | —       |
|  📌🪨  | Spiker     | —     | —      | —     | —     | —     | —       | 2H    | —       |
|  🔧🪨  | Wrencher   | —     | —      | —     | —     | —     | —       | 2H    | —       |
|  🌟🪨  | The Mauler | —     | —      | —     | —     | —     | —       | 2H    | —       |

Components: Core, Grip, Head, [Strap], [Studs], [Spike], [Hook]

Component descriptions

- Core: Main body material (wood/stone/metal) defining blunt output and durability.
- Grip: Handling surface; affects speed and retention.
- Head: Weighted end (or thickened section) that determines impact emphasis and defense on blocks.
- [Strap] (Optional): Wrist strap for retention; may support quick-equip / loss prevention.
- [Studs] (Optional): Embedded lumps/spikes for increased trauma.
- [Spike] (Optional): Converts some strikes into pierce-capable hits.
- [Hook] (Optional): Enables snag/pull interactions (tool-like variants).

Variant Descriptions

- Base: —
- Duster: —
- Billy: —
- Batson: —
- Crowston: —
- Piper: —
- Spiker: —
- Wrencher: —
- The Mauler: —

Additional Notes

- —

---

## Dart - (to be reviewed)

Type: **Dart — Weapon of Choice of the Nink**
Description: For most people, darts are thrown weapons. For the Nink—small, levitating, and capable of wielding tools via immaterial grasp—darts are properly proportioned melee weapons. They can still be thrown, then re-controlled or re-acquired through grasp technique.

|  Tag   | Variant   | Slash | Pierce | Blunt | Reach | Range | Speed | Defense | Wield | Effects |
| :----: | --------- | ----- | ------ | ----- | ----- | ----- | ----- | ------- | ----- | ------- |
|   ⭐   | Base      | None  | Good   | None  | Low   | Good  | High  | Weak    | 1H    | —       |
|   🔹   | Pin       | None  | Fair   | None  | Weak  | Fair  | Good  | Weak    | 1H    | —       |
| 🔹📌✂️ | Leaf      | Fair  | Fair   | None  | Weak  | Fair  | Good  | Weak    | 1H    | —       |
|   ✂️   | Lance     | Good  | Fair   | None  | Low   | Good  | Good  | Weak    | 1H    | —       |
|   📌   | Needle    | None  | High   | None  | Low   | High  | High  | Weak    | 1H    | —       |
|   🔨   | Rod       | None  | None   | Good  | Low   | Fair  | Good  | Weak    | 1H    | —       |
|  ✨📌  | Fléchette | Fair  | High   | None  | Low   | High  | High  | Low     | 1H    | —       |
|  🪨🎯  | Javelin   | None  | Good   | Fair  | Fair  | Low   | Good  | Low     | 2H    | —       |

Components: Shaft, Point, Fletching, [Weight], [Coating], [Rig]

Component descriptions

- Shaft: Main body; length and stiffness determine stability and handling.
- Point: Tip geometry defines pierce and any cutting edge.
- Fletching: Stabilizes flight (more relevant to non-Nink use and throw-focused builds).
- [Weight] (Optional): Alters balance; can increase impact at cost of speed.
- [Coating] (Optional): Enables effect delivery (status, irritant, adhesive, etc.).
- [Rig] (Optional): Carry/ready system for quick access.

Variant Descriptions

- Base: Standard dart optimized for balanced melee use (Nink) and reliable throws (others).
- Pin: Simple, small point.
- Leaf: Kunai-shaped dart; a utility form with both point and edge.
- Lance: Longer cutting head favoring slash contact.
- Needle: Narrow precision point built for penetration.
- Rod: Blunt dart for impact and disruption.
- Fléchette: Refined dart with superior stability and penetration.
- Javelin: Oversized dart; closer to a short spear.

Additional Notes

- **Immaterial Grasp (Nink trait):*- Nink can wield darts without physically holding them. Each grasp functions like a “hand slot” and can be contested (pull/strain/disrupt). Up to seven grasps may be developed.
- Dart Range is always shown (throwing remains valid for all users, and for Nink as technique).

---

## Tooth - (to be reviewed)

Type: **Tooth — Weapon of Choice of the Rowlf**
Description: Tooth are bite-handled blades used by the Rowlf with mouth-grip and forepaw control. The Bite is the handle. The striking portion curves at a right angle from the Bite, allowing stabbing, slashing, hooking, and hammering motions that match Rowlf posture and head movement.

|  Tag   | Variant         | Slash | Pierce | Blunt | Reach | Speed | Defense | Wield | Effects   |
| :----: | --------------- | ----- | ------ | ----- | ----- | ----- | ------- | ----- | --------- |
|   ⭐   | Jrrn (Horn)     | —     | —      | —     | —     | —     | —       | 1H    | —         |
| 🔹👐⚡ | Ff-ng (Fang)    | —     | —      | —     | —     | —     | —       | 1H    | dual: —;  |
|  🪨📌  | Tss-g (Tusk)    | —     | —      | —     | —     | —     | —       | 1H    | —         |
|  🎯✂️  | T-lnn (Talon)   | —     | —      | —     | —     | —     | —       | 1H    | throw: —; |
|  🪨✂️  | On-tlr (Antler) | —     | —      | —     | —     | —     | —       | 1H    | —         |
|   📌   | St-ng (Sting)   | —     | —      | —     | —     | —     | —       | 1H    | —         |
|  ✂️📌  | M-gss (Beak)    | —     | —      | —     | —     | —     | —       | 1H    | —         |
|  🪨🔨  | Rrrm (Ram)      | —     | —      | —     | —     | —     | —       | 1H    | —         |
| 🌟📌✂️ | T-grr (Dagger)  | —     | —      | —     | —     | —     | —       | 1H    | —         |

Components: Bite, Hook, [Guard], [Strap], [Ornament]

Component descriptions

- Bite: The mouth/paw handle section. Shaped for jaw retention and forepaw bracing.
- Hook: The striking blade that bends ~90° from the Bite. Geometry defines slash/pierce/blunt emphasis.
- [Guard] (Optional): Jaw-safe lip or paw-stop; improves control/defense.
- [Strap] (Optional): Retention loop for forepaw or harness.
- [Ornament] (Optional): Clan mark, trophy binding, or bone etching.

Variant Descriptions

- Jrrn (Horn): Straight, knife-like Tooth. Balanced stab-and-slash form.
- Ff-ng (Fang): Smaller Tooth designed for forepaw use. Dual-wieldable in paws.
- Tss-g (Tusk): Heavy pointed form favoring blunt + pierce; minimal slash.
- T-lnn (Talon): Throw-capable Tooth; a slashing-oriented throwing knife form.
- On-tlr (Antler): Wider blade face favoring blunt + slash.
- St-ng (Sting): Slim, narrow blade. Pure stabbing focus.
- M-gss (Beak): Pecking geometry; quick stab-and-slash hybrid.
- Rrrm (Ram): Hammer-like Tooth; heavy, pure blunt with curled solid mass.
- T-grr (Dagger): Saber-tooth form; pierce + slash with predatory curvature.

Additional Notes

- Rowlf phonology shapes naming: certain sounds are not produced in native speech; variant names reflect pronounceable forms.
- Tooth are designed for mouth handling and forepaw bracing, matching quadruped posture.

---

## Pitchfork - (to be reviewed)

Type: **Pitchfork — Weapon of Choice of the Redn**
Description: The Pitchfork is a farm tool pressed into service. The Redn have no standing military; when defense is needed, they use what is available. Pitchfork variants reflect agricultural purpose rather than combat doctrine.

|  Tag   | Variant           | Slash | Pierce | Blunt | Reach     | Speed | Defense | Wield | Effects                                                 |
| :----: | ----------------- | ----- | ------ | ----- | --------- | ----- | ------- | ----- | ------------------------------------------------------- |
|   ⭐   |Base               | Poor  | Good   | Fair  | High      | Good  | Fair    | 2H    | —                                                       |
|   🔹   | Shovel            | Fair  | Poor   | Good  | High      | Good  | Good    | 2H    | resist stagger;                                         |
|   🔹   | Hoe               | Good  | Poor   | Good  | High      | Good  | Fair    | 2H    | parry+;                                                 |
|  🔹🎯  | Hay Fork          | Poor  | Good   | Poor  | High      | Good  | Fair    | 2H    | critical%+;                                             |
|   🔹   | Garden Fork       | Poor  | Good   | Good  | Good      | Fair  | Fair    | 2H    | disarm%+;                                               |
|  🔹🪨  | Harvest Pitchfork | Poor  | Good   | Poor  | Good      | Poor  | High    | 2H    | perch: regen+;                                          |
|  🔹🪨  | Rock Fork         | None  | Poor   | Good  | Good      | Poor  | High    | 2H    | strike: splash;                                         |
|  ⚡👐  | Weeding Fork      | Fair  | Good   | Poor  | Fair      | High  | Poor    | 1H    | dual; parry: disarm%+; critical%+; parry+; pivot-;      |
|   🌟   | Combat Pitchfork  | Good  | High   | Fair  | Excellent | Good  | Good    | 2H    | perch: regen+; parry+; parry: disarm%+; resist stagger; |

Components: Head (Tines/Blade), Shaft, Grip, [Ferrule], [Crossbar], [Reinforcement]

Component descriptions

- Head: Working end of the tool (tines, blade edge, or heavy prongs). Defines pierce vs blunt vs slash bias.
- Shaft: Common wood in standard tools; upgraded shafts improve durability and control in combat builds.
- Grip: Handling wrap and balance point.
- [Ferrule] (Optional): Metal collar strengthening head-to-shaft connection.
- [Crossbar] (Optional): Hand stop for leverage and safer thrusts.
- [Reinforcement] (Optional): Armory-grade strengthening (steel core, bracing, improved tines).

Variant Descriptions

- Base: Standard pitchfork used for lifting and moving material.
- Shovel: Broad head for moving soil; stronger blocks and blunt strikes.
- Hoe: Edge-forward tool; more reliable cuts and cleaner parries.
- Hay Fork: Light fork for tossing hay; favors quick thrusts and opportunistic crits.
- Garden Fork: Sturdier fork for turning soil; more likely to disarm on contact.
- Harvest Pitchfork: Built to brace and hold loads; slow but sturdy, supports perching recovery.
- Rock Fork: Heavy-duty fork for shifting dense material; impacts create splash.
- Weeding Fork: Light, fast implement; usable one-handed and dual-wieldable but poor for defense and pivoting.
- Combat Pitchfork: Armory-forged version using reinforced shaft and head; designed for real fighting rather than farm work.

Additional Notes

- Pitchfork variants are not designed for combat; their overall combat performance is limited by common materials and tool ergonomics.
- Range is omitted (defaults to Low).
- **Perch*- represents bracing the tool to rest, stabilize, or hold position; `perch: regen+` increases regeneration while perching.
- `pivot-` indicates reduced pivot maneuvering (harder to change angle/rotate efficiently in close quarters).

---

## Saw - (to be reviewed)

Type: **Saw — Weapon of Choice of the Kapopa**

Description: Kapopa saws are crafted tools turned into brutal cutting weapons. Their edge is a line of teeth—meant to *bite*, not slice cleanly—making them especially vicious in close work. Kapopa craftsmanship is typically **Refined*- quality or better.

|  Tag   | Variant     | Slash | Pierce | Blunt | Reach     | Speed | Defense | Wield | Effects                        |
| :----: | ----------- | ----- | ------ | ----- | --------- | ----- | ------- | ----- | ------------------------------ |
|   ⭐   |Saw          | Good  | None   | Fair  | Fair      | Good  | Fair    | 1H    | —                              |
|   ✨   | Ripsaw      | High  | None   | Fair  | Fair      | Fair  | Good    | 1H    | critical%+;                    |
|  📏✂️  | Whipsaw     | High  | None   | None  | Excellent | Good  | Low     | 1H    | slash: bleed;                  |
|   ✨   | Bow Saw     | Good  | None   | Good  | Good      | Fair  | Good    | 1H    | disarm%+;                      |
|  🪨🔨  | Buck Saw    | Good  | None   | High  | Good      | Low   | High    | 2H    | critical: splash;              |
|   📌   | Jab Saw     | Good  | Fair   | Low   | Low       | Low   | Low     | 1H    | parry: critical;               |
|   🌟   | Tenor Saw   | High  | None   | High  | Good      | Good  | Good    | 1H    | parry: bleed;                  |
|  ✨✂️  | Chinsel Saw | Good  | None   | Fair  | Fair      | Good  | Fair    | 1H    | critical: bleed; critical%+;   |
|  🌟🪨  | Great Saw   | High  | Low    | Good  | Good      | Low   | High    | 2H    | strike: splash; splash: bleed; |

Components: Blade, Teeth, Handle, Spine/Frame, [Guard], [Tension Cord], [Second Handle]

Component descriptions

- Blade: The main cutting body the teeth are set into.
- Teeth: The biting edge. Tooth shape and spacing determine cut aggression and bleed tendency.
- Handle: Primary grip and control point.
- Spine/Frame: Structural support that prevents flex and improves defense on blocks.
- [Guard] (Optional): Hand protection and impact stop.
- [Tension Cord] (Optional): Required for bow-style frames; increases stability.
- [Second Handle] (Optional): Enables better leverage or true 2H operation on large builds.

Variant Descriptions

- Saw: Standard hand saw. Reliable cutting, simple handling.
- Ripsaw: Aggressive tooth geometry optimized to tear along grain—translates to higher crit frequency in combat.
- Whipsaw: Long, flexible saw optimized for reach and continuous cutting pressure; sacrifices defense.
- Bow Saw: Framed saw built for controlled cuts and leverage; excels at snagging and disarming.
- Buck Saw: Heavy framed saw with strong impact presence; crits create splash damage.
- Jab Saw: Compact thrust-capable saw form; rewards defensive timing with parry crits.
- Tenor Saw: Refined, powerful form; parries cause bleed through tooth catch and drag.
- Chinsel Saw: Precise toothwork; crits cause bleed and crit frequency is elevated.
- Great Saw: Massive saw built for destructive sweeping cuts; splash damage with bleeding spread.

Additional Notes

- Range is omitted (defaults to Low).
- Kapopa craftsmanship trends **Refined+**, so saw weapons commonly roll higher resulting stats than equivalent “tool weapons” from other cultures.
- Kapopa anatomy: they have **four wielding limbs*- (two arms plus forepaws capable of gripping). They can dual-wield configurations that would normally require two hands (including 2H weapons), subject to technique constraints.
