# thoughts 
Since spinning was a tailoring job, it was taking priority over other similar jobs like stonecutting. I think all of these raw material processing jobs should be processed together, so I'm moving it to crafting. From a lore perspective, I could see someone learning to spin cloth without knowing how to tailor a vest (similar to a stonecutter not knowing how to build a wall).

Fiber had no thingCategory, so it was deteriorating outside instead of being moved to the storage room. Whoops. Afterwards, I had about 45 cotton collecting dust because the only crafting bill is 50:25 fiber to cotton. Since these crafting bills only exist on spinning wheels, bloating the bills tab isn't a concern.

There's probably not a perfect solution for extra fibers. At some point, I'll probably have 2 or 3 fiber lying around with no plans of making more cotton. I don't think I need to solve for this, but I could add a burning recipe if it becomes an annoyance.

Spinning on the manual wheel is really fast. Early-game processing might be really annoying when I debuff it after adding the electric wheel.

## summary
 - consider a burning bill to deal with unused fibers

# changes
 - add `thingCategory` to fiber so it can be stored
 - assign spinning bills to `DoBillsUseCraftingSpot`
 - rename current spinning bills and add 10:5 crafting bills