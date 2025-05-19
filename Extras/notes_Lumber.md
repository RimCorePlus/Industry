# thoughts
Two days to dry is enough of an inconvenience to force temporary wood log buildings (especially drying racks) without making lumber obsolete. I built some wood log fences to protect my crops and never felt the need to replace them, but the few other structures and buildings I made with wood logs eventually got replaced with wood. Lumber sits in a nice place between wood logs (readily available, cheap, but low quality) and stone blocks.

I'm on the fence about balancing acquisition. On one hand, stone blocks are carved in one go and instantly available for building, whereas lumber has the additional step of drying for two whole days. Stone blocks are also a superior building material (unless you lack the terrain affordance). However, wood is much more plentiful in most biomes in the early game, and I found myself using a mix of stone and wood despite the drying inconvenience.

This made early-game base building more fun for me.

It may be beneficial to add late-game drying options. Woodworkers use something called a "solar kiln" to speed up wood drying. For reference, it takes about a year per inch to air dry lumber versus about a month in a solar kiln.

![](https://images.finewoodworking.com/app/uploads/2024/03/29113915/function-of-a-solar-kiln.jpg)

A solar kiln should probably be 2x1 and hold 100x wood. Anything higher than that would exacerbate the issue introduced in the switch from SYR to Vanilla Expanded, where the processor **must** be full to start processing the recipe. Before, any amount of wood would begin drying as soon as it was placed on the pallet.

The air drying time would probably be best off at 3 days with the solar kiln at 1 day. At 3 days, the theoretical maximum output would be reduced from 375 per quadrum to 250 per quadrum. At 1 day, the solar kiln would have a theoretical maximum output of 1500 (750 per tile) per quadrum. At this rate, one 2x1 solar kiln could theoretically output 6000 wood per year.

Loading and unloading the pallets is kind of micromanage-y. I think it uses the haul job, which is pretty low priority by default. Not sure if a fix is justified or if I'm getting the worst of it because I'm still in the early game. 

## summary
- consider increasing drying time for air drying
- consider adding a solar kiln

# changes
- set `destroyIngredientsAtStartOfProcess` to `true` because green lumber being yielded alongside the dried lumber