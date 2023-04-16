# unitscan_turtle    
[Unitscan](https://github.com/shirsig/unitscan-vanilla) modified for [Turtle WoW](https://turtle-wow.org/).

## Issues
Target switching may cause wanding/auto attack to stop.

## Description
This fork extends [unitscan-vanilla](https://github.com/shirsig/unitscan-vanilla) by automatically managing active scan targets ([zone targets](https://github.com/GryllsAddons/unitscan-turtle/blob/master/zonetargets.lua)) when you enter a zone.

The [zone targets](https://github.com/GryllsAddons/unitscan-turtle/blob/master/zonetargets.lua) includes all rare mobs in vanilla as a baseline.

This addon has a focus on leveling and [hardcore](https://turtle-wow.org/#/hardcore-mode) which is reflected in the choice of zone targets.

You can add custom targets to find players or targets not included in the zone targets list by using the command /unitscan *name*.

Unitscan will only look for zone targets specific to your current zone. The target list is reloaded when you change zones.

Zone targets will be reloaded 90 seconds after you have found a target (to re-detect roaming targets).

Unitscan will alert you of NPC targets that you can attack and are alive. 

You will always be alerted for player targets regardless.

Targets added by the /unitscan command will be removed from active scan targets after they are found.

You can move the unitscan frame by holding ctrl and dragging.
 
**Please note unitscan-turtle will not auto target the target when it is found.**    
**Click the target in the unitscan window or use the macro /unitscantarget to target the mob.**

## Commands
**/unitscan** *lists the active scan targets*    
**/unitscan name** *adds/removes **name** to/from the active scan targets*    
**/unitscantarget** *targets the most recently found target*    

## Updating Zone Targets
The target list was pulled from classic however please [create an issue](https://github.com/GryllsAddons/unitscan-turtle/issues) for adding any missing custom Turtle WoW targets or any other dangerous or noteworthy targets.
