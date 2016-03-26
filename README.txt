Minetest mod: Mines (with Treasurer support)
Short name: tsm_mines
Version: 0.5

License of source code and textures: WTFPL
-----------------------------------------
Started by BlockMen in 2013.
Forked by Wuzzy later.

Contributors:
-------------
cHyper (mine deep can be set by .conf)

This program is free software. It comes without any warranty, to
the extent permitted by applicable law. You can redistribute it
and/or modify it under the terms of the Do What The Fuck You Want
To Public License, Version 2, as published by Sam Hocevar. See
http://sam.zoy.org/wtfpl/COPYING for more details.


Using the mod:
--------------
This mod adds abandoned mines in the underground.

You can find chests with different stuff like food, resources, ingots or even tools.
If you have the Treasurer mod enabled and some treasure registration mods (TRMs), you
will find stuff from other mods as well.

Remember that this mod is still in alpha stage!

Settings
--------

You can change the spawing of mines by adding/changing these values in minetest.conf
(value after equals sign is default value):

mines_deep_min = -64
	At this depth mines are created

mines_deep_max = -380
	Up to this depth mines are created

mines_spawnfactor = 1.5
	Increase this value to generate more mines
