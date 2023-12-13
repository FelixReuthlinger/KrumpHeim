* 2.5.3 -> fixed spinning wheel config to also take spools
* 2.5.2 -> stackable carcasses
* 2.5.1 -> updated dependencies
* 2.5.0 -> 
    * updated for new Reforge version
    * removed some unnecessary mods and replaced the buggy conversion size and speed mod
* 2.4.1 -> more stacks configured
* 2.4.0 -> configured some stacks and plants
* 2.3.8 -> dropped CLLC from mod list, no need for this here imho
* 2.3.7 -> better wood stacks, now all 500
* 2.3.6 -> 
    * updated conversion size and speed config since long time again
    * updated dependencies to latest
* 2.3.5 -> added stackability to new carcasses, removed praying system overrides due to upcoming release
* 2.3.4 -> ops, I guess I forgot to remove randys eqas before
* 2.3.3 -> added foraging mod back
* 2.3.2 -> added auto store by azu
* 2.3.1 -> 
    * removed no skill drain and randy' eqas (since now skill and dropping equipment is available as valheim map options)
    * using Azu player inv with quick slots and equipment slots now
* 2.3.0 -> updated dependencies for latest Valheim version 0.217.30
* 2.2.0 -> 
    * removed "Farming" mod, since Datys Professions does now implement the farming skill
    * removed also "Foraging" mod, since not that necessary and might be conflicting with Reforge farming skills
    * removed blocking mod (long time no updates)
    * removed some server-only mods (server characters, server dev commands, multi user chest, networking)
    * added Reforge UI mod as replacement for the deprecated better UI
    * updated dependencies
* 2.1.5 -> forgot to remove the delete part for rune magic, now it should work again
* 2.1.4 -> 
    * turned off CLLC multiple boss trophies drop
    * added RuneMagic back after fixed
* 2.1.3 -> updated dependencies
* 2.1.2 -> temporarily removed Rune Magic due to bad HTTP library reference causing issues on logout/quit
* 2.1.1 -> removed outdated better UI
* 2.1.0 -> updated all dependencies and reforge 3.0.2
* 2.0.2 ->
    * extracted the AutoMapPins config to its own mod and using it in here
* 2.0.1 ->
    * replaced the broken instant loot drops mod, since it crashed any console commands
* 2.0.0 ->
    * finally Hildir's Quest update for Reforged and this pack
* 1.5.9 -> 
    * added more missing pins for reforge
    * updated dependencies
* 1.5.8 -> fixed temple icon, added hay icon
* 1.5.7 -> dependency update, added treasure pin configs
* 1.5.6 -> using smaller icons for map pins
* 1.5.5 -> updated version and fixed drying station renaming
* 1.5.3 & .4 ->
    * replaced auto map pins mod
* 1.5.2 ->
    * added my own new way of dynamically changing the discovery radius
    * dependency updates
* 1.5.0 & .1 -> 
    * updated dependencies for Valheim version 0.216.9
* 1.4.1 ->
    * fixed outdated discord link to Krumpac's 
    * updated dependencies
* 1.4.0 -> 
    * updated to the latest closed BETA community release of Reforge (requires )
* 1.3.3 -> 
    * updated dependencies
    * removed overriding spawners, moved those to another mod pack to make re-usable more widely
* 1.3.2 -> added custom praying config
* 1.3.1 -> added reconfiguration for the reforge plants
* 1.3.0 ->
    * updated to new reforge 1.7.9 and others
* 1.2.3 -> 
    * again tweaked spawners down a bit for treasures
    * replaced networking improvement mod (since old one seems to cause issues some times)
        * added script to remove the old one automatically
* 1.2.2 -> 
    * added loading screens
    * updated dependencies
    * decreased some spawners
* 1.2.1 -> fixed crafting station renamings (again and again and again... why? ;D)
* 1.2.0 ->
    * updated to reforge core 1.7.8
    * updated to professions 1.1.4
* 1.1.17 -> 
    * fixed some professions respawners
* 1.1.16 ->
    * cllc bosses nerfed
* 1.1.15 ->
    * fixed respawning herbs
* 1.1.14 ->
    * increased difficulty for creatures and especially bosses
    * dependency updates
* 1.1.13 -> 
    * added some basic item configs for cllc to override some game settings
    * added professions spawners back to Leifheim
* 1.1.11 & 12 -> another fix for renamed crafting stations (again)
* 1.1.10 ->
    * fixed conversion sizes for crafting stations (due to update issue)
    * added mod for extra stamina regen from foods
* 1.1.9 ->
    * increased the ranges, since bigger base range requires it
    * increased fishies
* 1.1.8 ->
    * fixes for conversion rates due to renaming issues
* 1.1.6 and .7 ->
    * updated dependencies
* 1.1.5 ->
    * fixed conversion size and speed config due to renaming issues
    * adding server dev commands
    * removed some config removal scripts, since reforge now include those and works fine
* 1.1.4 -> 
    * updated dependencies
* 1.1.3 -> 
    * fix the fix, now correct building pieces file
    * updated to latest reforge core version
* 1.1.2 ->
    * let's try this better networking
    * added cllc yamls for reforge
    * overriding the building pieces, why ever generated me wrong recipes
* 1.1.1 -> 
    * removed player building display from map details config
    * removed outdated overrides files from older krumpac mods
* 1.1.0 -> 
    * updates for Krumpac mods update
    * added CLLC
    * CLLC configured to medium (0 to 3 stars, no special things)
    * adding CLLC yamls for vanilla Valheim
    * dropped item drawers as not being nicely compatible with crafting from boxes
    * increased default container sizes instead supporting item drawers
* 1.0.13 -> 
    * added map details showing Krump's custom ships on map
    * dependency update
* 1.0.12 -> ok, Azu fails on empty yaml deserialization... added contents
* 1.0.11 -> finally replacing odin's crafty boxes with Azu's - good job, works fine now
* 1.0.10 -> dependencies updated
* 1.0.9 -> 
    * further improved cutting table capacity
    * deletion of outdated configs and mods added
* 1.0.8 -> fixed deletion and overrides
* 1.0.7 ->
    * improved spawners for lydit, hay, fishes, etc. (more frequent)
    * improved farming, lumberjacking, building configs (more yield, level entry level for special skills)
    * improved configs for conversion size and speed to add additional space for each killed boss, increased capacities, lowered production time
* 1.0.6 -> 
    * changed empty bucket recipe until fixed in core
    * changed rune magic foundation to use player location height
    * added build camera mod, since some build pieces are too large for short default range
* 1.0.5 -> 
    * removed some of the rune magic runes for just growing stones
    * combat slope mod removed, not compatible with how weapons are designed
* 1.0.4 -> added combat slope mod and this goes here to delete krumpac configs each boot
* 1.0.3 -> foraging and conversion config changes
* 1.0.2 -> adding server characters
* 1.0.1 -> dependency updates & added regenerative nature
* 1.0.0 -> first version
