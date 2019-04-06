# Fork of xerpi's ds4vita hooks branch

xerpi released an experimental ds4vita version https://github.com/xerpi/ds4vita/tree/hooks which hopefully fix the stuttering of Left analog on some games. 

This fork reverts the swapping of triggers (L1, R1, L2, R2) on line 284-294 in main.c.

**Credits:**
xerpi for their awesome plugin

**Download**: 

**Enable the plugin:**

1. Add ds4vita.skprx to taiHEN's config (ux0:/tai/config.txt):
	```
	*KERNEL
	ux0:tai/ds4vita.skprx
	```
2. You need to refresh the config.txt by rebooting or through VitaShell.

**Using it for the first time (pairing the controller):**

1. Go to Settings -> Devices -> Bluetooth Devices
2. Press SHARE+PS on the DS4 for about 3-4 seconds, until the lightbar blinks very quickly
3. The DS4 will then connect and be paired (don't press over it when it appears)

**Using it once paired (see above):**
1. Just press the PS button and it will connect to the Vita

**Note**: If you use Mai, don't put the plugin inside ux0:/plugins because Mai will load all stuff you put in there...
