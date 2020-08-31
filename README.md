//mHax Configuration File

//Maphack Configuration
Missile Color[Player]:   0x97
Missile Color[Neutral]:  0x0A
Missile Color[Partied]:  0x84
Missile Color[Hostile]:  0x5B

Monster Color[Normal]:   0x5B
Monster Color[Minion]:   0x60
Monster Color[Champion]: 0x91
Monster Color[Boss]:     0x84

Reveal Map:		False, None
Show Monsters:		False, None
Show Missiles:		False, None
Force Light Radius:	False, None
Remove Weather:		False, None
Infravision:		False, None
Remove Shake:		False, None
Display Level Names:	False, None
RevealMode:		0

//Skill Warnings: set true to warn when effect expires from the player
//The effect numbers can be found here:
//https://github.com/underbent/slashdiablo-maphack/wiki/Effects
Skill Warning[16]:	False		// enchant
Skill Warning[32]:	False		// battle orders
Skill Warning[101]:	False		// holy shield
Skill Warning[149]:	False		// oak sage
Skill Warning[151]:	False		// cyclone armor

//Screen Info Configuration
AutomapInfo[0]:		Game Name: %GAMENAME%
AutomapInfo[1]:		Game Password: %GAMEPASS%
AutomapInfo[2]:		%LEVEL%
AutomapInfo[3]:		Difficulty: %GAMEDIFF%
AutomapInfo[4]:		Ip: %GAMEIP%
AutomapInfo[5]:		%GAMETIME%
AutomapInfo[6]:		%REALTIME%

//Quest Drop Warning for Mephisto/Diablo/Baal quests
Quest Drop Warning:	False

//Gamefilter Configuration
GameListRefresh:	1500

//Bnet Configuration
Show Last Game:		False
Fail To Join:		4000

//Character Configuration
Character Stats:	VK_8

//Item Configuration
Show Ethereal:		False, None
Show Sockets:		False, None
Show iLvl:		False, None
Show Rune Numbers:	False, None
Alt Item Style:		False, None
Color Mod:		False, None
Shorten Item Names:	False, None
Show Players Gear:	VK_0

//AutoTele Configuration
//Display Messages:	False, None
//Draw Path:		False, None
//Draw Destination:	False, None
//CP to cave:		False, None
//Fast Teleport:	False, None

//Next Tele:		VK_NUMPAD0
//Other Tele:		VK_NUMPAD1
//Waypoint Tele:	VK_NUMPAD2
//Prev Tele:		VK_NUMPAD3

//Path Color:		97
//Next Color:		0x97
//Other Color:		0x0A
//WP Color:		0x84
//Prev Color:		0x5B

//Party Configuration
Party Enabled:		False, VK_9
Looting Enabled:	False, VK_7

//Using Potions in Inventory
Use Healing Potion:	False, VK_NUMPADMULTIPLY
Use Mana Potion:	False, VK_NUMPADSUBTRACT

//Spam Filter Configuration
Log Chat:		False, None
Log Blocks:		False, None
Enabled:		False, None
Autosave:		False, None
Log File:		chatlog.txt
Update URL:		
Token DB:		tokens.db


//Item Display Configuration
Advanced Item Display: True, None

// GEMS
// Hide chipped and flawed
ItemDisplay[GEMLEVEL<3 !GEMLEVEL=1]:
// Hide normal (not amethyst or skull)
ItemDisplay[GEMLEVEL=3 AND !(GEMTYPE=1 OR GEMTYPE=7)]:
// Make normal purple
ItemDisplay[GEMLEVEL=3]: %PURPLE%%NAME%
// Make flawless purple
ItemDisplay[GEMLEVEL=4]: %PURPLE%%NAME%
// Makw perfect purple
ItemDisplay[GEMLEVEL=5]: %PURPLE%%NAME%

//Ignore 'junk' (Miscellaneous potions, quivers, etc.), potion, scroll renaming & gold piles below 1000.
ItemDisplay[GOLD<2000]:
ItemDisplay[tsc]: 
ItemDisplay[isc]: 
ItemDisplay[vps]:
ItemDisplay[yps]:
ItemDisplay[wms]:
ItemDisplay[gps]:
ItemDisplay[ops]:
ItemDisplay[gpm]:
ItemDisplay[opm]:
ItemDisplay[gpl]:
ItemDisplay[opl]:
ItemDisplay[hp1]: 
ItemDisplay[hp2]: 
ItemDisplay[hp3]: 
ItemDisplay[hp4]: 
ItemDisplay[hp5]: Super Healing Potion
ItemDisplay[mp1]: 
ItemDisplay[mp2]: 
ItemDisplay[mp3]: 
ItemDisplay[mp4]:
ItemDisplay[mp5]: Super Mana Potion
ItemDisplay[rvs]: %PURPLE% Rejuvenation Potion
ItemDisplay[rvl]: %PURPLE% Full Rejuvenation Potion
ItemDisplay[aqv]:
ItemDisplay[cqv]:
ItemDisplay[key]:
ItemDisplay[ear]:

// Jewels, Small/Grand Charms
ItemDisplay[MAG (jew OR cm1 OR cm3)]: %ORANGE%%NAME%

//Druid Pelts
ItemDisplay[RARE !ETH !ID CL1]: %PURPLE%O%BLUE%%NAME%
//Monarchs
ItemDisplay[RARE !ETH !ID uit]: %PURPLE%O%BLUE%%NAME%
//Circlets/Diadems/Etc
ItemDisplay[RARE !ETH !ID EQ7]: %PURPLE%O%BLUE%%NAME%
//Archon Plate
//ItemDisplay[MAG !ETH !ID utp]: %PURPLE%O%BLUE%%NAME%
//Assassin Claws
//ItemDisplay[MAG !ID (9lw OR 7lw OR 9tw OR 7tw OR 9hw OR 7hw)]: %PURPLE%O%BLUE%%NAME%
