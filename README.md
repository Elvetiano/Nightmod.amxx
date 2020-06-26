# Nightmod.amxx
AmxModX 1.8.3 or higher nightmode Plugin

Night Mode plugin! Created by S3ekEr, and developed by UNU

- This is a night plugin for automated timed change servers setting!
- This plugin is compatible only with AmxModX version 1.8.3 or higher
What it does?

* pauses some plugins when night time is set and unpause them when day starts!
* Changes cvar values

	- amx_vipgold_everyone (Custom VIP plugin cvar)
	- sv_timeout (HLDS cvar)
	- sv_unlag  (HLDS cvar)
	- sv_maxunlag (HLDS cvar)
	- mp_autokick	(HLDS cvar)
	- mp_autoteambalance (HLDS cvar)
	- mp_timelimit (HLDS cvar)
*Changes server Hostname using cvar "hostname"
	-changes are made with the help of 2 files
	serverhostnamefreevip.cfg, and serverhostnameclassic.cfg
  
  Change List
  
  	- Version 1.1 
		* Last round when number of rounds meets the amx_restart_maxrounds and reload map
 
	- Version 2.0 20-06-2020
		* Added galileo to pause list
		* Added auto pausing plugins in pause list when switching to nightmode 
 
	- Version 2.0 20-06-2020
		* Added Autoexecconfig to execute own config for this plugin you can find config in (cstrike/addons/amxmodx/configs/plugins/plugin-Nightmod.cfg)
	- Version 2.0.1 26-06-2020
		* Removed some plugins from pause
