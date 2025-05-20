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

# [CorePlus] Industry
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
Production chains add tedium to the game. This is good for immersion, but (in my experience) detracts from the overall experience when there's no benefit. Accordingly, the refining recipes have been balanced to maximize output per job and create a stream of income for mining colonies that doesn't break the economy.

Here's how refining jobs compare to vanilla[^2] money making activities:
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

Wealth management is another upside of refining chains over vanilla mining. Since raw materials are worth less than their refined counterparts, mining large veins doesn't drastically inflate your colony's wealth. Refining bills can be managed to meet the colony's needs without creating excess wealth.

### Refining Recipes
|  | Ore (Bulk) | Coal (Bulk) | Work amount (Bulk) | Output (Bulk) |
|---:|:---:|:---:|:---:|:---:|
| Steel | 15 (60) | 5 (20) | 1000 (4000) | 15 (60) |
| Plasteel | 12[^1] (48) | 1 (4) | 2000 (8000) | 10 (40) |
| Silver | 50 (200) | 5 (20) | 1125 (4500) | 50 (200) |
| Gold | 10 (40) | ~ | 1250 (5000) | 10 (40) |

## Legal
Portions of the materials used to create this mod are trademarks and/or copyrighted works of Ludeon Studios Inc. All rights reserved by Ludeon. This mod is not official and is not endorsed by Ludeon.

This mod includes code and textures from [Simple Chains: Lumber](https://github.com/Owlchemist/simple-chains-lumber) and [Simple Chains: Steel](https://github.com/Owlchemist/simple-chains-steel) by Owlchemist, originally licensed under the GPL-3.0 License. These assets have been modified by boomer.

[^1]: Also requires 3 iron ore (12 for bulk).
[^2]: [Money making guide - RimWorld Wiki](https://rimworldwiki.com/wiki/Money_making_guide)