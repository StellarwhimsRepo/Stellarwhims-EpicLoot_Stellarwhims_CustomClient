# Epic Loot custom changes

This mod contains json config files for [EpicLoot](https://valheim.thunderstore.io/package/RandyKnapp/EpicLoot/)
mod, so, mostly enchanting materials will get dropped. If you are using a mod that allows higher star level monsters, generally,
three star and up will start dropping gear. Monster specific loot (example: troll armor) has been changed to drop only from those 
specific monsters and their loot starts appearing at two stars. In addition, I will be updating as many of the .json files in epicloot 
as neccessary to bring a sense of balance as far as we (the players on my private server) percieve it.

Mostly damage nerfs.

Some Parry, Block, Stamina and Health Regen effects are nerfed, and set to legendary only.

Parry, Block, Stamina and Health Regen for lowhealth are still available to roll as normal.

Removed bows from attack speed effect.

Recipes to build trophies have been removed.

Mythic crafting knowledge has been lost to the ages ...

Keep an eye on the patch notes as this description is more of a general guideline.

# Eitr and other items integration

Be aware:
This mod changes epic loot to drop Greydwarf Eye, Root, Freeze Gland, Dragon Tear, Fuling Totem, Eitr and recipes to use those ingredients, instead of rarity appropriate dust.

## Installation

* Automated: just install as long as using TMM or R2Modman.
* Manual: you need to know what you are doing ;)

Since this mod now uses json config files, no files from the original EpicLoot are overwritten.

If you are using other Epic Loot json config mods, you will need to consult the Epic Loot discord for help integrating them.

The json priority set on the files is left at a default of 500.
 
## Changelog

2.0.2

		- updated for latest epicloot release 0.10.3
		- some now redundant balance changes removed
		- epicloot config file changes
		- added MainStreetGaming-BetterDiving-1.1.0 to dependencies

<details>
  <summary>
    Previous changes:
  </summary>

		2.0.1

				- tuned drops for vanilla difficulty
				- added Azus_UnOfficial_ConfigManager to dependencies
				- added tweaked config for Epic Loot

		2.0.0

				- re-wrote all json modifications as json config file patches.
				- reconfigured for my current mod server configuration. IE: only epic loot configuration. 
				- Other mod configurations have been removed.

		1.3.23

				- changed greylings to drop any tier 0 enchanting material

		1.3.22

				- added wackydatabase files for npc market place
				- hoping will make the npc build pieces only visible to admins

		1.3.21

				- added wackydatabase files for pottery barn pieces
				- added ComfyMods-PotteryBarn-1.5.1 to dependencys

		1.3.20 

				- combined nerfs and loottables mod into one mod
				- they were becoming more and more intertwined
				- the old mods are marked as deprecated and will no longer receive updates

		1.3.19 ( MagicPlugin Integration )

				- surtling and eikthyr staff changes to describe damage post nerf (via wackydb and custom localization text)

		1.3.18 ( MagicPlugin Integration )

				- added MagicPlugin gear to the loottables
				- added MagicPlugin as a dependency

		1.3.17 ( Quest Items Integration ):

				- corrected serpent 1 star drop rates
				- added quest item drops to the ocean biome drop table ( for a future vanilla game update )

		1.3.16 ( Quest Items Integration ):

				- added missing quest item drop chance to black forest npcs

		1.3.15 ( Quest Items Integration ):

				- removed example drops from questitems
				- adjusted quest items drop chance using epic loot

		1.3.14 ( Quest Items Integration ):

				- added QuestItems items to the loottable
				- added QuestItems as a dependency
				- added wackysdatabase as a dependency
				- added supporting config files
				- These changes support use of Valheim Legends mod on my server.
				- saves / servers without valheim legends will be fine.
				- you can sell the drops to the trader.

		1.3.9 ( Eitr Integration ):

				- removed Magic, Rare, Epic, Legendary dust from the loot tables
				- added Eitr to the loot tables
				- Going forward, this mod is intended to be paired with version 1.1.24 (or higher) of [EpicLoot Stellarwhims Nerfs](https://valheim.thunderstore.io/package/Stellarwhims/EpicLoot_Stellarwhims_Nerfs/)

		1.3.8:

				- removed antler pickaxe from loot table. this shouldn't drop as it is 
				  core to teaching new players how gating can work in the game through crafting.
				- fixed monster specific loot not dropping.
				- moved serpent scale shield to only drop from serpent.
				- legendary mats should start dropping off 2 star mistlands creatures now.
  
		1.3.7:

				- final tuning candidate 6

		1.3.6:

				- updates and modifications for EL 0.9.3 release

		1.3.5:

				- monster specific gear ( ex: troll / fenring ) drop chances adjusted
				- low level greyling magic dust drop chances increased

		1.3.4:

				- final tuning candidate 5

		1.3.3:

				- minor changes to correctly tell EL that a star level has zero chance of dropping when appropriate.

				- increased greyling magic dust drop chance for star levels 0 - 2

				- adjust various boss' legendary drop chance. generally, the farther you are progressed in bosses, the better legendary drop chances will be.

		1.3.2:

				- moved frostner to only drop from moder

				- moved fenrir claw to only drop from fenrir cultists

				- moved fenrir armor and helm to only drop from fenrir cultists

				- moved root armor to only drop from abomination

				- moved troll armor to only drop from trolls

		1.3.1:

				- fixed json errors

		1.3.0:

				- Mistlands compatability

				- final tuning candidate 4

				- removed iteminfo.json from this mod as it no longer needs changes

		1.2.7:

				- final tuning candidate 3

				- added fenring cultst and ulv to epicloot loot tables

		1.2.6:

				- forgot to update some readme file text.

				- updated dll process filter.

		1.2.5:

				- added Growth and Abomination to the loot tables.

				- added crystal battleaxe, silver knife, bone tower shield, and iron buckler to the loot tables

				- updated this goes here copy operation

		1.2.3 - 1.2.4:

				- re-arranged mob tiers to correspond to general biomes encountered.

				- brought item drops back for high difficulty mobs.

				- updated this goes here mod operation.

				- removed stagbreaker from the regular mob loot tables (can still be crafted & enchanted)

		1.2.2: 

				- i learned markdown stuffs! =D

		1.2.1: 

				- formatted readme code example for read-ability.

		1.2.0: 

				- added an empty dll as a version check for connecting clients to help ensure loottables are synced.

		1.1.9: 

				- final tuning candidate 2

		1.1.8: 

				- final tuning candidate 2

		1.1.7: 

				- edited manifest json. it incorrectly suggested there were manual steps required.

		1.1.6: 

				- final tuning candidate 1

		1.1.5: 

				- difficulty testing.  Kill skeletons with larger groups for higher tier weapons. This will go away.

		1.1.3: -> 1.1.4 

				- difficulty testing. Kill skeletons with larger groups for higher tier weapons. This will go away.

		1.1.2: 

				- intial upload ... and learning how the upload package works. first time using thunderstore.

</details>

## dll code example if included

```
using BepInEx;
using Debug = UnityEngine.Debug;

namespace EpicLoot_Stellarwhims_Loottables_versionverify
{
    [BepInPlugin("stellarwhims.SwhimsELVerify", "Stellarwhims EpicLoot Loottables", "1.3.8")]
    [BepInProcess("valheim.exe")]
    [BepInProcess("valheim_server.exe")]

    public class SwhimsELVerify : BaseUnityPlugin
    {

        void Awake()
        {
            Debug.Log("Stellarwhims EpicLoot Loottables installed!");


        }

    }
}
```

