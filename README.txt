If you want to contribute maps to this racing server, please ensure following conditions are met:

1. Map has entites which specify map endings. Please add entities to existing maps, before uploading!
You may use "flag" or "playerstart" entities (matter of taste). argument 2 of entity must be negative integer and specifies race win place, for example:
	/newent flag -1
	/newent playerstart -1
	/entset flag 0 -2
Argument 3 of entity specify radius. if its 0 or negative, value is ignored and default value of 24 is used. Example:
	/entset flag 0 -3 64
If win places are really big, please override default radius. You may use more than 1 entity to specify same race place too (for better precision), if you want.
Please specify all 3 race endings if they are avaiable.
Note: you may specify all 3 race endings with 1 entity. Simply specify last race ending, for example, -3. In this case,
server will allocate 3 places, and treat this entity as first place.
So, in sumrary, for first place entity: /entset flag 0 -1
In case you are too lazy to specify all race ends entities, or just want 3 race places regardless of entities: /entset flag 0 -3

2. Please don't send poor quality maps. Ensure map has enough spawnpoints to hold bigger number of players. Race end should be reachable.

3. If map has lights, you may calculate them. do "/calclight; recalc; savemap;" before uploading map here.

If you followed these rules, you may upload map to "testing" folder. This folder is anonymously writtable from FTP.
To upload files you may use windows explorer, Filezilla, command line ftp client or any ftp client of your choice.
Send only .ogz files, and don't send garbage. Map will be added to server when admin verifies that map meets prevous requirements. You may see maps at maps/ folder.
Note: on windows, saved maps are stored at My Documents\My Games\Sauerbraten\packages\base, on linux at ~/.sauerbraten/packages/base
