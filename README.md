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

Scope of this mod:
- Rebalance existing production chains for manufactured goods
- Add production chains for goods that cannot otherwise be crafted

> [!IMPORTANT]
> Requires [Vanilla Expanded Framework](https://steamcommunity.com/sharedfiles/filedetails/?id=2023507013).

## Changes
### Components
- Craftable at the machining table with a 20% increased work requirement compared to fabrication

### Metal
- Adds production chains for steel, silver, gold, and plasteel
- Steel chain is required, the rest are toggable
- Toggable patches to improve vanilla metal balance

#### Refining
|  | Ore (Bulk) | Coal (Bulk) | Work amount (Bulk) | Output (Bulk) |
|---:|:---:|:---:|:---:|:---:|
| Steel | 15 (60) | 5 (20) | 1000 (4000) | 15 (60) |
| Plasteel | 12[^1] (48) | 1 (4) | 2000 (8000) | 10 (40) |
| Silver | 50 (200) | 5 (20) | 1125 (4500) | 50 (200) |
| Gold | 10 (40) | ~ | 1250 (5000) | 10 (40) |

### Neutroamine
- (WIP) ~~Can now be synthesized in an expensive three step process~~

### Textiles
- Cotton and devilstrand plants now yield raw fiber that must be spun before it can be used for tailoring
- To offset this additional step, the new 2x1 electric spinning wheel can stack with two tool cabinets for an 18% work speed boost on tailoring benches

### Wood
- Lumber production chain
- Firewood

## Toggable Patches
- Metal is not flammable
- Gold and silver are beautiful
- Increase steel durability
- Increase uranium durability
- Increase plasteel durability
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

## Legal
Portions of the materials used to create this mod are trademarks and/or copyrighted works of Ludeon Studios Inc. All rights reserved by Ludeon. This mod is not official and is not endorsed by Ludeon.

This mod includes code and textures from [Simple Chains: Lumber](https://github.com/Owlchemist/simple-chains-lumber) by Owlchemist, originally licensed under the GPL-3.0 License. These assets have been modified by boomer.\
This mod includes code and textures from [Simple Chains: Steel](https://github.com/Owlchemist/simple-chains-steel) by Owlchemist, originally licensed under the GPL-3.0 License. These assets have been modified by boomer.

[^1]: Also requires 3 iron ore (12 for bulk).
[^2]: [Money making guide - RimWorld Wiki](https://rimworldwiki.com/wiki/Money_making_guide)