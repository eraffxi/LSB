## LandSandBoat Changelog (2024-12-15)
- [core] adjust db::escapestring to emulate strlen [[#6523](https://github.com/LandSandBoat/server/pull/6523), [patch](https://github.com/LandSandBoat/server/pull/6523.patch)] (WinterSolstice8)
- Fix terra crystal item id in synthutils [[#6517](https://github.com/LandSandBoat/server/pull/6517), [patch](https://github.com/LandSandBoat/server/pull/6517.patch)] (Xaver-DaRed)
- Db: properly escape % in blobs, more error handling in query() [[#6511](https://github.com/LandSandBoat/server/pull/6511), [patch](https://github.com/LandSandBoat/server/pull/6511.patch)] (zach2good)
- [lua] move ws offhand swing to end, adjust tp gains accordingly [[#6509](https://github.com/LandSandBoat/server/pull/6509), [patch](https://github.com/LandSandBoat/server/pull/6509.patch)] (WinterSolstice8)
- [core] trigger time of day based latents on all day events [[#6508](https://github.com/LandSandBoat/server/pull/6508), [patch](https://github.com/LandSandBoat/server/pull/6508.patch)] (WinterSolstice8)
- [sql] actually use scale/solid greaves item id in smithing gp [[#6506](https://github.com/LandSandBoat/server/pull/6506), [patch](https://github.com/LandSandBoat/server/pull/6506.patch)] (WinterSolstice8)
- [fix] correct string instrument effect on skill [[#6504](https://github.com/LandSandBoat/server/pull/6504), [patch](https://github.com/LandSandBoat/server/pull/6504.patch)] (Xaver-DaRed)
- Make vs workload selection more obvious [[#101](https://github.com/LandSandBoat/lsb-wiki/pull/101), [patch](https://github.com/LandSandBoat/lsb-wiki/pull/101.patch)] (zach2good)
- [sql] fix dynamis lord immunity bitmask [[#6503](https://github.com/LandSandBoat/server/pull/6503), [patch](https://github.com/LandSandBoat/server/pull/6503.patch)] (Xaver-DaRed)
- Chore: bump some dep versions [[#6501](https://github.com/LandSandBoat/server/pull/6501), [patch](https://github.com/LandSandBoat/server/pull/6501.patch)] (zach2good)
- Db: fix query() to use perfect forwarding for arguments [[#6500](https://github.com/LandSandBoat/server/pull/6500), [patch](https://github.com/LandSandBoat/server/pull/6500.patch)] (zach2good)
- [core] change getalliancesize() to actually get alliance size [[#6499](https://github.com/LandSandBoat/server/pull/6499), [patch](https://github.com/LandSandBoat/server/pull/6499.patch)] (WinterSolstice8)
- Implement food hp/mp mods (distinct from standard hp/mp mods) [[#6495](https://github.com/LandSandBoat/server/pull/6495), [patch](https://github.com/LandSandBoat/server/pull/6495.patch)] (WinterSolstice8)
- Async: remove sqlconnection helpers [[#6494](https://github.com/LandSandBoat/server/pull/6494), [patch](https://github.com/LandSandBoat/server/pull/6494.patch)] (zach2good)
- Return no available traverser stones if epoch is unset [[#6493](https://github.com/LandSandBoat/server/pull/6493), [patch](https://github.com/LandSandBoat/server/pull/6493.patch)] (claywar)
- Add currency2 entries for di, mog segments, gallimaufry, is accolades [[#6491](https://github.com/LandSandBoat/server/pull/6491), [patch](https://github.com/LandSandBoat/server/pull/6491.patch)] (claywar)
- [core] codeql warning cleanup for zone_entities.cpp [[#6488](https://github.com/LandSandBoat/server/pull/6488), [patch](https://github.com/LandSandBoat/server/pull/6488.patch)] (WinterSolstice8)
- Remove expansion_areas global, add local definition in roe_records [[#6487](https://github.com/LandSandBoat/server/pull/6487), [patch](https://github.com/LandSandBoat/server/pull/6487.patch)] (claywar)
- [chore] cleanup "the garden of ru'hmet" zone script [[#6486](https://github.com/LandSandBoat/server/pull/6486), [patch](https://github.com/LandSandBoat/server/pull/6486.patch)] (Xaver-DaRed)
- Fix loot grouping for zi'gui boneeater (palbarough) [[#6484](https://github.com/LandSandBoat/server/pull/6484), [patch](https://github.com/LandSandBoat/server/pull/6484.patch)] (Xaver-DaRed)
- [synthesis] audit modifiers involved in crafting and prep work for moving logic to lua [[#6483](https://github.com/LandSandBoat/server/pull/6483), [patch](https://github.com/LandSandBoat/server/pull/6483.patch)] (Xaver-DaRed)
- [core] use retail vit:def ratio of vit * 1.5 = def bonus [[#6480](https://github.com/LandSandBoat/server/pull/6480), [patch](https://github.com/LandSandBoat/server/pull/6480.patch)] (WinterSolstice8)
- [lua] add missing confirmtrade to quest brygid the stylist returns [[#6476](https://github.com/LandSandBoat/server/pull/6476), [patch](https://github.com/LandSandBoat/server/pull/6476.patch)] (bope12)
- [lua] update charvar name in coffer check for the quest wild card [[#6474](https://github.com/LandSandBoat/server/pull/6474), [patch](https://github.com/LandSandBoat/server/pull/6474.patch)] (bope12)
- Chore: cleanup mixed british/american spelling to american english [[#6470](https://github.com/LandSandBoat/server/pull/6470), [patch](https://github.com/LandSandBoat/server/pull/6470.patch)] (hooksta4)
- Core: add env64bit definition for osx [[#6467](https://github.com/LandSandBoat/server/pull/6467), [patch](https://github.com/LandSandBoat/server/pull/6467.patch)] (zach2good)
- Ceizak nm - unfettered twitherym - behavior, hp, mp, mob skills. [[#6459](https://github.com/LandSandBoat/server/pull/6459), [patch](https://github.com/LandSandBoat/server/pull/6459.patch)] (Yuchemey)
- [lua] dealer moogle: always return table for item selection [[#6432](https://github.com/LandSandBoat/server/pull/6432), [patch](https://github.com/LandSandBoat/server/pull/6432.patch)] (jamesbradleym)
- [lua] handle chocobo ticket and chocopass trade [[#6375](https://github.com/LandSandBoat/server/pull/6375), [patch](https://github.com/LandSandBoat/server/pull/6375.patch)] (jamesbradleym)
- Fix item enhancement/effect: multiple effects, wear on zone. add enhancement/effect source [[#6322](https://github.com/LandSandBoat/server/pull/6322), [patch](https://github.com/LandSandBoat/server/pull/6322.patch)] (jamesbradleym)
- Db: add resultsetwrapper type [[#6300](https://github.com/LandSandBoat/server/pull/6300), [patch](https://github.com/LandSandBoat/server/pull/6300.patch)] (zach2good)
- [quest] move the tenshodo showdown mob steal code to if file [[#6196](https://github.com/LandSandBoat/server/pull/6196), [patch](https://github.com/LandSandBoat/server/pull/6196.patch)] (jamesbradleym)