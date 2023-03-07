---
layout: biapage
path: help
title: Help
---

## Install

**Note**: Your installed game path is `C:\Program Files (x86)\Steam\steamapps\common\Call of Duty` if you installed via Steam or `C:\Program Files (x86)\Call of Duty` if you installed from CD.

1. Install [Call of Duty and the expansion pack United Offensive](https://store.steampowered.com/sub/222/).
2. Download [punkbuster definitions](http://www.callofdutyview.net/files/pb/cod_pb.zip), extract it and copy the pb folder over the existing pb folder in your game folder.
3. Download [pbsvc.exe](http://www.evenbalance.com/downloads/pbsvc/pbsvc.exe), run it, start the punkbuster service and perform test.
4. Start game as administrator (you will always have to do this) and enable downloads.
5. Ensure serverlist filters shows non-pure servers and servers without Punkbuster.
6. Refresh, find our server and doubleclick it! :)

Downloads:
* [Cod UO 1.51 patch](http://callofduty.filefront.com/file/Call_of_Duty_United_Offensive_151_Patch;36116)
* [CoD UO Official Map pack](http://www.gamefront.com/files/CoD_United_Offensive_Map_Pack/;3771736;;/fileinfo.html)

## Widescreen

Find and edit the following config file with notepad: uo\uoconfig_mp.cfg
All of the following commands need to be changed in the file (they are already there but with different values - if cg_fov is missing, just add it). Obviously only one of 16:9 or 16:10 needs to be done, depending on your screen. Replace 1440 and 900 with your monitor resolution (1920 and 1200 for me).

For a 16:9 Aspect Ratio Resolution: (usually for widescreen TV)</p>
```
seta cg_fov 96.4183
seta r_mode -1
seta r_customheight 900
seta r_customwidth 1440
```

For a 16:10 Aspect Ratio Resolution: (usually for widescreen pc monitor)
```
seta cg_fov 90.3951
seta r_mode -1
seta r_customheight 900
seta r_customwidth 1440
```
Once done, when you go in the game menu, it may not show the correct resolution in the options, but it will be in game. Do not change your resolution in the game. If you do, you will lose widescreen, and have to do this all over again.

## FAQ

* If PunkBuster is not running, try running the game as administrator by right-clicking on the shortcut and select "Run as administrator"
* If PunkBuster complains about files with "d3d" in their name being corrupt, reinstall [DirectX](http://www.microsoft.com/en-us/download/details.aspx?id=35).
* If PunkBuster says you<re banned, contact us on Discord. But we only remove bans, we don't whitelist. If PunkBuster doesn't like your computer, neither do we.

Some other links:
* https://answers.ea.com/t5/Battlefield-Hardline/Punkbuster-Guide/td-p/4390461
* http://www.funteamgermany.de/?path=download&contentid=21&catid=4&themeid=0

