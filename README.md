# CVP_7DTD

This modpack for 7 Days to Die is designed to be server-side friendly and aims to address performance and quality of life issues for both myself and my friends. It eliminates the hassle of guiding inexperienced friends through the mod installation process.

***Please ensure that the modlet folder names remain unchanged. The "z" at the beginning of each folder name is intentionally added to enforce proper load order and avoid conflicts. Altering the folder names may result in incorrect functionality.***

## Installation

1. Navigate to your server folder and create a "Mods" folder if one does not already exist.
2. Copy and paste the "zCVP" modlets of your choice into the Mods folder.
3. Enjoy the benefits!

*For local games or singleplayer, follow the same installation steps but locate your game folder instead of a server folder.*

## Included Modlets

### CVP_ZombieLoot
This modlet increases the drop probability and reduces the despawn timer of zombie loot bags.

> To customize the drop probability and despawn timer, navigate to the Mods folder and access `zCVP_ZombieLoot/Config/entityclasses.xml`. Modify the relevant values accordingly.

*Note: This modlet may conflict with any other mods that modify zombies.*

### CVP_SkillPoints
This modlet boosts the number of skill points earned per level (default is 2).

> To adjust the amount of skill points earned, go to the Mods folder and open `zCVP_SkillPoints/Config/progression.xml`. Modify the appropriate values as desired.

*Note: This modlet may conflict with mods that alter the skill point system, particularly overhaul mods.*

### CVP_ForeverTrader
This modlet ensures that traders are available 24/7 and removes the unnecessary open/close announcements.

*Note: This modlet may conflict with mods that modify the trader's operating schedule.*

### CVP_BetterAirdrops
With this modlet, airdrops now contain significantly better loot, making them more rewarding.

> To adjust the loot contents, navigate to the Mods folder and open `zCVP_BetterAirdrops/Config/loot.xml`. Add or modify the appropriate values to suit your preferences.

*Note: This modlet may conflict with mods that modify airdrops.*

### CVP_ModSlots
This modlet establishes a link between mod slots and weapon/armor tiers.

*Note: This modlet may conflict with mods that modify mod slots.*

### CVP_FasterVehicles
This modlet increases the speed (specifically the maxVelocity) of all vehicles.

> To modify vehicle speed, go to the Mods folder and open `zCVP_FasterVehicles/Config/vehicles.xml`. Adjust or add the appropriate values.

*Note: This modlet may conflict with mods that modify vehicle speed.*

### CVP_SilencerUnlocker
This modlet allows the immediate crafting of silencers when a workbench is available.

*Note: This modlet is unlikely to conflict with other mods.*

### CVP_BetterItemStacks
Most item stacks are now increased to 30,000, and casino coins/old cash stacks are increased to 50,000.

> To modify stack sizes, access either `zCVP_BetterItemStacks/Config/blocks.xml` or `zCVP_BetterItemStacks/Config/items.xml` within the Mods folder. Adjust or add the relevant values.

*Note: This modlet may conflict with mods that modify stack sizes.*

### CVP_BetterVehicleStorage
This modlet significantly increases vehicle storage capacity for long-range loot runs while maintaining a balanced approach.

> To modify storage capacity, go to the Mods folder and open `zCVP_BetterVehicleStorage/Config/loot.xml`. Adjust or add the appropriate values.

*Note: This modlet may conflict with mods that modify vehicle storage.*

### CVP_NoTimers
This modlet removes timers associated with looting and block pickup.

*Note: This modlet may conflict with mods that modify loot timers.*

### CVP_BetterTraps
Spike traps take less damage, and the durability of blade traps is increased with this modlet.

> To modify traps, go to the Mods folder and open `zCVP_BetterTraps/Config/blocks.xml`. Adjust or add the relevant values.

*Note: This modlet may conflict with mods that modify existing traps.*

### CVP_BetterZombieRange
This modlet reduces the melee range of zombies.

> To modify zombie range, go to the Mods folder and open `zCVP_BetterZombieRange/Config/items.xml`. Adjust or add the relevant values.

*Note: This modlet may conflict with mods that modify zombies.*

### CVP_T6Crafting
This modlet enables crafting of Tier 6 items with maximum perk levels.

*Note: This modlet may conflict with mods that modify crafting levels.*

### CVP_HarvestMore
This modlet triples the amount of resources gathered.

*Note: This modlet may conflict with mods that modify item harvest counts.*

### CVP_CorpseCleaner
This modlet automatically cleans up zombie bodies after 10 seconds to reduce lag.

> To modify the cleanup settings, go to the Mods folder and open `zCVP_CorpseCleaner/Config/entityclasses.xml`. Adjust or add the relevant values.

*Note: This modlet may conflict with mods that modify zombies.*

### CVP_BetterTurrets
This modlet enhances turrets by increasing the maximum amount of turrets and implementing various general tweaks for improved functionality.

> To customize the turret settings, navigate to the Mods folder and open `zCVP_BetterTurrets/Config/entityclasses.xml`, `zCVP_BetterTurrets/Config/items.xml`, or `zCVP_BetterTurrets/Config/progression.xml`. Adjust or add the relevant values as desired.

*Note: This modlet may conflict with other mods that modify turrets.*
