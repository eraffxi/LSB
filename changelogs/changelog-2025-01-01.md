## LandSandBoat Changelog (2025-01-01)
- [core] remove unused function to allow ci to pass again [[#6626](https://github.com/LandSandBoat/server/pull/6626), [patch](https://github.com/LandSandBoat/server/pull/6626.patch)] (WinterSolstice8)
- [login] remove static assert to allow builds again [[#6625](https://github.com/LandSandBoat/server/pull/6625), [patch](https://github.com/LandSandBoat/server/pull/6625.patch)] (WinterSolstice8)
- [lua] update empyreal arrow acc bonus to correct value [[#6621](https://github.com/LandSandBoat/server/pull/6621), [patch](https://github.com/LandSandBoat/server/pull/6621.patch)] (WinterSolstice8)
- Search: minor cleanup and refactoring of handler<t> [[#6619](https://github.com/LandSandBoat/server/pull/6619), [patch](https://github.com/LandSandBoat/server/pull/6619.patch)] (zach2good)
- Update manuever type abilities to be 0 delay [[#6614](https://github.com/LandSandBoat/server/pull/6614), [patch](https://github.com/LandSandBoat/server/pull/6614.patch)] (TiberonKalkaz)
- [lua] rename all incorrectly named mamool ja scripts so they work [[#6613](https://github.com/LandSandBoat/server/pull/6613), [patch](https://github.com/LandSandBoat/server/pull/6613.patch)] (WinterSolstice8)
- Apply speed mod setting to base speed [[#6612](https://github.com/LandSandBoat/server/pull/6612), [patch](https://github.com/LandSandBoat/server/pull/6612.patch)] (cocosolos)
- [search] rewrite search in asio [[#6611](https://github.com/LandSandBoat/server/pull/6611), [patch](https://github.com/LandSandBoat/server/pull/6611.patch)] (WinterSolstice8)
- [core] always recalculate stats during level sync application [[#6607](https://github.com/LandSandBoat/server/pull/6607), [patch](https://github.com/LandSandBoat/server/pull/6607.patch)] (WinterSolstice8)
- Remove empty statement in application() [[#6606](https://github.com/LandSandBoat/server/pull/6606), [patch](https://github.com/LandSandBoat/server/pull/6606.patch)] (claywar)
- Ci: update compilers to ubuntu 24.04 newest [[#6604](https://github.com/LandSandBoat/server/pull/6604), [patch](https://github.com/LandSandBoat/server/pull/6604.patch)] (zach2good)
- Core: add empty cfellowentity class [[#6602](https://github.com/LandSandBoat/server/pull/6602), [patch](https://github.com/LandSandBoat/server/pull/6602.patch)] (zach2good)
- [lua] sagheera abcs count for unused chips fix [[#6600](https://github.com/LandSandBoat/server/pull/6600), [patch](https://github.com/LandSandBoat/server/pull/6600.patch)] (sruon)
- [lua] ix drk and qnaern fixes [[#6597](https://github.com/LandSandBoat/server/pull/6597), [patch](https://github.com/LandSandBoat/server/pull/6597.patch)] (slashtangent)
- [lua] add fallen star through logging for wish upon a star [[#6596](https://github.com/LandSandBoat/server/pull/6596), [patch](https://github.com/LandSandBoat/server/pull/6596.patch)] (CriticalXI)
- [lua] update great katana hybrid ws ftp to known retail values [[#6595](https://github.com/LandSandBoat/server/pull/6595), [patch](https://github.com/LandSandBoat/server/pull/6595.patch)] (WinterSolstice8)
- [lua] add some known ranged ws acc bonuses [[#6594](https://github.com/LandSandBoat/server/pull/6594), [patch](https://github.com/LandSandBoat/server/pull/6594.patch)] (WinterSolstice8)
- [lua] use correct variable in hb hp% check [[#6593](https://github.com/LandSandBoat/server/pull/6593), [patch](https://github.com/LandSandBoat/server/pull/6593.patch)] (WinterSolstice8)
- [lua] ensure white procs can't happen without sj_restriction effect in dynamis [[#6589](https://github.com/LandSandBoat/server/pull/6589), [patch](https://github.com/LandSandBoat/server/pull/6589.patch)] (sruon)
- Bind spells duration has a floor of 5 seconds if not fully resisted. [[#6588](https://github.com/LandSandBoat/server/pull/6588), [patch](https://github.com/LandSandBoat/server/pull/6588.patch)] (blueBounder)
- Use local vars, format tables for glittering ruby, zipacna [[#6585](https://github.com/LandSandBoat/server/pull/6585), [patch](https://github.com/LandSandBoat/server/pull/6585.patch)] (claywar)
- Misc fixes: sch af qm positions update (bandaid), warp cudgel use time [[#6584](https://github.com/LandSandBoat/server/pull/6584), [patch](https://github.com/LandSandBoat/server/pull/6584.patch)] (WinterSolstice8)
- [lua] add gettotalskill function to xi.crafting [[#6583](https://github.com/LandSandBoat/server/pull/6583), [patch](https://github.com/LandSandBoat/server/pull/6583.patch)] (Flibe-XI)
- Fix textoffset for magian trial #1826 [[#6580](https://github.com/LandSandBoat/server/pull/6580), [patch](https://github.com/LandSandBoat/server/pull/6580.patch)] (claywar)
- [lua] cargo crab colin - ph fix [[#6578](https://github.com/LandSandBoat/server/pull/6578), [patch](https://github.com/LandSandBoat/server/pull/6578.patch)] (slashtangent)
- V1.1.4 - fix search server failing randomly [[#31](https://github.com/LandSandBoat/xiloader/pull/31), [patch](https://github.com/LandSandBoat/xiloader/pull/31.patch)] (WinterSolstice8)
- [lua] properly apply sj_restriction effect in dynamis dreamlands [[#6577](https://github.com/LandSandBoat/server/pull/6577), [patch](https://github.com/LandSandBoat/server/pull/6577.patch)] (sruon)
- Ci: build and run all modules in own job [[#6573](https://github.com/LandSandBoat/server/pull/6573), [patch](https://github.com/LandSandBoat/server/pull/6573.patch)] (zach2good)
- Modules: cache zone_settings before applying modules [[#6572](https://github.com/LandSandBoat/server/pull/6572), [patch](https://github.com/LandSandBoat/server/pull/6572.patch)] (zach2good)
- Db: p.stmt and query will now reconnect after disconnects [[#6571](https://github.com/LandSandBoat/server/pull/6571), [patch](https://github.com/LandSandBoat/server/pull/6571.patch)] (zach2good)
- Modules: replace p.stmt with query inside loadluamodules [[#6570](https://github.com/LandSandBoat/server/pull/6570), [patch](https://github.com/LandSandBoat/server/pull/6570.patch)] (zach2good)
- Db: make db:state self-healing on invalid connection (timeouts) [[#6568](https://github.com/LandSandBoat/server/pull/6568), [patch](https://github.com/LandSandBoat/server/pull/6568.patch)] (zach2good)
- Move draw-in to lua [[#6566](https://github.com/LandSandBoat/server/pull/6566), [patch](https://github.com/LandSandBoat/server/pull/6566.patch)] (cocosolos)
- Rng seeding updates, update default rng to mt64 [[#6565](https://github.com/LandSandBoat/server/pull/6565), [patch](https://github.com/LandSandBoat/server/pull/6565.patch)] (WinterSolstice8)
- [core] audit mob distributerewards, implement rare item special case [[#6562](https://github.com/LandSandBoat/server/pull/6562), [patch](https://github.com/LandSandBoat/server/pull/6562.patch)] (WinterSolstice8)
- Implement follow-up attacks and update virtue stone weapons to use follow-up attacks [[#6560](https://github.com/LandSandBoat/server/pull/6560), [patch](https://github.com/LandSandBoat/server/pull/6560.patch)] (Dukilles)
- [lua] made math.randoms more explicit [[#6558](https://github.com/LandSandBoat/server/pull/6558), [patch](https://github.com/LandSandBoat/server/pull/6558.patch)] (Flibe-XI)
- Adding a guide to use letsencrypt certificates with xi_connect [[#103](https://github.com/LandSandBoat/lsb-wiki/pull/103), [patch](https://github.com/LandSandBoat/lsb-wiki/pull/103.patch)] (GanimanSwift)
- [lua] change effect koru's flurry gambit checks to stop spamming [[#6557](https://github.com/LandSandBoat/server/pull/6557), [patch](https://github.com/LandSandBoat/server/pull/6557.patch)] (WinterSolstice8)
- [codeql] replace c-style cast/objtype compare with dynamic_cast [[#6556](https://github.com/LandSandBoat/server/pull/6556), [patch](https://github.com/LandSandBoat/server/pull/6556.patch)] (claywar)
- [fix] remove invalid drop ids from nyzul boss mixin [[#6555](https://github.com/LandSandBoat/server/pull/6555), [patch](https://github.com/LandSandBoat/server/pull/6555.patch)] (Xaver-DaRed)
- Update lord's cuirass to be craftable [[#6554](https://github.com/LandSandBoat/server/pull/6554), [patch](https://github.com/LandSandBoat/server/pull/6554.patch)] (bliven-was-taken)
- [core][lua][sql] implement contradance [[#6553](https://github.com/LandSandBoat/server/pull/6553), [patch](https://github.com/LandSandBoat/server/pull/6553.patch)] (WinterSolstice8)
- [lua] replaced item ids with enums in zaldon.lua [[#6551](https://github.com/LandSandBoat/server/pull/6551), [patch](https://github.com/LandSandBoat/server/pull/6551.patch)] (Flibe-XI)
- Modules: replace dedicated sqlconnection with db::, fix ahpaginationmodule and ahannouncementmodule [[#6548](https://github.com/LandSandBoat/server/pull/6548), [patch](https://github.com/LandSandBoat/server/pull/6548.patch)] (zach2good)
- Core: start replacing pushpacket(new t, ...) with pushpacket<t>(...) [[#6546](https://github.com/LandSandBoat/server/pull/6546), [patch](https://github.com/LandSandBoat/server/pull/6546.patch)] (zach2good)
- [lua] implement promyvion memory clusters [[#6543](https://github.com/LandSandBoat/server/pull/6543), [patch](https://github.com/LandSandBoat/server/pull/6543.patch)] (WinterSolstice8)
- Mob run speed changes [[#6542](https://github.com/LandSandBoat/server/pull/6542), [patch](https://github.com/LandSandBoat/server/pull/6542.patch)] (cocosolos)
- [core] dirty & undirty inventory when changing gear [[#6541](https://github.com/LandSandBoat/server/pull/6541), [patch](https://github.com/LandSandBoat/server/pull/6541.patch)] (WinterSolstice8)
- [vscode] add gdb attach config to attach to xi_map [[#6539](https://github.com/LandSandBoat/server/pull/6539), [patch](https://github.com/LandSandBoat/server/pull/6539.patch)] (WinterSolstice8)
- Db: handle std::array and structs in binders [[#6538](https://github.com/LandSandBoat/server/pull/6538), [patch](https://github.com/LandSandBoat/server/pull/6538.patch)] (zach2good)
- [fix] correct typo in "yellow gingsen" enum [[#6531](https://github.com/LandSandBoat/server/pull/6531), [patch](https://github.com/LandSandBoat/server/pull/6531.patch)] (Xaver-DaRed)
- Add more explanation to module guide [[#102](https://github.com/LandSandBoat/lsb-wiki/pull/102), [patch](https://github.com/LandSandBoat/lsb-wiki/pull/102.patch)] (zach2good)
- V1.1.3, hint  to windows are are dpi aware, better logging, better detect when to use autologin [[#30](https://github.com/LandSandBoat/xiloader/pull/30), [patch](https://github.com/LandSandBoat/xiloader/pull/30.patch)] (WinterSolstice8)
- [cpp] prevent plants from updating if not on correct stage [[#6527](https://github.com/LandSandBoat/server/pull/6527), [patch](https://github.com/LandSandBoat/server/pull/6527.patch)] (lapislosh)
- [client] december 2024 version update [[#6526](https://github.com/LandSandBoat/server/pull/6526), [patch](https://github.com/LandSandBoat/server/pull/6526.patch)] (claywar)
- Enable virtue stone offhand attacks for faith baghnakhs [[#6520](https://github.com/LandSandBoat/server/pull/6520), [patch](https://github.com/LandSandBoat/server/pull/6520.patch)] (TiberonKalkaz)
- [lua/sql] zipacna fixes for pathing and door interactions [[#6516](https://github.com/LandSandBoat/server/pull/6516), [patch](https://github.com/LandSandBoat/server/pull/6516.patch)] (0x05010705)
- [digging] final part: implement digging layers and rank requirements [[#6135](https://github.com/LandSandBoat/server/pull/6135), [patch](https://github.com/LandSandBoat/server/pull/6135.patch)] (Xaver-DaRed)
- [lua] hybrid weaponskill damage is incorrect [[#5883](https://github.com/LandSandBoat/server/pull/5883), [patch](https://github.com/LandSandBoat/server/pull/5883.patch)] (Gloin-Horizon)