## LandSandBoat Changelog (2022-07-01)
- [core] adjust party.cpp to allow for party leader removal in "mob" parties safely [[#2162](https://github.com/LandSandBoat/server/pull/2162), [patch](https://github.com/LandSandBoat/server/pull/2162.patch)] (WinterSolstice8)
- [luacheck] simplify caskets global to satisfy ci [[#2161](https://github.com/LandSandBoat/server/pull/2161), [patch](https://github.com/LandSandBoat/server/pull/2161.patch)] (claywar)
- Interaction - missions: undying light, the light within [[#2159](https://github.com/LandSandBoat/server/pull/2159), [patch](https://github.com/LandSandBoat/server/pull/2159.patch)] (claywar)
- Interaction - missions: watery grave through abomination [[#2156](https://github.com/LandSandBoat/server/pull/2156), [patch](https://github.com/LandSandBoat/server/pull/2156.patch)] (claywar)
- Correct setting names to correct crafting skill ups  [[#2155](https://github.com/LandSandBoat/server/pull/2155), [patch](https://github.com/LandSandBoat/server/pull/2155.patch)] (Xaver-DaRed)
- Homepoint the player instead of setting a specific zone [[#2150](https://github.com/LandSandBoat/server/pull/2150), [patch](https://github.com/LandSandBoat/server/pull/2150.patch)] (TeoTwawki)
- [ws] add multihit ftp to club weaponskills [[#2147](https://github.com/LandSandBoat/server/pull/2147), [patch](https://github.com/LandSandBoat/server/pull/2147.patch)] (Schaedelschaden)
- [sql] add comments to mob_spell_lists table [[#2146](https://github.com/LandSandBoat/server/pull/2146), [patch](https://github.com/LandSandBoat/server/pull/2146.patch)] (claywar)
- [core] add special spawn animation to non-trust entities [[#2144](https://github.com/LandSandBoat/server/pull/2144), [patch](https://github.com/LandSandBoat/server/pull/2144.patch)] (zach2good)
- Fixes pirate ship client crashes [[#2143](https://github.com/LandSandBoat/server/pull/2143), [patch](https://github.com/LandSandBoat/server/pull/2143.patch)] (The-Aerec)
- [luacheck] simplify magic global functions to satisfy ci complexity [[#2141](https://github.com/LandSandBoat/server/pull/2141), [patch](https://github.com/LandSandBoat/server/pull/2141.patch)] (claywar)
- [luacheck] simplify xi.spells.damage.calculateresist() to satisfy ci complexity [[#2139](https://github.com/LandSandBoat/server/pull/2139), [patch](https://github.com/LandSandBoat/server/pull/2139.patch)] (claywar)
- Comment out call to updateservermessage() until implemented [[#2138](https://github.com/LandSandBoat/server/pull/2138), [patch](https://github.com/LandSandBoat/server/pull/2138.patch)] (claywar)
- Fix settings references for decimation, rampage, and ruinator [[#2137](https://github.com/LandSandBoat/server/pull/2137), [patch](https://github.com/LandSandBoat/server/pull/2137.patch)] (claywar)
- [lua] use utils function for avatar shadow calculation, attach summon global to xi.summon [[#2136](https://github.com/LandSandBoat/server/pull/2136), [patch](https://github.com/LandSandBoat/server/pull/2136.patch)] (claywar)
- [core] replace roesystem.roeenabled with new settings system [[#2135](https://github.com/LandSandBoat/server/pull/2135), [patch](https://github.com/LandSandBoat/server/pull/2135.patch)] (zach2good)
- Fix ci warnings for trailing whitespace in globals/settings.lua [[#2133](https://github.com/LandSandBoat/server/pull/2133), [patch](https://github.com/LandSandBoat/server/pull/2133.patch)] (claywar)
- [core] add flag to load all lua files for sanity testing [[#2132](https://github.com/LandSandBoat/server/pull/2132), [patch](https://github.com/LandSandBoat/server/pull/2132.patch)] (zach2good)
- [core] extract client language id during login [[#2131](https://github.com/LandSandBoat/server/pull/2131), [patch](https://github.com/LandSandBoat/server/pull/2131.patch)] (WinterSolstice8)
- [core] fix pulling incorrect settings for zmq/map [[#2129](https://github.com/LandSandBoat/server/pull/2129), [patch](https://github.com/LandSandBoat/server/pull/2129.patch)] (WinterSolstice8)
- [sql/lua] add mods for rarab cap and make usable [[#2128](https://github.com/LandSandBoat/server/pull/2128), [patch](https://github.com/LandSandBoat/server/pull/2128.patch)] (CatsEyeXI)
- Fixing error from new settings mr [[#2126](https://github.com/LandSandBoat/server/pull/2126), [patch](https://github.com/LandSandBoat/server/pull/2126.patch)] (The-Aerec)
- Add new settings location to .gitignore [[#2125](https://github.com/LandSandBoat/server/pull/2125), [patch](https://github.com/LandSandBoat/server/pull/2125.patch)] (claywar)
- Interaction - missions: yggdrasil beckons through the seventh guardian [[#2124](https://github.com/LandSandBoat/server/pull/2124), [patch](https://github.com/LandSandBoat/server/pull/2124.patch)] (claywar)
- [cmake] remove redundant logging about ccache [[#2121](https://github.com/LandSandBoat/server/pull/2121), [patch](https://github.com/LandSandBoat/server/pull/2121.patch)] (zach2good)
- Fixed phairet portion of the_trader_in_the_wood.lua [[#2119](https://github.com/LandSandBoat/server/pull/2119), [patch](https://github.com/LandSandBoat/server/pull/2119.patch)] (austinclprojects)
- [ws] add multihit ftp to axe weaponskills [[#2117](https://github.com/LandSandBoat/server/pull/2117), [patch](https://github.com/LandSandBoat/server/pull/2117.patch)] (Schaedelschaden)
- [core] set trustentity and petentity to be unclaimable [[#2113](https://github.com/LandSandBoat/server/pull/2113), [patch](https://github.com/LandSandBoat/server/pull/2113.patch)] (WinterSolstice8)
- [sql] fix @uncommon references after comment changes [[#2112](https://github.com/LandSandBoat/server/pull/2112), [patch](https://github.com/LandSandBoat/server/pull/2112.patch)] (claywar)
- Interaction - missions: balamor's ruse through a portent most ominous [[#2111](https://github.com/LandSandBoat/server/pull/2111), [patch](https://github.com/LandSandBoat/server/pull/2111.patch)] (claywar)
- [sql] add comments to mob_droplists.sql [[#2109](https://github.com/LandSandBoat/server/pull/2109), [patch](https://github.com/LandSandBoat/server/pull/2109.patch)] (claywar)
- [ext] update sol to new release v3.3.0 [[#2107](https://github.com/LandSandBoat/server/pull/2107), [patch](https://github.com/LandSandBoat/server/pull/2107.patch)] (zach2good)
- [core] make sure equipped dynamic entities have correct names [[#2106](https://github.com/LandSandBoat/server/pull/2106), [patch](https://github.com/LandSandBoat/server/pull/2106.patch)] (zach2good)
- [item mods] update equipment item mods (originally pr #2088) [[#2105](https://github.com/LandSandBoat/server/pull/2105), [patch](https://github.com/LandSandBoat/server/pull/2105.patch)] (Schaedelschaden)
- Change dbtool client version read/write [[#2097](https://github.com/LandSandBoat/server/pull/2097), [patch](https://github.com/LandSandBoat/server/pull/2097.patch)] (cocosolos)
- [ci] fix issue templates [[#2094](https://github.com/LandSandBoat/server/pull/2094), [patch](https://github.com/LandSandBoat/server/pull/2094.patch)] (zach2good)
- [core] update zoneutils::getentity to match dynamic entity index change [[#2092](https://github.com/LandSandBoat/server/pull/2092), [patch](https://github.com/LandSandBoat/server/pull/2092.patch)] (WinterSolstice8)
- [fix] remove npc argument from messagetext in quests and rework some logic for maat [[#2090](https://github.com/LandSandBoat/server/pull/2090), [patch](https://github.com/LandSandBoat/server/pull/2090.patch)] (Xaver-DaRed)
- [item mods] rename da_double_damage and ta_triple_damage mods [[#2089](https://github.com/LandSandBoat/server/pull/2089), [patch](https://github.com/LandSandBoat/server/pull/2089.patch)] (Schaedelschaden)
- [geo] add missing reservoirs and reconcile differences from retail [[#2087](https://github.com/LandSandBoat/server/pull/2087), [patch](https://github.com/LandSandBoat/server/pull/2087.patch)] (CatsEyeXI)
- Fix variable spelling errors in "the wayward automaton" quest [[#2086](https://github.com/LandSandBoat/server/pull/2086), [patch](https://github.com/LandSandBoat/server/pull/2086.patch)] (tristamgreen)
- [core] only allow mobs to gain enmity [[#2085](https://github.com/LandSandBoat/server/pull/2085), [patch](https://github.com/LandSandBoat/server/pull/2085.patch)] (WinterSolstice8)
- Move buildnpctable to onconquestupdate [[#2084](https://github.com/LandSandBoat/server/pull/2084), [patch](https://github.com/LandSandBoat/server/pull/2084.patch)] (RunAwayDSP)
- Interaction - missions: anagnorisis through arciela's resolve [[#2082](https://github.com/LandSandBoat/server/pull/2082), [patch](https://github.com/LandSandBoat/server/pull/2082.patch)] (claywar)
- [item mods] add double/triple attack damage + mods and functionality [[#2080](https://github.com/LandSandBoat/server/pull/2080), [patch](https://github.com/LandSandBoat/server/pull/2080.patch)] (Schaedelschaden)
- [docs] make the github templates more obvious [[#2078](https://github.com/LandSandBoat/server/pull/2078), [patch](https://github.com/LandSandBoat/server/pull/2078.patch)] (zach2good)
- [geo] add geo scrolls to item_usable table and corresponding scripts [[#2073](https://github.com/LandSandBoat/server/pull/2073), [patch](https://github.com/LandSandBoat/server/pull/2073.patch)] (CatsEyeXI)
- [search] further simplify the logic in expireahitems [[#2071](https://github.com/LandSandBoat/server/pull/2071), [patch](https://github.com/LandSandBoat/server/pull/2071.patch)] (zach2good)
- [search] add expire_all command, fix delete order in listing expiry [[#2069](https://github.com/LandSandBoat/server/pull/2069), [patch](https://github.com/LandSandBoat/server/pull/2069.patch)] (zach2good)
- Interaction - missions: light of dawn comes from the east through balamor, the deathborne xol [[#2065](https://github.com/LandSandBoat/server/pull/2065), [patch](https://github.com/LandSandBoat/server/pull/2065.patch)] (claywar)
- Update trust adelheid to use dark arts / addendum: black [[#2061](https://github.com/LandSandBoat/server/pull/2061), [patch](https://github.com/LandSandBoat/server/pull/2061.patch)] (neuromancerxi)
- Interaction - missions: the gates through the lightsland [[#2059](https://github.com/LandSandBoat/server/pull/2059), [patch](https://github.com/LandSandBoat/server/pull/2059.patch)] (claywar)
- Mini patch to fix chocobo digging fatigue [[#2058](https://github.com/LandSandBoat/server/pull/2058), [patch](https://github.com/LandSandBoat/server/pull/2058.patch)] (m241dan)
- Remove sethp(0) from mijin when mob:isindynamis() [[#2057](https://github.com/LandSandBoat/server/pull/2057), [patch](https://github.com/LandSandBoat/server/pull/2057.patch)] (OpheliaXI)
- Add storm and helix plumbing to trust adelheid [[#2056](https://github.com/LandSandBoat/server/pull/2056), [patch](https://github.com/LandSandBoat/server/pull/2056.patch)] (neuromancerxi)
- [zm/quest] divine might bugfix + small adjustments [[#2052](https://github.com/LandSandBoat/server/pull/2052), [patch](https://github.com/LandSandBoat/server/pull/2052.patch)] (The-Aerec)
- [core] change spikes other than dread spikes to do damage again [[#2050](https://github.com/LandSandBoat/server/pull/2050), [patch](https://github.com/LandSandBoat/server/pull/2050.patch)] (m241dan)
- Update crooked_cards.lua power from 17->20 per bg [[#2049](https://github.com/LandSandBoat/server/pull/2049), [patch](https://github.com/LandSandBoat/server/pull/2049.patch)] (drobinsona149)
- [core] adds "too far" for player and trust ws, fix 0 delay tp moves generating an empty action packet, add some more safety [[#2045](https://github.com/LandSandBoat/server/pull/2045), [patch](https://github.com/LandSandBoat/server/pull/2045.patch)] (WinterSolstice8)
- Update ghrah mixin spell lists [[#2043](https://github.com/LandSandBoat/server/pull/2043), [patch](https://github.com/LandSandBoat/server/pull/2043.patch)] (The-Aerec)
- [core] allow commands to be specified from modules [[#2042](https://github.com/LandSandBoat/server/pull/2042), [patch](https://github.com/LandSandBoat/server/pull/2042.patch)] (zach2good)
- [core] add safety and additional logging to replace debug breaks [[#2039](https://github.com/LandSandBoat/server/pull/2039), [patch](https://github.com/LandSandBoat/server/pull/2039.patch)] (claywar)
- Nm mob fixes [[#2038](https://github.com/LandSandBoat/server/pull/2038), [patch](https://github.com/LandSandBoat/server/pull/2038.patch)] (dallano)
- Adjust trust adelheid cure thresholds [[#2037](https://github.com/LandSandBoat/server/pull/2037), [patch](https://github.com/LandSandBoat/server/pull/2037.patch)] (neuromancerxi)
- Remove duplicated field definitions in job_point_gifts.sql [[#2034](https://github.com/LandSandBoat/server/pull/2034), [patch](https://github.com/LandSandBoat/server/pull/2034.patch)] (TeoTwawki)
- [fix] jp gift su values [[#2033](https://github.com/LandSandBoat/server/pull/2033), [patch](https://github.com/LandSandBoat/server/pull/2033.patch)] (Xaver-DaRed)
- [core] shift dynamic entity id assignment by +256 (0x100) [[#2031](https://github.com/LandSandBoat/server/pull/2031), [patch](https://github.com/LandSandBoat/server/pull/2031.patch)] (WinterSolstice8)
- Add missing fields to char_check, health, and jobs, fix max merit poi… [[#2027](https://github.com/LandSandBoat/server/pull/2027), [patch](https://github.com/LandSandBoat/server/pull/2027.patch)] (claywar)
- Dbtool updates [[#2024](https://github.com/LandSandBoat/server/pull/2024), [patch](https://github.com/LandSandBoat/server/pull/2024.patch)] (cocosolos)
- Fix magic damage references from spell_damage to damage [[#2023](https://github.com/LandSandBoat/server/pull/2023), [patch](https://github.com/LandSandBoat/server/pull/2023.patch)] (claywar)
- Update menu_merit, break out monipulator packets [[#2021](https://github.com/LandSandBoat/server/pull/2021), [patch](https://github.com/LandSandBoat/server/pull/2021.patch)] (claywar)
- Update char_stats packet, fix roe packet sizes [[#2020](https://github.com/LandSandBoat/server/pull/2020), [patch](https://github.com/LandSandBoat/server/pull/2020.patch)] (claywar)
- Fix weekly logic for unity leader objectives [[#2018](https://github.com/LandSandBoat/server/pull/2018), [patch](https://github.com/LandSandBoat/server/pull/2018.patch)] (claywar)
- [sql] fixes typo in itemid for leathercraft guild points item leather shield. [[#2017](https://github.com/LandSandBoat/server/pull/2017), [patch](https://github.com/LandSandBoat/server/pull/2017.patch)] (EpicTaru)
- [core] add null check for pguildshop in smallpacket0x0aa [[#2016](https://github.com/LandSandBoat/server/pull/2016), [patch](https://github.com/LandSandBoat/server/pull/2016.patch)] (CatsEyeXI)
- [core] replace delete with assign of nullptr in ccharentity destructor [[#2015](https://github.com/LandSandBoat/server/pull/2015), [patch](https://github.com/LandSandBoat/server/pull/2015.patch)] (WinterSolstice8)
- [core] remove unnecessary delete, fix #2004  [[#2006](https://github.com/LandSandBoat/server/pull/2006), [patch](https://github.com/LandSandBoat/server/pull/2006.patch)] (WinterSolstice8)
- [commands] add !provokeall [[#2005](https://github.com/LandSandBoat/server/pull/2005), [patch](https://github.com/LandSandBoat/server/pull/2005.patch)] (Flam9)
- [core] rename trust sync packet [[#2003](https://github.com/LandSandBoat/server/pull/2003), [patch](https://github.com/LandSandBoat/server/pull/2003.patch)] (zach2good)
- [login] add ip limit exceptions [[#2002](https://github.com/LandSandBoat/server/pull/2002), [patch](https://github.com/LandSandBoat/server/pull/2002.patch)] (The-Aerec)
- [sql] corrected ah category for hajduk ring/+1 [[#1999](https://github.com/LandSandBoat/server/pull/1999), [patch](https://github.com/LandSandBoat/server/pull/1999.patch)] (EpicTaru)
- [core] fix crash with removal of dynamic mobs in parties, update renamer module to map name to name [[#1997](https://github.com/LandSandBoat/server/pull/1997), [patch](https://github.com/LandSandBoat/server/pull/1997.patch)] (zach2good)
- Pr/fix mother globe and slave globe behaviour mechanics to be more retail accurate [[#1970](https://github.com/LandSandBoat/server/pull/1970), [patch](https://github.com/LandSandBoat/server/pull/1970.patch)] (m241dan)
- [core] intialize uninitialized members, don't access out of bounds memory, add constructors, small memcpy fixes, fix various warnings [[#1954](https://github.com/LandSandBoat/server/pull/1954), [patch](https://github.com/LandSandBoat/server/pull/1954.patch)] (WinterSolstice8)
- Settings (and lua) refactor [[#1945](https://github.com/LandSandBoat/server/pull/1945), [patch](https://github.com/LandSandBoat/server/pull/1945.patch)] (zach2good)
- Garrison clean up and id shift prevention [[#1919](https://github.com/LandSandBoat/server/pull/1919), [patch](https://github.com/LandSandBoat/server/pull/1919.patch)] (RunAwayDSP)
- [mission] cop 1-3 the mothercrystals - promyvion balancing [[#1902](https://github.com/LandSandBoat/server/pull/1902), [patch](https://github.com/LandSandBoat/server/pull/1902.patch)] (Frankie-hz)
- [missions] cop 8-4 dawn mechanics / adjustments [[#1888](https://github.com/LandSandBoat/server/pull/1888), [patch](https://github.com/LandSandBoat/server/pull/1888.patch)] (The-Aerec)
- [mission] cop 2-5 ancient vow fixes [[#1887](https://github.com/LandSandBoat/server/pull/1887), [patch](https://github.com/LandSandBoat/server/pull/1887.patch)] (Frankie-hz)
- Implement enm holy cow; correct bearclaw pinnacle entrance required [[#1874](https://github.com/LandSandBoat/server/pull/1874), [patch](https://github.com/LandSandBoat/server/pull/1874.patch)] (CriticalXI)
- Get item id by name [[#1825](https://github.com/LandSandBoat/server/pull/1825), [patch](https://github.com/LandSandBoat/server/pull/1825.patch)] (paladindamarus)
- Add some basic messaging and plumbing for mog tablets [[#1123](https://github.com/LandSandBoat/server/pull/1123), [patch](https://github.com/LandSandBoat/server/pull/1123.patch)] (zach2good)
- Add scripts and adjust plumbing for many temp items [[#670](https://github.com/LandSandBoat/server/pull/670), [patch](https://github.com/LandSandBoat/server/pull/670.patch)] (neuromancerxi)