# bgee_npc_randomiser
JP's BG:EE NPC Randomizer

This mod will modify the recruitable BG:EE companions:

- Each new game all unkitted companions will have a random kit assigned (no kit is also an option). Race, alignment and other restrictions apply for kit assignment (aka only a Dwarven Fighter can get the Dwarven Defender kit, etc.). Additionally armor or weapons that are incompatible with the new kit are removed from the inventory.
- Each new game all companions will get random proficiencies assigned. These proficiencies are completely random generated and take their current kit into account. Note that this can sometimes lead to strange combinations (only weaponstyle proficiencies for example)

For kit assignment, following npc's are taken into account:

- Ajantis -> Unkitted Paladin, Cavalier, Undead Hunter, Inquisitor
- Alora -> Unkitted Thief, Swashbuckler, Assassin, Bounty Hunter, Shadowdancer
- Eldoth -> Unkitted Bard, Skald, Blade, Jester
- Faldorn -> Unkitted Druid, Shapeshifter, Totemic Druid, Avenger
- Garrick -> Unkitted Bard, Skald, Blade, Jester
- Imoen -> Unkitted Thief, Swashbuckler, Assassin, Bounty Hunter, Shadowdancer
- Kagain -> Unkitted Fighter, Wizard Slayer, Kensai, Barbarian, Dwarven Defender
- Khalid -> Unkitted Fighter, Wizard Slayer, Kensai, Barbarian, Berserker
- Kivan -> Unkitted Ranger, Beast Master, Archer, Stalker
- Minsc -> Unkitted Ranger, Beast Master, Archer, Stalker
- Safana -> Unkitted Thief, Swashbuckler, Assassin, Bounty Hunter, Shadowdancer
- Shar-Teel -> Unkitted Fighter, Wizard Slayer, Barbarian, Berserker
- Skie -> Unkitted Thief, Swashbuckler, Assassin, Bounty Hunter, Shadowdancer

For proficiency assignment all original BG companions are included. The four BG:EE only companions are not automatically included in this release due to technical hurdles.

It seems these npcs do not "exist" at the start of the game. It is possible to randomise their proficiencies once you are in the same area with them. Following commands in the console can be used:
- Baeloth -> C:CreateCreature("JP#BAELO")
- Dorn -> C:CreateCreature("JP#DORN")
- Neera -> C:CreateCreature("JP#NEERA")
- Rasaad -> C:CreateCreature("JP#RASAA")

The in-game generation of kits and proficiencies starts when charname leaves Candlekeep and arrives in the Lion's Way area. Imoen will wait with talking to charname until the randomisation is finished. Afterwards she will come to the PC and start her normal dialogue.

**Installation**
Copy the contents of the zip folder to your Baldur's Gate Enhanced Edition folder. Run setup-bgee_npc_randomiser.exe to install via WEIDU.

**Compatibility**
I've tested the mod with a BG:EE 2.6 install combined with SCS and BG1NPC project.
In general this version of the mod will not be compatible with any mods that change the default kits/proficiencies of BG:EE companions.
This mod also alters the class script of Imoen1.cre, any mod that alters this script may break this mod.
