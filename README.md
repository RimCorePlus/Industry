<!--[![GPLv3][badge-license]](https://www.gnu.org/licenses/gpl-3.0) -->
[badge-license]: https://img.shields.io/badge/License-GPLv3-lightgray
<!--![Supports Royalty][badge-dlc-royalty] supports Royalty DLC-->
[badge-dlc-royalty]: https://img.shields.io/badge/DLC-Royalty-gold
<!--![Supports Ideology][badge-dlc-ideology] supports Ideology DLC-->
[badge-dlc-ideology]: https://img.shields.io/badge/DLC-Ideology-indianred
<!--![Supports Biotech][badge-dlc-biotech] supports Biotech DLC-->
[badge-dlc-biotech]: https://img.shields.io/badge/DLC-Biotech-mediumturquoise
<!--![Supports Anomaly][badge-dlc-anomaly] supports Anomaly DLC-->
[badge-dlc-anomaly]: https://img.shields.io/badge/DLC-Anomaly-darkseagreen

# [RCP] Industry
![](About/Preview.png)\
[![GPLv3][badge-license]](https://www.gnu.org/licenses/gpl-3.0)

> [!IMPORTANT]
> Requires [Vanilla Expanded Framework](https://steamcommunity.com/sharedfiles/filedetails/?id=2023507013).

## Changes
### Chocolate
- Cocoa trees now yield cocoa beans, which are cooked with milk at a stove to yield chocolate (can be disabled in settings)

### Components
- Craftable at the machining table with a 20% increased work requirement compared to fabrication

### Metal
- Production chains for steel
- Optional production chains for gold, silver, and plasteel
- [Optional patches](#settings) to improve vanilla metal balance

### Neutroamine
- (WIP) ~~Can now be synthesized in an expensive three step process~~

### Textiles
- Cotton and devilstrand plants now yield raw fiber that must be spun before it can be used for tailoring
- Optional production chain for Synthread (requires Plasteel production chain)
- Patchleather can be tanned to create hardened patchleather

To help offset this added work requirement, the new 2x1 electric spinning wheel stacks with two tool cabinets for an 18% boost to work speed on tailoring benches.

### Wood
- Trees now yield logs that are less useful than wood
- Logs can be processed into firewood or green lumber at a carpentry trestle or machining table
- Green lumber is dried on a drying rack for approximately two days to yield lumber (vanilla wood)
- Wood-fueled benches and campfires now require firewood

## Settings
- [Production Chain] Chocolate
- [Production Chain] Gold
- [Production Chain] Plasteel (disabling this also disables Synthread chain)
- [Production Chain] Silver 
- [Production Chain] Synthread (requires Plasteel chain)
- Beautiful gold and silver
- Easier industrial components (removes workAmount penalty from industrial component recipe, disabled by default)
- Increase plasteel durability
- Increase steel durability
- Increase uranium durability
- Non-flammable metal (affects every metallic and stuffable ThingDef, vanilla and modded)
- Remove compacted machinery
- Remove compacted plasteel

## Impact
Production chains add tedium to the game. This is good for immersion, but (in my experience) detracts from the overall experience when there's no benefit. Accordingly, new production chains have been balanced to maximize output per job and create new streams of income for colonies that doesn't break the economy.

#### Metal
Refining jobs compared to vanilla[^1] money making activities:
|  | Added value (per hr work) |
|---:|:---:|
| Rolling smokeleaf joints | 25 |
| **Steel refining** | **35** |
| Making tribalwear | 43 |
| **Silver refining** | **50** |
| Go-juice synthesis | 55 |
| **Plasteel refining** | **60** |
| Flake synthesis | 64 |
| **Gold refining** | **70** |

Wealth management is another potential upside of refining chains over vanilla mining. Since raw materials are worth less than their refined counterparts, mining large veins doesn't drastically inflate your colony's wealth. Refining bills can be managed to meet the colony's needs without creating excess wealth.

#### Hardened Patchleather
Hardened patchleather is best used for crafting armor. It is superior to cloth, patchleather, and plainleather, and much easier to source than devilstrand and comparable exotic leathers. To offset its abundance, it takes a full day to tan and is 30% slower to craft with than normal leathers.

|  | Beauty | Max Hit Points | Armor - Sharp | Armor - Blunt | Armor - Heat | Insulation - Cold | Insulation - Heat | Market Value |
|---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Patchleather | 1 | 1 | 0.45 | 0.19 | 0.9 | 9 | 9 | 1.5 |
| Plainleather | 1 | 1.3 | 0.81 | 0.24 | 1.5 | 16 | 16 | 2.1 |
| **Hardened Patchleather** | **1** | **1.3** | **0.93** | **0.24** | **1.5** | **9** | **9** | **1.8** |
| Cloth | 1 | 1 | 0.36 | 0 | 0.18 | 18 | 18 | 1.5 |
| Devilstrand | 3.2 | 1.3 | 1.4 | 0.36 | 3 | 20 | 24 | 5.5 |

Since this chain adds a new resource with great benefits over an existing resource, it is not balanced as a money making activity. Hardened patchleather is only slightly more valuable than the sum of its precursors.

## Legal
Portions of the materials used to create this mod are trademarks and/or copyrighted works of Ludeon Studios Inc. All rights reserved by Ludeon. This mod is not official and is not endorsed by Ludeon.

This mod includes code and textures from [Simple Chains: Lumber](https://github.com/Owlchemist/simple-chains-lumber) and [Simple Chains: Steel](https://github.com/Owlchemist/simple-chains-steel) by Owlchemist, originally licensed under the GPL-3.0 License. These assets have been modified by boomer.

[^1]: [Money making guide - RimWorld Wiki](https://rimworldwiki.com/wiki/Money_making_guide)
[^2]: Also requires 3 iron ore (12 for bulk).