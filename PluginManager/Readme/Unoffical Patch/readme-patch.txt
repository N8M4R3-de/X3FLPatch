=============================================
Script:		Unofficial Patch
Created:	14/03/2026
Version:	1.3.20
Author:		Cycrow
Game:		X3: Farnham's Legacy 1.3
=============================================

Installation:

Install via the Plugin Manager


Introduction:

This is an Unofficial patch that adds a number fixes and improvements to the base game


Fixes:
Fixed Negative shares being bought at stock exchanged
Fixed freeze in collect marines job
Fixed HephCorp jump beacon ship being captured
Fixed text in ship browser (steering)
Fixed Jump Beacon price
Fixed trade distribution stock command to use destination amounts
Fixed trade distribution fill command to correctly wait
Fixed Mercury SuperFreighter hull value
Fixed collector achievements
Fixed adding additional resupply wares
Fixed Master Collector working locally
Fixed drone spawning position when ejecting drones
Fixed Fleet commands showing correctly
Fixed memory leak in dead agents
Fixed Asteroid in Complex Planner that no longer exist
Fixed Sneaky Acheivement
Fixed illegal Scans
Fixed freeze in Best Buy/Sells menu
Fixed ships with large ships docked from traveling through gates
Fixed Factory colour toggle
Fixed passenger status when ejecting/recollecting
Fixed space suits trying to go to enemy stations (ie Xenon Stations)
Fixed DockTrader job moving between sectors correctly
Fixed corporations loosing main race licences
Fixed Discovery points text display in player info menu
Fixed pirate bases relocating to inaccessable sectors
Fixed scavenger ships trying to goto inaccessable pirate bases
Fixed disbanding of wings
Fixed jumps display in factory trade menu
Fixed Station Manager when home sector is blacklisted
Fixed applying upgrades from HQ loadouts
Fixed Merchants using incorrect wares
Fixed pack station command when moving freight via drones
Fixed returning wares when deploying a packed station
Fixed move through gate command while docked
Fixed HEPT showing up in Station section (Freight Exchange)
Fixed text error in Flight School Tutorial
Fixed shields in starting mine (Nividium Miner)
Fixed resupply amount display (Additional Resupply)
Fixed station manager fuel resupply amount
Fixed account transaction over 2 billion
Fixed account transaction report displaying negative large numbers
Fixed station manager attempting to get resources above HQ Maximum settings
Fixed missing relay becon blueprint on Pirate Courior start
Fixed owner check in auto mining script
Fixed Mission Built Solar Powerplants primary/secondary resource
Fixed wares with no price showing in Networth Menu
Fixed Networth displaying deployable wares (Satellites, Lasertowers, etc)
Fixed Sell at Station menu option for Best Sells menu
Fixed Trade Reports showing weapon
Fixed Trade report showing correct value when equipping multiple ships
Fixed Terran TS ship selection for missions (Hayabusa, Mercator)
Fixed assination missions for Darkspace
Fixed removing ships from repair queue
Fixed HQ Repair from removing some ship settings
Fixed HQ Loadouts for Resupply Fuel
Fixed hq info display for stations
Fixed taxi jobs from using invalid races for passengers
Fixed destination stations for Corporation passenger transport missions
Fixed Hired TL from not undocking after leaving your service
Fixed move to coordinates command invalid input
Fixed ejected suits idling after buying used ships
Fixed clicking tabs in script editor menu
Fixed Xtreme tour of a life time mission
Fixed local trader range selection display
Fixed drones clearing command when docking at Drone Carrier
Fixed jumping out of gateless sectors
Fixed mission ships attempting to repair off course
Fixed loading of additional conversations files
Fixed script command, remove all wrecks
Fixed height of comm window
Fixed SIGNAL_ATTACKED from repeating
Fixed mission ships fleeing
Fixed Autopilot: Collect on astronauts
Fixed Argon stations in Split space
Fixed blank message in station building service
Fixed readtext error in station building service
Fixed plot mission givers being hidden
Fixed Salvage Insurance showing in Freight Bay
Fixed Station Manager repairing ships at HQ
Fixed local Stock Exchange
Fixed missions in Omicron Lyrae Beta
Fixed pirate base price
Fixed cycle tab in sector menu
Fixed Frieght Transfer via Drones, target and source ship being the same
Fixed mouse scrolling in some menus
Fixed selection of homebase in Fetch/Deliver commands
Fixed Defend Station fleet command menu
Fixed explorer points being added to sectors
Fixed target race display in mission briefings
Fixed custom menu info lines, colours split across lines
Fixed custom menu formatted info line columns
Fixed notoriety between races
Fixed requirements display in deliver ship missions
Fixed requirements display in build station missions
Fixed Terran Orbital Laser/Fusion beam factory in complex building placement
Fixed station manager going to wrong supply stations
Fixed some hardcoded texts
Fixed loading additional text files upon game start
Fixed Friend relations between races when loading save game from older versions
Fixed encyclopedia description scroll to top on selection change
Fixed Dukes being enemy with NMMC
Fixed docking slot of newly bought ship
Fixed shipyard display for stations in ships cargo
Fixed mouse switching ship type in carrier management
Fixed mouse switching values in reports menu
Fixed camera drone spawning
Fixed encyclopaedia new status when viewing page
Fixed fly through gate command on spacesuits
Fixed tab hotkey in Best Buys/Best Sells menu
Fixed mouse selecting values in Best Buys/Best Sells menu
Fixed MK3 Trader installing jumpdrive kits
Fixed Mission Director to use any minerals (create asteroid)
Fixed dormant jobs
Fixed Activate Turbo Booster Hotkey
Fixed displaying of pilots in my property (when scrolling)
Fixed default weapon masks for ships (Khaak)
Fixed repairing ship in headquarter losing some settings
Fixed sector selection (core/border) in MD
Fixed crash in applying loadouts via carrier management
Removed debug messages in dukes boarding scripts
Remove Goner Aran from unfocussed sector
Limited factory serial to omega

Improvements:
Improved spawning location for corporation ships
Improved LT/UT global blacklist handling
Improved station manager handling of blacklisted sectors
Increased respawn timer for Xenon Incursions
Improved extending of existing complexes (Build MK3)
Improved enemy race selection for assination missions
Improved ship type selection for missions
Improved turret scripts
Improved station manager ship protection
Improved station manager use of emergency jump
Improved consuming of dock and secondary wares
Improved forced pirate enemies
Improved command info text for Station Manager and Account Transfer
Improved Purging old mission actors
Improved Wing Command: Protect, input menu
Improved assassination mission jumping out claimed ships
Allowed removing homebase in Trade Distrubution Run
Adjusted production count of various weapons
Adjusted Discovery/Special Discvoery/Journal to show no price
Adjusted Trade missions to work with any ship
Added Transporter device to Dukes HQ
Added Transfer Freight menu to player stations (Split from Adjust Station Parameters)
Added option to Disable SETA Safeties
Added hired TL option to pack your stations
Added Notification – Ship Attacked
Added Notification – Ship Killed
Added Notification – Station Attacked
Added Notification – Station Killed
Added setting to disable HQ Notifications
Added setting to disable factory colouring
Added Hotkey: Toggle Turbo Booster
Added notority bar to station encyclopedia page
Added Cargo bay full text in trade menu
Added Payment/Honour for releasing passengers at Goner Temple
Added Unfocussed Jumpdrive
Added “Has Blueprint” to station/ship info
Added Save game count statastic
Added additional game tips
Added Strip Ship option in HQ Docked ship control
Added stripping of ship when recycling or reverse engineering
Added saving/loading to Custom Start Dialog
Added sector/galaxy hotkeys to Owned Ship list menu
Added Auto setting for individual races in Global Blacklist
Added Global option for disabling station colouring (Graphics Options)
Added News count to Encyclopedia sidebar entry
Added total ware cost for each ware in barter menu
Added Property menu filter: Factories
Added Property menu filter: Ships managed by homebase
Added External factories/complexes in complex planner
Added headquarters queue options to ship context menu while docked
Added stations to recycleable list in HQ info menu
Added Jumpdrive from gate/beacon context menu
Added Collect ware from flying ware context menu
Added Build station missions to corporations
Added station defence missions available to Darkspace Corporation
Added list of requirements on mission briefings
Added Sector Colour to property owned menu
Added pirate docks avaialble for sale at pirate shipyards
Added option to reload external script files in Script Editor
Added Autopilot: Collect, to astronauts/marines
Added Plot Assistance (Plot Guide for new players)
Added additional help items to Encyclopedia
Added switch tab hotkey (default: Tab)
Added Buy/sell/equip filter to trade menu in Docks
Added custom start file selection when loading
Added Hyperlinks to Mission Briefing requirements
Added more missions to corporations & pirates
Added requirements/details to more mission briefings
Added Captial Worlds status
Added additional info for Discovery Points
Added Resources/Products to docks
Added Homebase setting to Huge Ships
Added sector/galaxy hotkey to marines/pilots in personal tab (My Properties)
Added additional ship types to custom start (Kogarasu Maru)
Added playership docking on NPC carriers
Added Fighter Drone MK2 to more docks
Saved open status in encyclopaedia
Added Autopilot: Fly to command to asteroid context menu
Added per unit price on account transaction for trades
Added item counts to encyclopaedia sub groups
Added numeric seperators to Transaction log (Buying/Selling)
Added audio verbose description in galaxy map (sector description)
Prevented station rebuild in sectors with ownership change
Removed price display for some wares (Quantum Processor/Focus Crystal)

EXPERIMENTAL: Adjusted notoriety levels

Additions:
New Game Start – ATF Enforcer
New Game Start – OTAS Technitian
New Game Start – Pirate Courier
New Race – Darkspace
New Sector – Terran Unknown Sector (Darkspace)
New Ship Command – Upgrade factories (TL)
Sector Music Control – Change the music track of claimed sectors

Scripting/Modding:
Fixed custom ship commands displaying info correctly
Fixed Custom trade bar clicking beyond min/max (script menus)
Fixed custom menus return value when opening context menus
Fixed script command: get all ship types
Fixed script command: get docking port class string
Fixed script command: loadout resupply settings
Fixed hidden wares in asteroids
Fixed script SIGNAL_OWNERCHANGED old owner parameter for station
Fixed custom object context, “ishidden” arguments
Fixed missing “Select Agent” in script editor (Script Editor)
Fixed XML Data handling for integers (Script Editor)
Fixed command, destroy object: killer
Fixed script engine version (increased)
Fixed unregister god event script commands
Fixed Merge/Clone table script commands
Fixed get tasks commands to adjust the correct task number (task – 1)
Fixed custom menu formatted info line columns
Fixed custom menu info lines, colours split across lines
Fixed Race limited weapons in loadouts
Fixed Displaying of enemy ships when opening sector map from scripts
Fixed HasFreeDockPort script command
Fixed hyperlinked info line displaying twice
Fixed some script commands (laser/bullet stats)
Fixed script command, Get Faces
Fixed custom upgrades for certain ship types
Improved custom object context menu handling
Improved display of custom mneu hyperlinked info text
Improved display of race limited weapons in ship info
Adjust SignalCreated to also run after initilisation (first argument is boolean for before and after init)
Added script command: Split string by width
Added additional sections for custom object context menu items
Added patch_global file for adjustable patch settings
Added number of marines per boarding pod to patch_global
Added new constants, RaceFlg.Inactive, MEvent.TradeFull, MEvent.TradeEmpty, PlotFlags
Added control over race faces
Added Collision Warn ship signal
Added “galaxy.all.initplayership” for custom galaxies
Added “Jobs.all” and “JobWings.all” for custom galaxyies
Added Events to sectors (SetOwner, Claimed, Activated, Deactived)
Added Dock and Secondary ware consumtion rate to patch_globals
Added additional sector info script commands
Added additional object info to work with ships
Added race restrictions to laser compatibility
Added delay to scripted comm’s question
Added patch_global to suppress modified message
Added dynamic race corporation modifier
Added production modifiers to sector
Added sector race override (display only)
Added lasermasks to patch_globals (for default loadouts)
Added override controls for race limited weapons
Added no energy jump flag to jump command
Added generic beacon/satellite class
Added Fighter/Freight classes to MD shiptype class
Added force docking flag to MD
Added always allowing comms to MD (even if enemy)
Added setting attacked reponse in MD
Added client state (“nojumpdrive”) to MD
Added jumping out animation to MD warp object command
Added SG_SCRIPT_EDITOR to patch_global (for automatically enabling script editor)
Added option to reload external script files in Script Editor
Added Custom option selections (add options to gameplay options menu)
Added object info menu overrides
Added key id to register hotkey commands (for fixed position hotkeys)
Added HullShield ware to patch globals
Added face display to custom Comms
Added custom sidebar entries for different submenus
Added change_player_ship to MD
Added change_player_turret to MD
Added show_effect to MD
Added movie_finished event cue to MD
Added “reset” to alter_sector MD
Removed debug from station manager
Adjusted get ship base cost to include price variation

Added new script commands:
	<RetVar=> split string: <Var/String>, to width: <Var/Number>
	add object context entry: id=<Var/String>, class=<Var/ObjClass>, icon=<Var/Number>, pageid=<Var/Number>, textid=<Var/Number>, script=<Script>, type=<Var/Number>
	add object context entry: id=<Var/String>, class=<Var/ObjClass>, icon=<Var/Number>, pageid=<Var/Number>, textid=<Var/Number>, scriptname=<Var/String>, type=<Var/Number>
	<RetVar=> get true race blacklist: race=<Var/Race>
	<RetVar=> get global friend/foe race blacklist: race=<Var/Race>
	<RetVar=> get start day
	<RetVar=> set start day
	<RetVar=> get player marines
	<RetVar=> get player marines: in space, addto=<Var/Table>
	<RetVar=> get player marines: boarding, addto=<Var/Table>
	<RetVar=> get player marines: on ships, addto=<Var/Table>
	<RetVar=> get player marines: on stations, addto=<Var/Table>
	<RetVar=> get player pilots
	<RetVar=> get player marines: in training, addto=<Var/Table>
	<RetVar=> get player marines: waiting pickup, addto=<Var/Table>
	<RetVar=> <RefObj-> is stationary flagged
	<RefObj-> set stationary flag: <Var/Boolean>
	<RetVar=> exponential interpolation: x1=<Var/Number>, x2=<Var/Number>, y1=<Var/Number>, y2=<Var/Number>, value=<Var/Number>
	<RetVar=> logarithmic interpolation: x1=<Var/Number>, x2=<Var/Number>, y1=<Var/Number>, y2=<Var/Number>, value=<Var/Number>
	<RetVar=> <RaceObj-> is race active
	<RetVar=> <RaceObj-> does race have enconomy
	<RetVar=> <RaceObj-> is organised race
	<RaceObj-> clear all race threats
	<RetVar=> <RaceObj-> is race piloted
	<RetVar=> <RaceObj-> is pirate race
	<RetVar=> <RaceObj-> can race have marines
	<RetVar=> <RaceObj-> is fixed notority race
	<RetVar=> <RaceObj-> is XUniverse race
	<RetVar=> <RaceObj-> is terran race
	<RetVar=> <RaceObj-> is aggressive race
	<RetVar=> <RaceObj-> is default race
	<RetVar=> <RaceObj-> is race pilot sub race
	<RetVar=> <RaceObj-> is NPC race
	<RetVar=> <RaceObj-> is player race
	<RetVar=> <RaceObj-> is non talking race
	register god event script: script=<Script>, prio=<Var/Number>
	unregister god event script: script=<Script>
	register god event script: scriptname=<Var/String>, prio=<Var/Number>
	unregister god event script: scriptname=<Var/String>
	<RetVar=> <RaceObj-> should corporation use speaker race
	<RaceObj-> set should corporation use speaker race: <Var/Boolean>
	<RaceObj-> set corporation speaker race: <Var/Race>
	<RaceObj-> set corporation connected race: <Var/Race>
	add custom upgrade: ware=<Var/Ware>, shiptype=<Var/ShipType>
	add custom drone: ware=<Var/Ware>, shiptype=<Var/ShipType>, default command=<Var/ShipCommand>
	remove custom upgrade: ware=<Var/Ware>
	write to player logbook: type=<Var/Number>, text=<Var/String>
	<RetVar=> <HQ-> get HQ blueprint time: ware=<Var/Ware>, only available=<Var/Boolean>
	<RetVar=> <HQ-> get HQ blueprint product count: ware=<Var/Ware>
	<RetVar=> <HQ-> get HQ blueprint count: ware=<Var/Ware>
	<RetVar=> <HQ-> get HQ recyclable objects: include queued=<Var/Boolean>
	<RetVar=> <HQ-> get HQ recyclable stations: include queued=<Var/Boolean>
	<RetVar=> is race blacklist automatic
	<RetVar=> <Station-> get dock true products table
	<RetVar=> <Station-> get dock true resources table
	<RetVar=> <Station-> get dock true tradeables table
	<RetVar=> <Station-> get dock storage wares
	<RetVar=> <Station-> get dock storage wares table
	<RetVar=> <Passenger-> is passenger a pilot
	<RetVar=> <Passenger-> get marine status: as string=<Var/String>
	<RetVar=> get fleet leader count
	<RetVar=> get fleet ships count
	<RetVar=> get all fleet leaders
	add ware deployment: ware=%0, script=<Script>
	add ware deployment: ware=%0, scriptname=<Var/String>
	<RetVar=> get ware deployment script: ware=<Var/Ware>
	<RetVar=> <Sector-> get sector colour
	<Sector-> set sector colour: <Var/Number>
	<RetVar=> get real time
	<Sector-> clear sector objects
	<Sector-> remove sector wreck: <Var/Wreck>
	load universe map: <Var/String>
	<RefObj-> set override comm range: <Var/Number>
	<RetVar=> %0get override comm range
	<Sector-> set sector text id: <Var/Number>
	<Sector-> set sector description id: <Var/Number>
	<Sector-> clear all wrecks
	<RetVar=> <Sector-> has sector fog of war
	<Sector-> set sector fog of war: <Var/Boolean>
	<RetVar=> <Sector-> is sector always jumpable
	<Sector-> set sector always jumpable: <Var/Boolean>
	add script selection option: name=<Var/String>, pageid=<Var/Number>, textid=<Var/Number>, options=<Var/Array>, default=<Var/Number>
	add script selection option: name=<Var/String>, pageid=<Var/Number>, textid=<Var/Number>, options=<Var/Array>, default=<Var/Number>, callback script=<Script>
	remove script selection option: name=<Var/String>
	<RetVar=> get script selection value: name=<Var/String>
	<RetVar=> get all script selection options
	set script selection option: name=<Var/String>, value=<Var/Number>
	add script selection option: name=<Var/String>, pageid=<Var/Number>, textid=<Var/Number>, options=<Var/Array>, default=<Var/Number>, callback scriptname=<Var/String>
	add object info menu: class=<Var/ObjClass>, script=<Script>, prio=<Var/Number>
	add object info menu: class=<Var/ObjClass>, scriptname=<Var/String>, prio=<Var/Number>
	remove object info menu: class=<Var/ObjClass>, script=<Script>
	remove object info menu: class=<Var/ObjClass>, scriptname=<Var/String>
	<RetVar=> get files in directory: <Var/String> search pattern=<Var/String>
	<RetVar=> get random face: race=<Var/Race>, subrace=<Var/Race>, female=<Var/Boolean>
	<Race->add face: id=<Var/Number>, female=<Var/Boolean>, subrace=<Var/Race>
	<Race->remove face: id=<Var/Number>, female=<Var/Boolean>, subrace=<Var/Race>
	<RetVar=> <Race->get faces: female=<Var/Boolean>, subrace=<Var/Race>
	<RetVar=> <Race->get face from id: <Var/Number>, female=<Var/Boolean>, subrace=<Var/Race>
	<RetVar=> <Var/Number> << <Var/Number>
	<RetVar=> <Var/Number> >> <Var/Number>
	<RetVar=> get matrix from angles: alpha=<Var/Number>, beta=<Var/Number>, gamma=<Var/Number>
	<RetVar=> get angles from vector: x=<Var/Number>, y=<Var/Number>, z=<Var/Number>
	<RetVar=> get angles from matrix: <Var/Array>
	<RetVar=> matrix multiple: <Var/Array> * <Var/Array>
	<RetVar=> matrix multiple inverse: <Var/Array> * <Var/Array>
	<RetVar=> rotate vector: <Var/Array>, alpha=<Var/Number>, beta=<Var/Number>
	<RetVar=> rotate vector inverse: <Var/Array>, alpha=<Var/Number>, beta=<Var/Number>
	<RetVar=> <Sector->is capital sector
	<Sector->set capital sector: <Var/Boolean>
	<RetVar=> <Sector>has sector additional info
	<Sector>add sector additional info: id=<Var/String>, title=<Var/String>, data=<Var/String>
	<Sector>add sector additional info: id=<Var/String>, title page=<Var/Number>, title id=<Var/Number>, data page=<Var/Number>, data id=<Var/Number>
	<RetVar=> <Sector>get sector additional data
	<RetVar=> <Sector>get sector additional data title: id=<Var/String>
	<RetVar=> <Sector>get sector additional data text: id=<Var/String>
	<Sector>remove sector additional data: id=<Var/String>
	<RetVar=> get ware description: ware=<Var/Ware>
	remove god proposed station: id=<Var/Number>
	add laser restriction: laser=<Var/Laser>, race=<Var/Race>
	remove laser restriction: laser=<Var/Laser>, race=<Var/Race>
	clear laser restrictions: laser=<Var/Laser>
	<RetVar=> get laser restrictions: laser=<Var/Laser>
	<RetVar=> is laser restricted: laser=<Var/Laser>, race=<Var/Race>
	<RetVar=> can ship type install laser: shiptype=<Var/ShipType>, laser=<Var/Laser>, turret=<Var/Number>
	<RetVar=> get system time
	<RetVar=> get custom ranks: sorted=<Var/Boolean>
	<RetVar=> get mission ranks
	set custom rank: id=<Var/String>, name page=<Var/Number>, name id=<Var/Number>, title page=<Var/Number>, title id=<Var/Number>, percent=<Var/Number>
	set custom rank: id=<Var/String>, name=<Var/String>, title=<Var/String>, percent=<Var/Number>
	<RetVar=> get custom rank string: id=<Var/String>
	<RetVar=> get custom rank name: id=<Var/String>
	<RetVar=> get custom rank title: id=<Var/String>
	<RetVar=> get custom rank percent: id=<Var/String>
	<RetVar=> set allow player docking: <Var/Boolean>
	<RetVar=> <Ship>is allow player docking
	remove custom rank: id=<Var/String>


Changelog:

1.3.2:
	Fixed disbanding of wings
	Fixed jumps display in factory trade menu
	Fixed Station Manager when home sector is blacklisted
	Fixed applying upgrades from HQ loadouts
	Fixed Merchants using incorrect wares
	Fixed pack station command when moving freight via drones
	Fixed returning wares when deploying a packed station
	Fixed custom object context, "ishidden" arguments
	Improved station manager handling of blacklisted sectors
	Improved custom object context menu handling
	Added Transfer Freight menu to player stations (Split from Adjust Station Parameters)
	Added option to Disable SETA Safeties
	Added hired TL option to pack your stations
	Added script command: Split string by width
	Added additional sections for custom object context menu items
	Added Notification - Ship Attacked
	Added Notification - Ship Killed
	Added Notification - Station Attacked
	Added Notification - Station Killed
	Added setting to disable HQ Notifications
	Added setting to disable factory colouring
	Sector Music Control - Change the music track of claimed sectors

1.3.3:
	Fixed freeze in Best Buy/Sells menu
	Fixed ships with large ships docked from traveling through gates
	Fixed Factory colour toggle
	Fixed passenger status when ejecting/recollecting
	Fixed space suits trying to go to enemy stations (ie Xenon Stations)
	Removed debug from station manager
	Removed price display for some wares (Quantum Processor/Focus Crystal)
	Added Hotkey: Toggle Turbo Booster
	Added notority bar to station encyclopedia page
	Added Cargo bay full text in trade menu
	Added Payment/Honour for releasing passengers at Goner Temple
	Added Unfocussed Jumpdrive
	New Ship Command - Upgrade factories (TL)

1.3.4:
	Fixed move through gate command while docked
	Fixed disable hq queue message menu display
	Fixed missing "Select Agent" in script editor (Script Editor)
	Fixed XML Data handling for integers (Script Editor)
	Fixed HEPT showing up in Station section (Freight Exchange)
	Fixed text error in Flight School Tutorial
	Added patch_global file for adjustable patch settings
	Added number of marines per boarding pod to patch_global
	Added "Has Blueprint" to station/ship info
	Added Save game count statastic
	Added additional game tips
	Added Strip Ship option in HQ Docked ship control
	Added stripping of ship when recycling or reverse engineering
	Added saving/loading to Custom Start Dialog
	Added sector/galaxy hotkeys to Owned Ship list menu
	Added Auto setting for individual races in Global Blacklist
	Added Global option for disabling station colouring (Graphics Options)
	Added News count to Encyclopedia sidebar entry
	Added total ware cost for each ware in barter menu
	Added Property menu filter: Factories
	Added Property menu filter: Ships managed by homebase
	Added External factories/complexes in complex planner
	Improved extending of existing complexes (Build MK3)
	Allowed removing homebase in Trade Distrubution Run

1.3.5:
	Added headquarters queue options to ship context menu while docked
	Added stations to recycleable list in HQ info menu
	Added Jumpdrive from gate/beacon context menu
	Added Collect ware from flying ware context menu
	Added Build station missions to corporations
	Added station defence missions available to Darkspace Corporation
	Added list of requirements on mission briefings
	Added pirate docks avaialble for sale at pirate shipyards
	Adjusted Discovery/Special Discvoery/Journal to show no price
	Improved enemy race selection for assassination missions
	Improved ship type selection for missions
	Fixed station manager attempting to get resources above HQ Maximum settings
	Fixed missing relay becon blueprint on Pirate Courior start
	Fixed owner check in auto mining script
	Fixed Mission Built Solar Powerplants primary/secondary resource
	Fixed wares with no price showing in Networth Menu
	Fixed Networth displaying deployable wares (Satellites, Lasertowers, etc)
	Fixed Sell at Station menu option for Best Sells menu
	Fixed Trade Reports showing weapon
	Fixed Trade report showing correct value when equipping multiple ships
	Fixed Terran TS ship selection for missions (Hayabusa, Mercator)
	Fixed assassination missions for Darkspace
	Fixed removing ships from repair queue
	Fixed HQ Repair from removing some ship settings
	Fixed HQ Loadouts for Resupply Fuel
	Fixed hq info display for stations
	Fixed taxi jobs from using invalid races for passengers
	Fixed destination stations for Corporation passenger transport missions
	Fixed Hired TL from not undocking after leaving your service
	Fixed move to coordinates command invalid input
	Fixed ejected suits idling after buying used ships
	Fixed clicking tabs in script editor menu
	Fixed Xtreme tour of a life time mission
	Fixed local trader range selection display
	
	Scripting/Modding
	Added new constants, RaceFlg.Inactive, MEvent.TradeFull, MEvent.TradeEmpty, PlotFlags
	Fixed command, destroy object: killer
	Added new script commands


1.3.6:
	Fixed unregister god event script commands
	Fixed script engine version (increased)
	Fixed drones clearing command when docking at Drone Carrier
	Fixed jumping out of gateless sectors
	Fixed mission ships attempting to repair off course
	Added Sector Colour to property owned menu
	Added additional script commands
	
1.3.7:
	Added force docking flag to MD
	Added always allowing comms to MD (even if enemy)
	Added setting attacked reponse in MD
	Added client state ("nojumpdrive") to MD
	Added jumping out animation to MD warp object command
	Added SG_SCRIPT_EDITOR to patch_global (for automatically enabling script editor)
	Added option to reload external script files in Script Editor	Improved forced pirate enemies
	Added Autopilot: Collect, to astronauts/marines
	Adjusted production count of various weapons
	Improved turret scripts
	Improved station manager ship protection
	Improved station manager use of emergency jump
	Improved consuming of dock and secondary wares
	Fixed loading of additional conversations files
	Fixed script command, remove all wrecks
	Fixed height of comm window
	Fixed SIGNAL_ATTACKED from repeating
	Fixed mission ships fleeing	

1.3.8:
	Fixed Autopilot: Collect on astronauts
	Fixed Argon stations in Split space
	Fixed blank message in station building service
	Fixed readtext error in station building service
	Fixed plot mission givers being hidden
	Added Plot Assistance (Plot Guide for new players)
	Added Custom option selections (add options to gameplay options menu)
	Added object info menu overrides
	Added additional help items to Encyclopedia
	Added switch tab hotkey (default: Tab)
	Added key id to register hotkey commands (for fixed position hotkeys)
	Added Buy/sell/equip filter to trade menu in Docks
	Added custom start file selection when loading
	
1.3.9:
	Fixed Salvage Insurance showing in Freight Bay
	Fixed Station Manager repairing ships at HQ
	Fixed local Stock Exchange
	Fixed missions in Omicron Lyrae Beta
	Added Hyperlinks to Mission Briefing requirements
	Added more missions to corporations & pirates
	Added requirements/details to more mission briefings
	Added Captial Worlds status
	Added additional info for Discovery Points
	Adjusted Trade missions to work with any ship
	Improved command info text for Station Manager and Account Transfer
	
	Scripting/Modding:
	Fixed Merge/Clone table script commands
	Added control over race faces
	Added Collision Warn ship signal
	Added "galaxy.all.initplayership" for custom galaxies
	Added "Jobs.all" and "JobWings.all" for custom galaxyies
	Added Events to sectors (SetOwner, Claimed, Activated, Deactived)
	Added Dock and Secondary ware consumption rate to patch_globals
	Adjust SignalCreated to also run after initilisation (first argument is boolean for before and after init)
	
1.3.10:
	Fixed Captial world status (Argon Prime + Earth)
	Fixed Cargo delivery missions
	Fixed shields in starting mine (Nividium Miner)
	Fixed resupply amount display (Additional Resupply)
	Fixed station manager fuel resupply amount
	Fixed account transaction over 2 billion
	Fixed account transaction report displaying negative large numbers
	Improved Purging old mission actors
	EXPERIMENTAL: Adjusted notoriety levels
	Adjusted Darkspace Rank names
	
	Scripting/Modding:
	Adjusted get ship base cost to include price variation
	
1.3.11:
	Fixed get tasks commands to adjust the correct task number (task - 1)
	Fixed pirate base price	
	Fixed cycle tab in sector menu
	Fixed Frieght Transfer via Drones, target and source ship being the same
	Fixed mouse scrolling in some menus
	Fixed selection of homebase in Fetch/Deliver commands
	Fixed Defend Station fleet command menu
	Fixed explorer points being added to sectors
	Improved display of custom mneu hyperlinked info text
	Improved Wing Command: Protect, input menu
	Added Resources/Products to docks
	Added Homebase setting to Huge Ships
	Added sector/galaxy hotkey to marines/pilots in personal tab (My Properties)
	Added additional ship types to custom start (Kogarasu Maru)
	Added additional sector info script commands
	Added additional object info to work with ships
	Added race restrictions to laser compatibility	
	Added playership docking on NPC carriers
	Added delay to scripted comm's question
	Added patch_global to suppress modified message
	
1.3.12:
	Fixed target race display in mission breifings
	Fixed custom menu info lines, colours split across lines
	Fixed custom menu formatted info line columns
	Fixed notoriety between races
	Added dynamic race corpoation modifier
	
1.3.13:
	Fixed requirements display in deliver ship missions
	Fixed requirements display in build station missions
	Added production modifiers to sector
	Added sector race override (display only)

1.3.14:
	Fixed Terran Orbital Laser/Fusion beam factory in complex building placement
	Fixed station manager going to wrong supply stations
	Added Fighter Drone MK2 to more docks	
	
	Added lasermasks to patch_globals (for default loadouts)
	Added override controls for race limited weapons
	Fixed Race limited weapons in loadouts
	Improved display of race limited weapons in ship info
	
1.3.15:
	Fixed "No Pilot" in neutral ships
	Fixed some hardcoded texts	
	Limited factory serial to omega

	Added no energy jump flag to jump command

1.3.16:
	Fixed energy usage for jumps
	Fixed loading additional text files upon game start
	Fixed Friend relations between races when loading save game from older versions
	Fixed encyclopedia description scroll to top on selection change
	Fixed Dukes being enemy with NMMC
	Saved open status in encyclopedia
	Added Autopilot: Fly to command to asteroid context menu
	Added per unit price on account transaction for trades
	
	Fixed Displaying of enemy ships when opening sector map from scripts
	Added generic beacon/satellite class
	Added Fighter/Freight classes to MD shiptype class
	
1.3.17:
	Fixed docking slot of newly bought ship
	Fixed shipyard display for stations in ships cargo
	Fixed mouse switching ship type in carrier management
	Fixed mouse switching values in reports menu
	Fixed camera drone spawning
	Fixed encyclopedia new status when viewing page
	Fixed fly through gate command on spacesuits
	Added item counts to encyclopedia sub groups
	
	Fixed HasFreeDockPort script command
	Fixed hyperlinked info line displaying twice
	Added HullShield ware to patch globals
	
1.3.18:
	Fixed some commands showing correctly in context menu (ie Use Jumpdrive)
	Fixed some script commands (laser/bullet stats)
	Fixed tab hotkey in Best Buys/Best Sells menu
	Fixed mouse selecting values in Best Buys/Best Sells menu
	Fixed MK3 Trader installing jumpdrive kits
	Fixed Mission Director to use any minerals (create asteroid)
	Fixed dormant jobs
	Added numeric separators to Transaction log (Buying/Selling)
	Added audio verbose description in galaxy map (sector description)
	Added face display to custom Comms	
	Prevented station rebuild in sectors with ownership change

1.3.19:
	Fixed Activate Turbo Booster Hotkey
	Fixed displaying of pilots in my property (when scrolling)
	Fixed default weapon masks for ships (Khaak)
	Fixed repairing ship in headquarters losing some settings
	Fixed sector selection (core/border) in MD
	Fixed crash in applying loadouts via carrier management
	Improved assassination mission jumping out claimed ships
	Remove Goner Aran from unfocussed sector
	
	Fixed script command, Get Faces
	Fixed custom upgrades for certain ship types
	Added custom sidebar entries for different submenus
	Added change_player_ship to MD
	Added change_player_turret to MD
	Added show_effect to MD
	Added movie_finished event cue to MD
	Added "reset" to alter_sector MD
	
1.3.20:
	Fixed Return Wares mission
	Fixed hyperlink highlighting correct position due to word wrap
	Added some descriptions for Drone Carrier commands
	Drone Carrier repair targets interrupt current task to stop in space until repaired (non-player owned ships only).
	Drones of killed NPC Drone Carriers will now do [COMMAND_DESTROY_THIS] to avoid clogging universe.
	Drone Carrier command 'Repair station with drones'
	  Improved selection of ship/station and wording of command text
	  Nearest ship/station selector filters out undamaged objects.
	  Nearest ship filters out drones already in space.
	Fixed Drone Carrier automatic self repair getting stuck in a loop of docking and undocking
	Drone Carrier 'Scan asteroids with drones' command
	  Fixed bugging out where drones wouldn't undock.
	  Drones will scan asteroids discovered after flying to already known asteroids.
	  Drone carrier will scan asteroids in range with its own mineral scanner if available
	Fixed conversion error in 'Map sector with drones' command causing small scan area.
    Drone Carrier command 'Scan ships with drones' now abandons chase if target ship has docked or escaped more than a sector away.
    Drone Carrier command 'Collect wares with drones'
      Prepared to be usable by AI owned M7Ds
      Improved CPU efficiency.
      Drones won't collect wares undiscovered by player.
    Fixed and improved Drone Carrier command 'Resupply ships with drones'
	Fixed M7D drones inability to repair huge stations in active sector
	Fixed M7D drones of NPC races being unable to repair objects of same race in active sector
	Fixed Face/Voice mismatch for speakers
	Fixed creating some missions for Goners
	Fixed player owned mercenary stations
	Fixed indestructable ships (on game load)
	Improved freight drone docking. Drone can now use "Dock at" command. Drones transfer wares to target ship or space when docking
	Added ship Ugrades to missing Corporation Docks
	Added docking lockup fix to improve ships/drones docking at carriers	
	Improved random music generator
	Improved paranid reputation diplomacy during FL plot
	Removed Build Command Software from Docks where TLs are unable to dock
	
	Fixed getConnectedRace script command
	Fixed getDialogRace script command
	Fixed is docking allowed command to work with freight drones on larger ships.
	Fixed Side Menu in custom menus overlapping monitor
	Fixed LFL event triggers in MD
	Added Fire lasers ahead script command
	Added Reset S/M/L shipyard state script command
	Increased max number of lasers per turret to 80
