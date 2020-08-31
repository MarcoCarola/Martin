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
