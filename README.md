# Character Info Toolbox

Script to Automate KOL the Sea: Underwater Quests [KoLMafia](https://github.com/kolmafia/kolmafia).

Forked from: https://kolmafia.us/threads/thesea-ash-automated-underwater-quests.8708/

# Installation

Run this command in the graphical CLI:

```
git checkout https://github.com/rhovious/kol-thesea.git
```

Will require [a recent build of KoLMafia](https://ci.kolmafia.us/job/Kolmafia/lastSuccessfulBuild/).


# Settings & USAGE

There are a few zlib variables* you can setup:
- seafloor_bootQuest
- seafloor_monkeeQuest
- seafloor_outfitQuest
- seafloor_skateQuest
- seafloor_automateGladiators
- seafloor_buyBoot
- seafloor_buySkateMap
- seafloor_buySkateBoard
- seafloor_closetMeat
- seafloor_faxNeptune
- seafloor_getHelmet
- seafloor_getSushiMat
- seafloor_maximizeString
- seafloor_outfit
- seafloor_unlockTrophyfish
There are a few zlib variables* you should not need to setup:
- seafloor_grandpaChat
- seafloor_monkeeAscension
- seafloor_monkeeStep

*You can configure the variables above by typing zlib settingname = value in the gCLI. The script will either use the zlib setting if it has been set, or the setting you had on when you launched the script.

* Surviving combats is your responsibility. In the earlier quests, the only part where you need to actually WIN the combat is for getting the Wiggling Flytrap Pellet at the beginning. The other quest steps are all non-combats, or the items needed can be bought from the mall. For the Outfit quests, you do need to actually win... against the bosses, at least.

* Breathing underwater is your responsibility as well. Because this can be accomplished through effects or equipment, hard-coding it guarantees that people will be frustrated. Anyone can equip the makeshift SCUBA as it's a quest item received when you actually unlock the zone, but that is the option with the most penalties to item drop.

* Launch the script by typing call TheSea.ash in the gCLI.


## Historical Credits

By Theraze up to v 1.6.3 
https://kolmafia.us/threads/thesea-ash-automated-underwater-quests.8708/
