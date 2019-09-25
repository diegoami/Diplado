# DIPLADO (DIPLomacy desperADO) - YET ANOTHER DIPLOMACY CLONE

Forked from 
[1.174 Updates](https://steamcommunity.com/workshop/filedetails/discussion/285119009/451850849180281143/) from May 2019.
Note that the base version has not been released from the author yet (Somebody). 

Some additions

* Can spar with your army in the arena
* Prisoners in your party do not disappear while selling those in your garrison to the constable
* No crazy charge in battle of your party (they await your orders)
* Body guards
* Import / Export companions
* Whistle for your horse (key M)
* Taunt your opponents, so that they will attack you (key O)

Also on the **development** branch

* Option to turn the hold ground command on or off
* Option to assign lord to a default group

## Binaries

Under **https://github.com/diegoami/Diplado/releases/**
**master** releases' save files are backwardly compatible, but **develop** releases may contain more interesting features.

Unzip a binary release in a new directory in the Modules directory of your Warband installation (e.g. _C:/Program Files (x86)/Steam/steamapps/common/MountBlade Warband/Modules/Diplado/_ ) 

## Credits

Many to keep track of

* the Diplomacy mod maintainers (Waihti, hessuu, fisheye, rubik, jrider, Mjollnir, Akmar Nibelung, Parsifal, Somebody) 
* and other Taleworlds  forum users: Dj_FRedy, Jinnai, lazeras, Caba`dr, Glabrezu, Efe Karaca


## Branching Policy

On **master** there should be changes which do not break compatibility with 4.3+ Steam for 1.174.

The branch **somebody_ver** at the moment tracks the official version of this mod, maintained by Somebody.

On **develop** and possibly other release branches there might be changes that will break downward compatibility with the official version. 

## COMPILING

* Set up Python 2.7 
* Make a copy of your Native Module directory
* Edit `source/module_info.py` to point of the directory of your new module
* Edit `build_module_lav.bat` to point to the location of your Python 2
* Execute `build_module_lav.bat`

