Welcome to **dev build 27** of Long War of the Chosen!

This fixes some significant issues with the game and makes some more balance changes. We're not anticipating any more releases other than hotfixes before a 1.0 release!

Headline changes:

 * Unactivated Najas should no longer shoot XCOM on Intel Raid missions
 * Missions with lots of enemies should be noticeably less laggy
 * The issue with blank soldier rewards should no longer happen (fingers crossed)
 * At least one bug with pods not scampering is now fixed
 * LWOTC now comes packaged with the Community Promotion Screen

**Important** After installing the new build, you will need to enable:

 * Long War of the Chosen
 * \[Beta] X2WOTCCommunityHighlander
 * DLC2CommunityHighlander
 * X2WOTCCommunityPromotionScreen

To install dev build 27, just delete your existing LongWarOfTheChosen and X2WOTCCommunityHighlander folders from the *Mods* directory and unpack the following zip there:

||  **[Download the full release from Nexus Mods](https://www.nexusmods.com/xcom2/mods/757?tab=files)** ||

# Changelog dev build 27

## Quality of life

 * Mission screens on the Geoscape now have button hot links for controller users (e.g. B to cancel, A to launch mission/infiltration)

## Balance

### Chosen

 * Knowledge gained from kidnapping is now 10, down from 20
 * Passive knowledge gain per supply drop is now 12, up from 8
 * Chosen Avenger Assault has 6 fewer enemies

### Classes and abilities

*Reaper*
 * Tracking replaces Tradecraft at Squaddie
 * Total Combat replaces Shadow Grenadier (the latter was too easy to cheese with)
 * Blood Trail (+2 damage and -40 Dodge against units wounded that turn) replaces Tracking
 * Shadow can now be activated while flanked
 * Shadow Mobility bonus is now +20%, down from +37.5%
 * Shadow detection radius reduction is now 90%, down from 100%
 * Shadow bonuses no longer passively apply when the Reaper starts a mission in concealment (the Reaper *has* to activate Shadow to get them)
 * Reapers get Infiltration by default, which means they can't be detected by towers (and they get +25 Hack)
 * Knife Encounters range is now 5 tiles, up from 4
 * Homing Mine ability no longer grants Claymore charges as well

*Skirmisher*
 * Ripjack Slash ability replaces Battlemaster at Squaddie
 * Chain Shot replaces Deadeye
 * Battlefield Awareness (Untouchable with a 3-turn cooldown) replaces Untouchable
 * Manual Override reduces cooldown of abilities by 3 turns instead of effectively resetting them; cooldown of Manual Override itself is now 4 turns, down from 5
 * Reflex additionally reduces crit chances against the Skirmisher by 15 (like Resilience)
 * Combat Presence now has a 4-turn cooldown, up from 3
 * Total Combat grants the bonus grenade slot in place of Battlemaster



*Templar*
 * Channel (enemies can drop focus) replaces Concentration
 * Arc Wave AoE damage is now 4/6/8, down from 4/7/10
 * Void Conduit damage per tick is now 3, down from 5
 * Templars no longer get passive ablative from their shields
 * Bonus ablative from One For All is now 4/7/11, up from 4/7/10

*Miscellaneous*
 * Paramedic now also increases medikit heal by 3HP
 * Shooting Sharp bonus aim against units in cover is now +15, up from +10

### Strategy

 * Supply Extraction missions require retrieval of at least 4 crates to be a success (previously they were too easy to abuse for free mission XP)
 * Early Intel Raid missions have 1 or 2 fewer enemies than before
 * There are two new covert actions you can run:
   - Obtain a resistance MEC
   - Recruit resistance rebels
 * Alien Loot covert action now awards some alloys and elerium, with the quantity depending on how far into the campaign you are
 * Rescued soldiers are now healed for a significant portion of their health to compensate for time spent captured
 * Class abilities purchased with AP when another class ability at the same rank has already been picked once again incur a cost multiplier

### Tactical

 * Sectopods should now use their Lightning Field ability on XCOM

## Mods

 * LWOTC now depends on the new Community Promotion Screen, which should improve compatibility with other mods that depend on it
 * Mods can patch multi-shot abilities that are implemented like Rapid Fire/Chain Shot by adding them to the `MULTI_SHOT_ABILITIES` config array in *XComLW_Overhaul.ini*

## Bug fixes

### Strategy

 * You should no longer encounter blank soldier rewards or buggy rescued soldiers
 * You should no longer encounter Chosen at a higher level than intended for the current force level
 * Controller users should be able to traverse the options screen now

### Tactical

 * Disabling the pod leader will no longer prevent the rest of the pod from scampering (this fixes a more general issue with pods not scampering if the pod leader skips their move for any reason)
 * Multi-shot abilities will no longer cause lots of lag on missions with many enemies
 * Reinforcement units spawned from the Avenger on the Avenger Defense mission should now always be controllable
 * The Dark VIP should now be correctly extracted if carried by the last soldier to evac
 * Avenger and Flush will now shred targets if the shooter has the Shredder ability
 * Impersonal Edge will no longer trigger on other units' kills
 * The Sniper Defense AI behaviour should now work, making it harder for Sharpshooters to get flanking shots on enemy units that have no sight on XCOM

Thanks to everyone for their contributions!
