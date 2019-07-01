COMANGLIA FPS CONFIG UPDATED BY MASTERCOMS
//////////////////////////////////////////////////
FILES:
gfx.cfg		//normal config
toaster.cfg	//low-end PC and non-gaming laptops

HOW TO INSTALL:
drop all cfg files in \Steam\steamapps\common\Team Fortress 2\tf\cfg

open files with any text editor to edit.

edited by sage
classic comanglia but includes conservative changes
https://gist.github.com/mastercoms/f54f6476e0f2e4bdcf860ef902f1f93f

Official sage website: www.timfortress.today

!CHANGES IN TOASTER CONFIG
fps_max 150 		// Low cap to avoid overheating issues in laptops
cl_smooth 0			//tiny fps gain from non-smoothed movement
rate 50000
net_splitrate 1 	// Do not split multiple packets for bad PCs that cannot handle the extra load
mat_antialias 0		//Might cause a bug with mumble overlay
mat_filtertextures 0 
mat_specular 0
r_decals 9
r_staticprop_lod 63
snd_pitchquality 0 	//slight fps gain
snd_mixahead 0.11	//keep delay for weak processors
r_waterdrawrefraction 0



STILL HAVE LOW FPS?
-Close background aplicattions
-Lower the resolution
-Disable Steam in-game overlay
-Try dxlevel 81