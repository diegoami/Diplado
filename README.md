# DIPLADO (DIPLomacy desperADO) 

YET ANOTHER DIPLOMACY 4.3 CLONE

## SOURCE

Forked from 
[1.174 Updates](https://steamcommunity.com/workshop/filedetails/discussion/285119009/451850849180281143/) from May 2019.
Note that the base version has not been released from the author yet (Somebody). 

__There might be serious issues in this mod, so use at your own risk__

## Installation

As described [here](https://steamcommunity.com/sharedfiles/filedetails/?id=285119009), make a copy of Modules\Native and name it Diplado or as you wish. 

Then download one of the latest release from **https://github.com/diegoami/Diplado/releases/** and extract it into said directory

**master** releases contain changes which do not break compatibility with 4.3+ Steam for 1.174, while **develop** releases contain feature that might break downward compatibility with the base version, but contain more features and life improvements.

That is why I actually work locally with two modules, _Diplado_master_ and _Diplado_develop_

## KNOWN ISSUES

* Multiplayer seems to be broken in many places


## FEATURES

Some additions

* Can spar with your army in the arena
* No crazy charge in battle of your party (they await your orders)
* Body guards
* Import / Export companions
* Whistle for your horse (key M)
* Taunt your opponents, so that they will attack you (key O)

Also on the **development** branch

* Option to turn the hold ground command on or off
* Option to assign lords to a default group

**master** releases' save files are backwardly compatible, but **develop** releases may contain more interesting features.

## Credits

Many to keep track of

* the Diplomacy mod maintainers (Waihti, hessuu, fisheye, rubik, jrider, Mjollnir, Akmar Nibelung, Parsifal, Somebody) 
* and other Taleworlds  forum users: Dj_FRedy, Jinnai, lazeras, Caba`dr, Glabrezu, Efe Karaca


## COMPILING

1. Install a release from **https://github.com/diegoami/Diplado/releases/** as described above.
2. Set up Python 2.7 
* (Optional) Edit `source/module_info.py` to point to the directory where you installed the module
* Edit `build_module_lav.bat` to point to the location of your Python 2
* Execute `build_module_lav.bat`


