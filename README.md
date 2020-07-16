if gg.isPackageInstalled("sstool.only.com.sstool") then
gg.toast("️⚠️ Dangerous software installed! Remove it! ⚠️")
print("⚠️ Dangerous software installed! Remove it! ⚠️")
os.exit()
end
if gg.isPackageInstalled("io.neoterm") then
gg.toast("️⚠️ Dangerous software installed! Remove it! ⚠️")
print("⚠️ Dangerous software installed! Remove it! ⚠️")
os.exit()
end
if gg.isPackageInstalled("com.sstool.only.sstool") then
gg.toast("️⚠️ Dangerous software installed! Remove it! ⚠️")
print("⚠️ Dangerous software installed! Remove it! ⚠️")
os.exit()
end
function startscript()
gg.setVisible(false)
BP = gg.alert(' 🔹   🇰🇼  سـكـربـت هـــدام  🇰🇼   🔹\n  🔹       SECREPT: ALSHAYA       🔹\n  🔹     PHONE: 90966060     🔹\n 🔹    TELEGRAM: FADELALSHAYA      🔹',
'🔹بـــدء🔹') 
if BP == 1 then HOME() end
end
HOME=1
function HOME()
FF = gg.choice({  
   '🎗      حمايه اللوبي سيرفر (1)      🎗\n',--AntibanLobby  
   '🎗      حمايه اللوبي سيرفر (2)      🎗\n',--AntibanLobby   
   '🎗      قـائـمـه نـقـره واحـده          🎗\n',--One Click Menu
   '🎗      قائمه الولهاك و الالوان         🎗\n️',--Wallhack/Colors Menu
   '🎗      قـائـمـه الأسـلـحـة               🎗\n',--Weapon Menu
   '🎗      قـائـمـه الـسـرعــة               🎗\n',--Speed Menu
   '🎗      قـائـمـه تـفـعـيلات أخـرى     🎗\n️️',--Vegetation Menu Other Function Menu
   '🎗      تـرســيت ســريـع               🎗\n',--Fix 10 min DataOff
   '⛔ خروج 🔴'--exit
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')
if FF == 1 then AntibanLobbyP1() end      
if FF == 2 then AntibanLobbyP2() end
if FF == 3 then OneClickMenu() end
if FF == 4 then WallhackColors() end
if FF == 5 then WeaponMenu() end
if FF == 6 then SpeedMenu() end
if FF == 7 then VegetationOtherMenu() end
if FF == 8 then minDataOff() end
if FF == 9 then exit() end
HOMEDM=-1
end

function AnribanLobbyP1()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("67109633", gg.TYPE_DWORD)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("67109377", gg.TYPE_DWORD)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("131586", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(4)
  gg.searchNumber("135682", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.isVisible(false)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(4)
  gg.searchNumber("134658", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.isVisible(false)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(4)
  gg.searchNumber("131842", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.isVisible(false)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.setVisible(false)
  gg.searchNumber("134658", gg.TYPE_DWORD)
  gg.getResults(50000)
  gg.setVisible(false)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.setVisible(false)
  gg.clearResults() 
end

function AntibanLobbyP2()
local mem = 0
function getMemCpp()
	gg.setRanges(gg.REGION_CODE_APP)
	local alloc = gg.getRangesList("libUE4.so")
	for i in ipairs(alloc) do
		if alloc[i].type == "r-xp" and alloc[i].state == "Xa" then
			if mem == 0 then
				mem = alloc[i].start
				break
			end
		end
	end
end
getMemCpp()
if mem == 0 then
		gg.alert("ERROR")
		os.exit()
end
DEMI = 1
function ANNDJDJDJ()
gg.setVisible(false)
DOLAR = gg.multiChoice({
"✅ حمايه اللوبي سيرفر (2)✅",
"🔙 عودة"--BACK
}, nil, (([[
]])))
if DOLAR == nil then else
if DOLAR[1] == true then anti1() end
if DOLAR[2] == true then HOME() end
end
DEMI= -1
end
function anti1()
gg.searchNumber("67109633",gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0, -1)
gg.getResults(50000)
gg.editAll("RRC633",gg.TYPE_WORD)
gg.clearResults()
gg.searchNumber("67109377",gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0, -1)
gg.getResults(50000)
gg.editAll("RRC377",gg.TYPE_WORD)
gg.clearResults()
gg.searchNumber("RRC633",gg.TYPE_WORD,false,gg.SIGN_EQUAL,0, -1)
gg.getResults(50000)
gg.editAll("67109377",gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("RRC377",gg.TYPE_WORD,false,gg.SIGN_EQUAL,0, -1)
gg.getResults(50000)
gg.editAll("67109633",gg.TYPE_DWORD)
gg.clearResults()
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("67109633", gg.TYPE_DWORD)
revert = gg.getResults(99999)
local t = gg.getResults(99999)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_DWORD then
v.value = "67109633"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("67109633",gg.TYPE_DWORD)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("67109377", gg.TYPE_DWORD)
revert = gg.getResults(99999)
local t = gg.getResults(99999)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_DWORD then
v.value = "67109377"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("67109377",gg.TYPE_DWORD)
end
gg.setVisible(false)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("1.88696049e-40", gg.TYPE_FLOAT)
revert = gg.getResults(247)
local t = gg.getResults(247)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_FLOAT then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_FLOAT)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("134914", gg.TYPE_DWORD)
revert = gg.getResults(147)
local t = gg.getResults(147)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_DWORD then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_DWORD)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("133378", gg.TYPE_DWORD)
revert = gg.getResults(216)
local t = gg.getResults(216)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_DWORD then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_DWORD)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("134402", gg.TYPE_DWORD)
revert = gg.getResults(216)
local t = gg.getResults(216)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_DWORD then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_DWORD)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("579451217772544", gg.TYPE_QWORD)
revert = gg.getResults(1000)
local t = gg.getResults(1000)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_QWORD then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_QWORD)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("572854148005888", gg.TYPE_QWORD)
revert = gg.getResults(1000)
local t = gg.getResults(1000)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_QWORD then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_QWORD)
gg.clearResults()
gg.setVisible(false)
gg.searchNumber("1.88696049e-40", gg.TYPE_FLOAT)
revert = gg.getResults(1000)
local t = gg.getResults(1000)
for i, v in ipairs(t) do
if v.flags == gg.TYPE_FLOAT then
v.value = "0"
v.freeze = true
end
end
gg.addListItems(t)
t = nil
gg.editAll("0",gg.TYPE_FLOAT)
gg.clearResults()
gg.alert('️Antiban Activated 🇰🇼')
anti1()
end

function AntibanLobbyP1()
gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("1.3132476e-38;1.956023e-35;1.1754945e-37::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResultsCount()
  gg.setRanges(gg.REGION_ANONYMOUS | gg.REGION_C_ALLOC | gg.REGION_CODE_APP)
  gg.getResults(5000)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("67109633", gg.TYPE_DWORD)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.searchNumber("67109633", gg.TYPE_DWORD)
  gg.getResults(50000)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setVisible(false)
  gg.clearResults()
gg.alert('️Antiban Activated 🇰🇼')
end

function minDataOff()
gg.clearResults()
gg.setVisible(false)
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("1.1754945e-37", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("9CC",-1,gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.sleep(5000)
gg.setVisible(false)
gg.editAll("1.1754945e-37", gg.TYPE_FLOAT)
gg.clearResults()
end
function OneClickMenu()
FF = gg.choice({
   '➿🔰🔶️ آمنة بنقرة واحدة\n             🔆(قـيــم)\n',--OneClickSafe
   '➿🔰♦️ نقرة واحدة وحشية\n             🔆(قـيــم)\n',--OneClickBrutal
   '🔙 عودة'--BACK
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if FF == 1 then OneClickSafe() end
if FF == 2 then OneClickBrutal() end
if FF == 3 then HOME() end
HOMEDM=-1
end
function OneClickSafe()
skycolormenupro()
MicroAimbot()
LessRecoil()
NoFogV2()
NoGrassv1()
Headshot50()
Zoom8X()
end
function OneClickBrutal()
UltraAimbot()
skycolormenupro()
NoRecoil()
NoFogV2()
NoGrassv1()
Headshot90()
SpeedFallParachute()
MircoSpeedON()
AntiShake()
Zoom15X()
SmailCrosshair()
end

function WeaponMenu()
SSQ = gg.multiChoice({   
   '➿🔰🔫🔸 ثبات سلاح v1\n             🔶(لـوبي/قـيــم)',--LessRecoilv1
   '➿🔰🔫🔸 ثبات سلاح v2\n             🔶(لـوبي)',--LessRecoilv2
   '➿🔰🔫🔸 ثبات سلاح 100\n             🔶(لـوبي/قـيــم)',--NoRecoilv1
   '➿🔰🔫🔸 تصغير نيشان\n             🔆(قـيــم)',--SmallCroshair   
   '➿🔰🔫🔸 عدم اهتـزاز\n             🔆(قـيــم)',--AntiShake       
   '➿🔰🔫🔸 والــشــوت\n             🔆(قـيــم)',--Wallshot       
   '➿🔰🔫🔸 ايم بوت قوي\n             🔆(قـيــم)',--UltraAimbot       
   '➿🔰🔫🔸 ايمبوت خفيف\n             🔶(لـوبي/قـيــم)',--MicroAimbot
   '➿🔰🔫🔸 زحـف سـريع\n             🔆(قـيــم)',--SpeedKnock
   '➿🔰🔫 دمـــج بلس\n             🔆(قـيــم)',--MoreDamage
   '➿🔰🔫 قائمه الهيدشوت\n             🔆(قـيــم)',--HeadshotMenu
   '➿🔰🔫 قائمه الـمـجـك\n             🔆(قـيــم)',--MagicBulletMenu
   '➿🔰🔫 قائمه الـزوم\n             🔆(قـيــم)',--ZoomMenu
   '➿🔰🔫 قائمه الست سكوب\n             🔆(قـيــم)',--ScopeMenu
   '🔙 عودة'--BACK
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SSQ == nil then else
if SSQ[1] == true then LessRecoilv1() end
if SSQ[2] == true then LessRecoilv2() end
if SSQ[3] == true then NoRecoil() end
if SSQ[4] == true then SmallCroshair() end
if SSQ[5] == true then AntiShake() end
if SSQ[6] == true then Wallshot() end
if SSQ[7] == true then UltraAimbot() end
if SSQ[8] == true then MicroAimbot() end
if SSQ[9] == true then SpeedKnock() end 
if SSQ[10] == true then MoreDamage() end 
if SSQ[11] == true then HeadshotMenu() end
if SSQ[12] == true then MagicBulletMenu() end
if SSQ[13] == true then ZoomMenu() end
if SSQ[14] == true then ScopeMenu() end
if SSQ[15] == true then HOME() end
end
end
function NoRecoil()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('1,084,227,584D;1D;0.64999997616F;1.2520827e-32F', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.2520827e-32', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('1.4012985e-43', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.2~0.3;53;30;1::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.2~0.3;1::', gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll('1.4012985e-45', gg.TYPE_FLOAT)
gg.clearResults()
end
function SmallCroshair()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2F;2F;1079446077;1.09375F;1F::17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultsCount()
gg.searchNumber("1079446077", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
end
function AntiShake()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('1,084,227,584D;1D;0.64999997616F;1.2520827e-32F', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.2520827e-32', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('1.4012985e-43', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.2~0.3;53;30;1::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.2~0.3;1::', gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll('1.4012985e-45', gg.TYPE_FLOAT)
gg.clearResults()
end
function Wallshot()
gg.clearResults()
gg.searchNumber("1.0e-7;2.0;2.0;2.0;2.0;1.0::37", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("1.0e-7;0;0;2.0;0;1.0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90.775703430176;0;8;15;16;18;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("1000", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.775703430176;8;27.25;18;16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("140", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber("1.0e-7;1.0e-7;2;2;1::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function UltraAimbot()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1.0;0.5;0.10000000149;200.0::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3.5;1.0;0.5;0.10000000149;200.0::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("999999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;0.5;200;20::", gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll("999999999", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("6.0;2.0;1.0::99", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("101", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;0.5;200;20::", gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll("999999999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end

function NoRecoilv1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('1,084,227,584D;1D;0.64999997616F;1.2520827e-32F', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('1.2520827e-32', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('1.4012985e-43', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('0.2~0.3;53;30;1::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('0.2~0.3;1::', gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll('1.4012985e-45', gg.TYPE_FLOAT)
gg.clearResults()
end
function MicroAimbot()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90.775703430176;0;8;15;16;18;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("1000", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("-1228926272664220957", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1228926272664220957", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("E00", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1228926272664220957", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("-1228926276669014016", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function UltraAimbot()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("2046820354;-336587221:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2046820354", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("2046820353", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("2015175168", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function LessRecoilv1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1,868,784,978;1,850,305,641;28,518;13,212::13", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1,850,305,641", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;0;0;1,028,443,341;1,090,519,040;1,036,831,949;1,057,803,469;1,092,091,904;1,097,859,072::33", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function LessRecoilv2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1D;0.05000000075F;0.10000000149F;0.55000001192F;9.5F;15.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
end
function SitScope()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-4767057191527907328", gg.TYPE_QWORD)
gg.clearResults()
end
function AntiShake()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function SmailCrosshair()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1.2382424e28;-1.4239333e28;-1.1144502e28;-1.8331474e27;-7.1608877e24::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("7.5", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedKnock()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0;7.0064923e-45;1;100;1;2,500,000,000.0;0.10000000149;88", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1.7", gg.TYPE_FLOAT)
gg.clearResults()
end
function MoreDamage()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("16000~99999;3D;0.1;1D::40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("16000~99999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("500000", gg.TYPE_FLOAT)
gg.clearResults()
end
function HeadshotMenu()
SSTT = gg.multiChoice({
   '➿🔰🔫🔸 هيدشوت 50%\n             🔆(قـيــم)',
   '➿🔰🔫🔸 هيدشوت 60%\n             🔆(قـيــم)',
   '➿🔰🔫🔹 هيدشوت 70%\n             🔆(قـيــم)',
   '➿🔰🔫🔹 هيدشوت 80%\n             🔆(قـيــم)',
   '➿🔰🔫🔹 هيدشوت 90%\n             🔆(قـيــم)',
   '🔙 عودة'
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SSTT == nil then else
if SSTT[1] == true then Headshot50() end
if SSTT[2] == true then Headshot60() end
if SSTT[3] == true then Headshot70() end
if SSTT[4] == true then Headshot80() end
if SSTT[5] == true then Headshot90() end
if SSTT[6] == true then WeaponMenu() end
end
end
function Headshot50()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot60()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("175", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot70()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("200", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot80()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("215", gg.TYPE_FLOAT)
gg.clearResults()
end
function Headshot90()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("225", gg.TYPE_FLOAT)
gg.clearResults()
end
function MagicBulletMenu()
SSTT = gg.multiChoice({
   '➿🔰🔫🔹 مجك بولت v1\n             🔆(قـيــم)',
   '➿🔰🔫🔹 مجك بولت v2\n             🔆(قـيــم)',
   '➿🔰🔫🔹 مجك بولت v3\n             🔆(قـيــم)',
   '➿🔰🔫🔹 مجك بولت v4\n             🔆(قـيــم)',
   '🔙 عودة'
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SSTT == nil then else
if SSTT[1] == true then MagicBulletv1() end
if SSTT[2] == true then MagicBulletv2() end
if SSTT[3] == true then MagicBulletv3() end
if SSTT[4] == true then MagicBulletv4() end
if SSTT[5] == true then WeaponMenu() end
end
end
function MagicBulletv1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("69.5;35;33", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("160;140;230", gg.TYPE_FLOAT)
gg.clearResults()
end
function MagicBulletv2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("260", gg.TYPE_FLOAT)
gg.searchNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("260", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1;20.51941871643;2.04908943176;-86.45767974854;-92.2311706543;16.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultCount()
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("240", gg.TYPE_FLOAT)
gg.clearResults()
end
function MagicBulletv3()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("\"0.10000000149;64.50088500977\"", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("\"0.10000000149\"", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("\"55\"", gg.TYPE_FLOAT)
gg.clearResults()
end
function MagicBulletv4()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("8.4077908e-45;25.0;30.5:12", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("250", gg.TYPE_FLOAT)
gg.clearResults()
end
function ZoomMenu()
SSU = gg.multiChoice({
   '➿🔰🔫🔸 تكبير 4X\n             🔆(قـيــم)',
   '➿🔰🔫🔸 تكبير 6X\n             🔆(قـيــم)',
   '➿🔰🔫🔸 تكبير 8X\n             🔆(قـيــم)',
   '➿🔰🔫🔹 تكبير 15X\n             🔆(قـيــم)',
   '🔙 عودة'
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SSU == nil then else
if SSU[1] == true then Zoom4X() end
if SSU[2] == true then Zoom6X() end
if SSU[3] == true then Zoom8X() end
if SSU[4] == true then Zoom15X() end
if SSU[5] == true then WeaponMenu() end
end
end
function Zoom4X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("15", gg.TYPE_FLOAT)
gg.clearResults()
end
function Zoom6X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("14", gg.TYPE_FLOAT)
gg.clearResults()
end
function Zoom8X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("13", gg.TYPE_FLOAT)
gg.clearResults()
end
function Zoom15X()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("9", gg.TYPE_FLOAT)
gg.clearResults()
end
function ScopeMenu()
SST = gg.multiChoice({
   '➿🔰🔫🔹 سيت سكوب \n             🔆(قـيــم)',
   '➿🔰🔫🔹 سيت سكوب يمين \n             🔆(قـيــم)',
   '➿🔰🔫🔹 سيت سكوب يسار \n             🔆(قـيــم)',
   '➿🔰🔫🔹 سيت سكوب للامام \n             🔆(قـيــم)',
   '➿🔰🔫🔹 سيت سكوب يمين \n             🔆(قـيــم)',
   '➿🔰🔫🔹 ستاند سكوب للامام \n             🔆(قـيــم)',
   '➿🔰🔫🔹 ستاند سكوب يسار\n             🔆(قـيــم)',
   '➿🔰🔫 قائمه الغاء سيت سكوب',
   '🔙 عودة'
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SST == nil then else
if SST[1] == true then SitScope() end
if SST[2] == true then SitScopeRight() end
if SST[3] == true then SitScopeLeft() end
if SST[4] == true then SitScopeFront() end
if SST[5] == true then SitScopeRight() end
if SST[6] == true then StandScopeFront() end
if SST[7] == true then StandScopeLeft() end
if SST[8] == true then ScopeDeactivateMenu() end
if SST[9] == true then WeaponMenu() end
end
end
function SitScope()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("-4767057191653227520", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("-4767057191527907328", gg.TYPE_QWORD)
gg.clearResults()
end
function SitScopeRight()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109841324179456", gg.TYPE_QWORD)
gg.clearResults()
end
function SitScopeLeft()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841269983040", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109839176695808", gg.TYPE_QWORD)
gg.clearResults()
end
function SitScopeFront()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4848124999984742400", gg.TYPE_QWORD)
gg.clearResults()
end
function StandScopeLeft()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109952939150800", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952939150800", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952939150800", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109950845845504", gg.TYPE_QWORD)
gg.clearResults()
end
function StandScopeFront()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("4138667321167981973", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4848124999984742400", gg.TYPE_QWORD)
gg.clearResults()
end
function ScopeDeactivateMenu()
SSTT = gg.multiChoice({   
   '➿🔰🔫🔹 سيت سكوب يسار \n             🔆(قـيــم)',
   '➿🔰🔫🔹 سيت سكوب للامام \n             🔆(قـيــم)',
   '➿🔰🔫🔹 سيت سكوب يمين \n             🔆(قـيــم)',
   '➿🔰🔫🔹 ستاند سكوب للامام \n             🔆(قـيــم)',
   '➿🔰🔫🔹 ستاند سكوب يسار \n             🔆(قـيــم)',
   '➿🔰🔫🔹 قائمه الغاء سيت سكوب\n             🔆(قـيــم)',
   '🔙 عودة'
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SSTT == nil then else
if SSTT[1] == true then SITSCOPEOFF() end
if SSTT[2] == true then SITSCOPEROFF() end
if SSTT[3] == true then SITSCOPELOFF() end
if SSTT[4] == true then STANDSCOPEOFF() end
if SSTT[5] == true then STANDSCOPEROFF() end
if SSTT[6] == true then STANDSCOPELOFF() end
if SSTT[7] == true then ScopeMenu() end
end
end
function SITSCOPEOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("-4767057191527907328", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("-4767057191653227520", gg.TYPE_QWORD)
gg.clearResults()
end
function SITSCOPEROFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109841324179456", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841324179456", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109841324179456", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109841269983040", gg.TYPE_QWORD)
gg.clearResults()
end
function SITSCOPELOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109839176695808", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109839176695808", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109839176695808", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109841269983040", gg.TYPE_QWORD)
gg.clearResults()
end
function STANDSCOPEOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4848124999984742400", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4138667321167981973", gg.TYPE_QWORD)
gg.clearResults()
end
function STANDSCOPEROFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109952993329152", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952993329152", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109952993329152", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109952939150800", gg.TYPE_QWORD)
gg.clearResults()
end
function STANDSCOPELOFF()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("4548109950845845504", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109950845845504", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber("4548109950845845504", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("4548109952939150800", gg.TYPE_QWORD)
gg.clearResults()
end

function VegetationOtherMenu()
SSR = gg.multiChoice({
'➿🔰🌱🔸 رؤيه واضحه\n             🔶(لـوبي)',--NoFog
'➿🔰🌱🔸 رؤيه واضحهv2\n             🔆(قـيــم)',--NoFogv2
'➿🔰🌱🔸 لا عشب \n             🔆(قـيــم)',--NoGrass
'➿🔰🌱🔸 لا عشب v2\n             🔶(لـوبي)',--NoGrassv2
'➿🔰🌱🔸 ازاله الاشجار والعشب\n             🔆(قـيــم)',--NoGrassTrees
'➿🔰🗼🔸 انتينا مستمر\n             🔆(قـيــم)',--AlwaysAntenna
'➿🔰🦅🔸 رؤيه ايـباد\n             🔆(قـيــم)',--IpadView
'➿🔰🛫🔸 طيران سياره\n             🔆(قـيــم)',--FlyCar
'🔙 عودة'--BACK
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SSR == nil then else 
if SSR[1] == true then NoFog() end
if SSR[2] == true then NoFogV2() end
if SSR[3] == true then NoGrassv1() end
if SSR[4] == true then NoGrassv2() end
if SSR[5] == true then NoGrassTrees() end
if SSR[6] == true then AlwaysAntenna() end
if SSR[7] == true then IpadView() end
if SSR[8] == true then FlyCar() end
if SSR[9] == true then HOME() end
end
end
function NoFogV2()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-486470348;-298841535;-409731072:9", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-298841535", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("08")
gg.getResults(551)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
end
function NoFog()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__ExponentialHeightFog", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
end
function NoGrassv1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("8.0F;1.20000004768F;0.80000001192F;1.5F;0.80000001192F;1.5F::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function NoGrassv2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__MaterialExpressionLandscapeGrassOutput", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
end
function NoGrassTrees()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.00390625;1;0.99900001287;2", gg.TYPE_FLOAT, false)
gg.searchNumber("1", gg.TYPE_FLOAT, false)
gg.getResults(30)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function AlwaysAntenna()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
gg.clearResults()
end
function IpadView()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2.8025969e-45;220;25;178;15;100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("440", gg.TYPE_FLOAT)
gg.clearResults()
end
function FlyCar()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.76000005007;0.96078431606;1;0.74509805441::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.74509805441", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("45F;15F;20F;2500F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("500", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("45F;15F;20F;2500F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999999)
gg.editAll("700", gg.TYPE_FLOAT)
gg.clearResults()
end
function HighJump()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("3", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("443", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("2500", gg.TYPE_FLOAT)
gg.clearResults()
end

function SpeedMenu()
SS = gg.multiChoice({
   '➿🔰🔫 اصلاح الاسحله \n             🔆(قـيــم)',--FixDamageMenu
   '[ON]\n➿🔰🏃🔹 تشغيل سرعه فلاش \n             🔆(قـيــم)',--SpeedhackON
   '[OFF]\n➿🔰🏃🔹 إطفاء سرعه فلاش \n             🔆(قـيــم)',--SpeedhackOFF
   '[ON]\n➿🔰🏃🔸 تشغيل سرعه خفيفه v1\n             🔆(قـيــم)',--MircoSpeedON
   '[OFF]\n➿🔰🏃🔸 إطفاء سرعه خفيفه v1\n             🔆(قـيــم)',--MircoSpeedOFF
   '[ON]\n➿🔰🏃🔸 تشغيل سرعه خفيفه v2\n             🔆(قـيــم)',--MircoSpeedONv2
   '[OFF]\n➿🔰🏃🔸 إطفاء سرعه خفيفه v2\n             🔆(قـيــم)',--MircoSpeedOFFv2   
   '➿🔰✈️🔸 سرعه برشوت فقط v1\n             🔆(قـيــم)',--SpeedParachutev1
   '➿🔰✈️🔸 سرعه برشوت فقط v2\n             🔆(قـيــم)',--SpeedParachutev2
   '➿🔰🚙🔸 سرعه جيب \n             🔆(قـيــم)',--SpeedJeep
   '➿🔰🚙🔸 سرعه ساديا \n             🔆(قـيــم)',--SpeedCar
   '➿🔰🤸🔹 نقزه عاليه \n             🔆(قـيــم)',--HighJump
   '🔙 عودة'--BACK
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if SS == nil then else
if SS[1] == true then FixDamageMenu() end
if SS[2] == true then SpeedhackON() end 
if SS[3] == true then SpeedhackOFF() end 
if SS[4] == true then MircoSpeedON() end 
if SS[5] == true then MircoSpeedOFF() end 
if SS[6] == true then MircoSpeedONV2() end 
if SS[7] == true then MircoSpeedOFFV2() end 
if SS[8] == true then SpeedParachuteV1() end  
if SS[9] == true then SpeedParachuteV2() end  
if SS[10] == true then SpeedJeep() end 
if SS[11] == true then SpeedCar() end
if SS[12] == true then HighJump() end  
if SS[13] == true then HOME() end
end
end

function SpeedParachuteV1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.75;150;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("30", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("0.75;150;30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.75", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedParachuteV2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1024;5000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(7242)
gg.editAll("999999", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedhackON()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,296,744,149,883,614,555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll(" -1,296,744,153,870,237,696", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-1,904,987,454,010,553,855', gg.TYPE_QWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(99)
gg.editAll('-1,904,987,454,002,165,247', gg.TYPE_QWORD)
gg.clearResults()
end
function SpeedhackOFF()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,296,744,153,870,237,696", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll(" -1,296,744,149,883,614,555", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-1,904,987,454,002,165,247', gg.TYPE_QWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(99)
gg.editAll('-1,904,987,454,010,553,855', gg.TYPE_QWORD)
gg.clearResults()
end
function MircoSpeedON()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-1,296,744,149,883,614,555', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(787)
gg.editAll(' -1,296,744,153,870,237,696', gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber('-1,904,987,454,010,553,855', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(532)
gg.editAll('-1,904,987,454,002,165,247', gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('1;1;1;0.0001;20;0.0005;0.4::50', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber('1', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(54)
gg.editAll('1.08', gg.TYPE_FLOAT)
gg.clearResults()
end
function MircoSpeedOFF()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-1,296,744,153,870,237,696', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(444)
gg.editAll('-1,296,744,149,883,614,555', gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber('-1,904,987,454,002,165,247', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll('-1,904,987,454,010,553,855', gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('1.08;0.0001;20;0.0005;0.4::50', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber('1.08', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('1', gg.TYPE_FLOAT)
gg.clearResults()
end
function MircoSpeedONV2()
gg.clearResults() 
  gg.setRanges(gg.REGION_ANONYMOUS) 
  gg.searchNumber("1;1;1;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1) 
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1) 
  gg.getResults(100) 
  gg.editAll("1.2,5", gg.TYPE_FLOAT) 
  gg.clearResults() 
end
function MircoSpeedOFFV2()
gg.clearResults() 
gg.setRanges(gg.REGION_ANONYMOUS) 
gg.searchNumber("1.25;1.25;1.25;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1) 
gg.searchNumber("1.25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1) 
gg.getResults(100) 
gg.editAll("1", gg.TYPE_FLOAT) 
gg.clearResults() 
end
function SpeedJeep()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedCar()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1000;10;4D;4D;50;5;2;0.03::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.03", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.03", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.03", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedParachute()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.75;150;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("30", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("0.75;150;30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.75", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
end
function SpeedFallParachute()
gg.clearResults()
gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber("2048D;4D;1F;1F;1D:30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultsCount()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3000;5000;1024;1000::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6284)
gg.editAll("999999", gg.TYPE_FLOAT)
gg.clearResults()
end
function FixDamageMenu()
FD = gg.multiChoice({
  '➿🔰🔫 Fix All Weapon',
  '➿🔰🔫 M416',
  '➿🔰🔫 SCAR',
  '➿🔰🔫 M16A4',
  '➿🔰🔫 AKM',
  '➿🔰🔫 KAR',
  '➿🔰🔫 AWM',
  '➿🔰🔫 SKS',
  '➿🔰🔫 MINI',
  '➿🔰🔫 M249',
  '➿🔰🔫 DP28',
  '➿🔰🔫 QBZ',
  '➿🔰🔫 G36',
  '➿🔰🔫 AUG',
  '➿🔰🔫 BERYL',
  '➿🔰🔫 GROZA',
  '➿🔰🔫 MUTAN',
  '➿🔰🔫 M24',
  '➿🔰🔫 MK',
  '➿🔰🔫 SLR',
  '➿🔰🔫 QBU',
  '🔙 عودة'
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
if FD == nil then else
if FD[1] == true then fixallweaponnnn() end
if FD[2] == true then M416D() end
if FD[3] == true then SCARD() end
if FD[4] == true then M16A4D() end
if FD[5] == true then AKMD() end
if FD[6] == true then KARD() end
if FD[7] == true then AWMD() end
if FD[8] == true then SKSD() end
if FD[9] == true then MINID() end
if FD[10] == true then M249D() end
if FD[11] == true then DP28D() end
if FD[12] == true then FD1() end
if FD[13] == true then FD2() end
if FD[14] == true then FD3() end
if FD[15] == true then FD4() end
if FD[16] == true then FD5() end
if FD[17] == true then FD6() end
if FD[18] == true then FD7() end
if FD[19] == true then FD8() end
if FD[20] == true then FD9() end
if FD[21] == true then FD10() end
if FD[22] == true then SpeedMenu() end
end
end
function fixallweaponnnn()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90000;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("90000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09229999781", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.86", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("94000;0.08570999652", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("94000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.07999999821", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("78000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("78000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.2;2.5::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("79000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("79000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("85300;0.09000000358", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("85300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("84000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("84000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("94500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("94500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M416D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function SCARD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M16A4D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90000;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("90000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function AKMD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function KARD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end 
function AWMD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.2;2.5::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function SKSD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function MINID()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M249D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function DP28D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function FD1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('87000;0.09229999781', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('87000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('87000;0.86', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('87000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD3()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('94000;0.08570999652', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('94000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD4()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD5()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('71500;0.07999999821', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD6()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('78000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('78000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD7()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('79000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('79000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD8()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('85300;0.09000000358', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('85300', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD9()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('84000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('84000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end
function FD10()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('94500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('94500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('37401', gg.TYPE_FLOAT)
gg.clearResults()
end

function whitealldevices()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-5.1210619E-18;1:20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1000)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
end
function ItemWallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-7.00649232e-45",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.refineAddress("38",-1,gg.TYPE_FLOAT,gg.SIGN_EQUAL,0,-1)
gg.getResults(7243)
gg.editAll("5444",gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-3.12839322e-39",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.refineAddress("38",-1,gg.TYPE_FLOAT,gg.SIGN_EQUAL,0,-1)
gg.getResults(7243)
gg.editAll("5444",gg.TYPE_FLOAT)
gg.clearResults()
end
      
function WallhackColors()
  WHMN2 = gg.choice({
    "⁦➿🔰📚 قائمة الألوان",
    "➿🔰👁️ Snapdragon 865",
    "➿🔰👁️ Snapdragon 855",
    "➿🔰👁️ Snapdragon 855 v2",
    "➿🔰👁️ Snapdragon 845",
    "➿🔰👁️ Snapdragon 845 v2",
    "➿🔰👁️ Snapdragon 835",
    "➿🔰👁️ Snapdragon 820",
    "➿🔰👁️ Snapdragon 810",
    "➿🔰👁️ Snapdragon 710",
    "➿🔰👁️ Snapdragon All 6XX",
    "➿🔰👁️ Snapdragon 675 v1",
    "➿🔰👁️ Snapdragon 675 v2",
    "➿🔰👁️ Snapdragon 660",
    "➿🔰👁️ Snapdragon 636",
    "➿🔰👁️ Snapdragon 625 v1",    
    "➿🔰👁️ Snapdragon 625 v2",
    "➿🔰👁️ Snapdragon 430",
    "➿🔰👁️ Snapdragon 425",
    "➿🔰👁️ جميع Snapdragons",
    "➿🔰👁️🧹 ولهاك الاسحله",
    "➿🔰👁️ إصلاح الوميض 430-835",
    "➿🔰👁️ إصلاح الوميض 845-855",
    "➿🔰👁️ إصلاح الوميض v3",
    "🔙 عودة"
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
  if WHMN2 == nil then
  else
    if WHMN2 == 1 then
      ColorMenu()
    end
    if WHMN2 == 2 then
      WH865()
    end    
    if WHMN2 == 3 then
      WH855()
    end
    if WHMN2 == 4 then
      WH855V2()
    end
    if WHMN2 == 5 then
      WH845()
    end
    if WHMN2 == 6 then
      WH855V2()
    end
    if WHMN2 == 7 then
      WH835()
    end
    if WHMN2 == 8 then
      WH820()
    end
    if WHMN2 == 9 then
      WH810()
    end
    if WHMN2 == 10 then
      WH710()
    end
    if WHMN2 == 11 then
      WH6XX()
    end
    if WHMN2 == 12 then
      WH675()
    end
    if WHMN2 == 13 then
      WH6752()
    end
    if WHMN2 == 14 then
      WH660()
    end
    if WHMN2 == 15 then
      WH636()
    end
    if WHMN2 == 16 then
      WH625()
    end
    if WHMN2 == 17 then
      WH6252()
    end
    if WHMN2 == 18 then
      WH430()
    end
    if WHMN2 == 19 then
      WH425()
    end    
    if WHMN2 == 20 then
      ALLD()
    end
    if WHMN2 == 21 then
      ItemWallhack()
    end
    if WHMN2 == 22 then
      FIXWH()
    end
    if WHMN2 == 23 then
      FIXWH2()
    end
    if WHMN2 == 24 then
      FIXSCOPE()
    end   
    if WHMN2 == 25 then
      HOME()
    end
  end
  HOMEDM = -1
end
function ColorMenu()
  CLRMN2 = gg.choice({
    "➿🔰📚 قائمة لون السماء",
    "➿🔰⚪ لون ابيض كل الاجهزه",
    "➿🔰🔴 لون أحمر HDR",
    "➿🔰🟡 اللون الاصفر 865",    
    "➿🔰🔴 أحمر اللون 855",
    "➿🔰🔵 اللون الأزرق 855",
    "➿🔰🟡 اللون الاصفر 855",    
    "➿🔰🟢 اللون الاخضر 855",
    "➿🔰🔵 اللون الأزرق 845",    
    "➿🔰🟢 اللون الاخضر 845",        
    "➿🔰⚪ لون أبيض 845",            
    "➿🔰🟡 اللون الاصفر 845",
    "➿🔰🔴 أحمر اللون 845",    
    "➿🔰🟡 اللون الاصفر 835",                        
    "➿🔰🔴 أحمر اللون 835",                                            
    "➿🔰⚫ لون أسود",
    "➿🔰⚪ لون أبيض",    
    "➿🔰🟢 اللون الاخضر 675",
    "➿🔰🔵 اللون الأزرق 675",    
    "➿🔰⚪ لون أبيض 675",                                                                                                                                                                                    
    "➿🔰🟡 اللون الاصفر 660", 
    "➿🔰🔴 أحمر اللون 660",                                                                                                                                                                                                                                                                
    "➿🔰🟡 اللون الاصفر 625",                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               
    "➿🔰🔴 أحمر اللون 625",
    "➿🔰🟡 اللون الاصفر 425",    
    "➿🔰🔴 أحمر اللون 425",                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        
    "🔙 عودة️"
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
  if CLRMN2 == nil then
  else
    if CLRMN2 == 1 then
      skycolormenupro()
    end
    if CLRMN2 == 2 then
      whitealldevices()
    end
    if CLRMN2 == 3 then
      redHDRcolor()
    end
    if CLRMN2 == 4 then
      YELL865()
    end   
    if CLRMN2 == 5 then
      RED855()
    end    
    if CLRMN2 == 6 then
      BLUE845()
    end    
    if CLRMN2 == 7 then
      YELL855()
    end    
    if CLRMN2 == 8 then
      GREEN845()
    end
    if CLRMN2 == 9 then
      BLUE845()
    end    
    if CLRMN2 == 10 then
      GREEN845()
    end        
    if CLRMN2 == 11 then
      WHITEALL()
    end            
    if CLRMN2 == 12 then
      YELL845()
    end                
    if CLRMN2 == 13 then
      RED845()
    end                    
    if CLRMN2 == 14 then
      YELL835()
    end                            
    if CLRMN2 == 15 then
      RED835()
    end
    if CLRMN2 == 16 then
      BLACKALL()
    end    
    if CLRMN2 == 17 then
      WHITEALL()
    end        
    if CLRMN2 == 18 then
      GREEN675()
    end 
    if CLRMN2 == 19 then
      BLUE675()
    end    
    if CLRMN2 == 20 then
      WHITE675()
    end                    
    if CLRMN2 == 21 then
      YELL625()
    end                                    
    if CLRMN2 == 22 then
      RED625()
    end
    if CLRMN2 == 23 then
      YELL625()
    end
    if CLRMN2 == 24 then
      RED625()
    end    
    if CLRMN2 == 25 then
      YELL425()
    end
    if CLRMN2 == 26 then
      RED425()
    end                                                                                                                                                                           
    if CLRMN2 == 27 then
      WallhackColors()
    end
  end
  HOMEDM = -1
end
function skycolormenupro()
  CLRMN6752 = gg.choice({
    "➿🔰🔵 سماء صافية",
    "➿🔰⚪ وايت سكاي",
    "➿🔰⚫ السماء السوداء",
    "🔙 عودة"
}, nil, '       ⫷════════════•❁❀❁•═══════════⫸\n     °•✮•°            🇰🇼  سـكـربـت هـــدام  🇰🇼         °•✮•°            \n     °•✮•°              SECREPT: ALSHAYA            °•✮•°            \n     °•✮•°            PHONE: 90966060              °•✮•°            \n     °•✮•°        TELEGRAM: FADELALSHAYA      °•✮•°            \n⫷════════════•❁❀❁•════════════⫸')      
  if CLRMN6752 == nil then
  else
    if CLRMN6752 == 1 then
      clearsky()
    end
    if CLRMN6752 == 2 then
      whitesky()
    end
    if CLRMN6752 == 3 then
      blackskyall()
    end
    if CLRMN6752 == 4 then
      ColorMenu()
    end
  end
  HOMEDM = -1
end

function YELL865()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1,194,347,012;8,196;8,200;524,292;1,080,039,424", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("6", gg.TYPE_DWORD)
gg.clearResults()
end
function WH865()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.12020508e-19;3.76158192e-37;2.0;0.24022650719;0.69314718246::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.getResultsCount()
gg.addListItems({ -- table(8db2da3)
	[1] = { -- table(c4c48a0)
		['address'] = 0x7fa32e748,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(816201e)
	[1] = { -- table(46900ff)
		['address'] = 0x7fa32ea90,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(ce4e515)
	[1] = { -- table(e80202a)
		['address'] = 0x7fa332658,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(8568bb8)
	[1] = { -- table(3bbbd91)
		['address'] = 0x7fa335d50,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(3a810f7)
	[1] = { -- table(9c4ab64)
		['address'] = 0x7fa336254,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(1e88a82)
	[1] = { -- table(cc2c593)
		['address'] = 0x7fa33814c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(79f8dc9)
	[1] = { -- table(e98ccce)
		['address'] = 0x7fa338594,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(21802fc)
	[1] = { -- table(a3d85)
		['address'] = 0x7fa338a54,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(93b540b)
	[1] = { -- table(d6052e8)
		['address'] = 0x7fa338b54,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(90da7a6)
	[1] = { -- table(44925e7)
		['address'] = 0x7fa33a668,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(d7983d)
	[1] = { -- table(85c9832)
		['address'] = 0x7fa33e050,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(9089700)
	[1] = { -- table(aa7b39)
		['address'] = 0x7fa3441b8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(3faeadf)
	[1] = { -- table(ce0232c)
		['address'] = 0x7fa3442b0,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(acafb8a)
	[1] = { -- table(7cd55fb)
		['address'] = 0x7fa344358,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(ba35871)
	[1] = { -- table(1e54656)
		['address'] = 0x7fa344740,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(5a1abc4)
	[1] = { -- table(5c40aad)
		['address'] = 0x7fa344e88,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(b2a8973)
	[1] = { -- table(8efc030)
		['address'] = 0x7fa345970,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(62eca2e)
	[1] = { -- table(11a49cf)
		['address'] = 0x7fa348054,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(b08e265)
	[1] = { -- table(6e15b3a)
		['address'] = 0x7fa348eac,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(5df6548)
	[1] = { -- table(eaa3fe1)
		['address'] = 0x7fa348f28,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(7fa3c7)
	[1] = { -- table(d298df4)
		['address'] = 0x7fa34914c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(5b41792)
	[1] = { -- table(9c8b563)
		['address'] = 0x7fa34cb6c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(2f20a19)
	[1] = { -- table(8781ade)
		['address'] = 0x7fa34d488,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(9c4a78c)
	[1] = { -- table(6102ed5)
		['address'] = 0x7fa34d6c8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(9756ddb)
	[1] = { -- table(dab078)
		['address'] = 0x7fa354234,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(7a6a7b6)
	[1] = { -- table(5d30cb7)
		['address'] = 0x7fa354354,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(6e0638d)
	[1] = { -- table(7ed8942)
		['address'] = 0x7fa355054,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(89f1690)
	[1] = { -- table(7fcab89)
		['address'] = 0x7fa35576c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(860dbaf)
	[1] = { -- table(c870bbc)
		['address'] = 0x7fa355b70,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(946fe9a)
	[1] = { -- table(9e983cb)
		['address'] = 0x7fa357ad4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(a6142c1)
	[1] = { -- table(66a66)
		['address'] = 0x7fa35882c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(30b1654)
	[1] = { -- table(57e49fd)
		['address'] = 0x7fa35aa90,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(944a143)
	[1] = { -- table(82d43c0)
		['address'] = 0x7fa35b030,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(8ae603e)
	[1] = { -- table(1860e9f)
		['address'] = 0x7fa35e438,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(741bbb5)
	[1] = { -- table(12c424a)
		['address'] = 0x7fa35e870,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(5b7cad8)
	[1] = { -- table(a1f5e31)
		['address'] = 0x7fa35ec38,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(6653297)
	[1] = { -- table(64abc84)
		['address'] = 0x7fa35ed54,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(172d0a2)
	[1] = { -- table(8c06133)
		['address'] = 0x7fa35f06c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(d82a269)
	[1] = { -- table(45154ee)
		['address'] = 0x7fa35f1e4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(eb181c)
	[1] = { -- table(719fc25)
		['address'] = 0x7fa35f278,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(89cc3ab)
	[1] = { -- table(f9f9a08)
		['address'] = 0x7fa35f290,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(80b13c6)
	[1] = { -- table(de1ef87)
		['address'] = 0x7fa35f6c8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(10c8add)
	[1] = { -- table(894a652)
		['address'] = 0x7fa362238,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(8c5a220)
	[1] = { -- table(84bf7d9)
		['address'] = 0x7fa362b34,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(76f487f)
	[1] = { -- table(3b2c04c)
		['address'] = 0x7fa36302c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(7f2adaa)
	[1] = { -- table(eb9ed9b)
		['address'] = 0x7fa3636c8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(923c911)
	[1] = { -- table(fa5fa76)
		['address'] = 0x7fa363894,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(246cce4)
	[1] = { -- table(6eae54d)
		['address'] = 0x7fa36518c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(cde7513)
	[1] = { -- table(215d350)
		['address'] = 0x7fa366474,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(88de24e)
	[1] = { -- table(5b14f6f)
		['address'] = 0x7fa366854,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(59c7105)
	[1] = { -- table(ce9d55a)
		['address'] = 0x7fa366e54,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(110bc68)
	[1] = { -- table(df81881)
		['address'] = 0x7fa366f70,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(fdbd67)
	[1] = { -- table(693714)
		['address'] = 0x7fa3672e4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(ccdb5b2)
	[1] = { -- table(a9ec903)
		['address'] = 0x7fa367c50,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(dce56b9)
	[1] = { -- table(b5d7afe)
		['address'] = 0x7fa367f34,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(9ec54ac)
	[1] = { -- table(474a575)
		['address'] = 0x7fa368494,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(146557b)
	[1] = { -- table(1200f98)
		['address'] = 0x7fa368f74,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(193ebd6)
	[1] = { -- table(b5ace57)
		['address'] = 0x7fa36ad38,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(d490e2d)
	[1] = { -- table(e3aef62)
		['address'] = 0x7fa36b558,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(e0d39b0)
	[1] = { -- table(1556029)
		['address'] = 0x7fa36b578,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(7ab314f)
	[1] = { -- table(f0440dc)
		['address'] = 0x7fa36c254,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(ed708ba)
	[1] = { -- table(13936b)
		['address'] = 0x7fa36e330,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(247eb61)
	[1] = { -- table(5cf686)
		['address'] = 0x7fa37c6b4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(315cf74)
	[1] = { -- table(d36dc9d)
		['address'] = 0x7fa380da4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(56d04e3)
	[1] = { -- table(17a6ee0)
		['address'] = 0x7fa3835b4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(f86505e)
	[1] = { -- table(f610c3f)
		['address'] = 0x7fa38432c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(1e60255)
	[1] = { -- table(663146a)
		['address'] = 0x7fa38642c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(bdb39f8)
	[1] = { -- table(5d16ed1)
		['address'] = 0x7fa386f34,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(5ae4437)
	[1] = { -- table(d85fda4)
		['address'] = 0x7fa3871ec,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(42dc6c2)
	[1] = { -- table(618ecd3)
		['address'] = 0x7fa387334,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(6122709)
	[1] = { -- table(7958d0e)
		['address'] = 0x7fa388424,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(5e95d3c)
	[1] = { -- table(72d2ac5)
		['address'] = 0x7fa388854,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(bc7234b)
	[1] = { -- table(78d1128)
		['address'] = 0x7fa38bf38,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(45a2fe6)
	[1] = { -- table(6e2a927)
		['address'] = 0x7fa38c07c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(942ed7d)
	[1] = { -- table(1896472)
		['address'] = 0x7fa38eeb8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(fc6dd40)
	[1] = { -- table(e95e479)
		['address'] = 0x7fa38f438,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(159961f)
	[1] = { -- table(9dc8d6c)
		['address'] = 0x7fa38feb8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(2bd0fca)
	[1] = { -- table(58b753b)
		['address'] = 0x7fa38ff30,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(3eaa9b1)
	[1] = { -- table(a845e96)
		['address'] = 0x7fa3901d8,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(bf91e04)
	[1] = { -- table(b4f2fed)
		['address'] = 0x7fa39034c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(82550b3)
	[1] = { -- table(3ec1670)
		['address'] = 0x7fa390d54,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(810aa6e)
	[1] = { -- table(21a450f)
		['address'] = 0x7fa390d98,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(fab6fa5)
	[1] = { -- table(6a0ff7a)
		['address'] = 0x7fa391950,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(4c84388)
	[1] = { -- table(1086121)
		['address'] = 0x7fa394058,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(39bc707)
	[1] = { -- table(6621034)
		['address'] = 0x7fa394274,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(8bc03d2)
	[1] = { -- table(7a3cca3)
		['address'] = 0x7fa394378,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(44b1359)
	[1] = { -- table(3b28b1e)
		['address'] = 0x7fa394658,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(4c331cc)
	[1] = { -- table(108c15)
		['address'] = 0x7fa394c34,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(e342d1b)
	[1] = { -- table(fd79eb8)
		['address'] = 0x7fa396438,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(936dff6)
	[1] = { -- table(2de7ff7)
		['address'] = 0x7fa396938,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(26728cd)
	[1] = { -- table(fe90582)
		['address'] = 0x7fa397738,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(8038cd0)
	[1] = { -- table(74a84c9)
		['address'] = 0x7fa397dc0,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(e7f76ef)
	[1] = { -- table(e5ca5fc)
		['address'] = 0x7fa397e34,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(52dc2da)
	[1] = { -- table(476930b)
		['address'] = 0x7fa398854,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(fe90401)
	[1] = { -- table(f3532a6)
		['address'] = 0x7fa399ed4,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(a31b894)
	[1] = { -- table(3e0df3d)
		['address'] = 0x7fa39cc34,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(ffc5883)
	[1] = { -- table(9bbca00)
		['address'] = 0x7fa39cc7c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(d65f07e)
	[1] = { -- table(321f9df)
		['address'] = 0x7fa39d060,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(a39b8f5)
	[1] = { -- table(36c968a)
		['address'] = 0x7fa39d36c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.addListItems({ -- table(548d918)
	[1] = { -- table(2b9ef71)
		['address'] = 0x7fa39d67c,
		['flags'] = 16, -- gg.TYPE_FLOAT
		['freeze'] = true,
		['value'] = 120,
	},
})
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.25414346e-19;1.7506772e-39;2.0;1.8425141e-39;1.74488844e-39::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
ColorMenu()
end
function redHDRcolor()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("298", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function clearsky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.clearResults()
gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.clearResults()
end
function blackskyall()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("000", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-90", gg.TYPE_FLOAT)
gg.clearResults()
end
function whitesky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.5;0.16513200104", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
lgg.searchNumber("1.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("-99", gg.TYPE_FLOAT)
gg.clearResults()
end
function GREEN675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("69,897;147,457;69,739", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function WHITE675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8202", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(330)
  gg.editAll("14", gg.TYPE_DWORD)
  gg.clearResults()
end
function BLUE675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.sleep(140)
  gg.refineNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.sleep(140)
  gg.refineAddress("2D0", -1, gg.TYPE_QWORD, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("5,129,821,174,980,681,738", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1401)
  gg.editAll("5,129,821,174,980,673,543", gg.TYPE_QWORD)
  gg.clearResults()
end
function RED425()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("\"8204\"", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.processResume()
  gg.refineAddress("\"408\"", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  revert = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("\"96\"", gg.TYPE_DWORD)
  local t = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.addListItems(t)
  t = nil
  gg.clearResults()
end
function YELL425()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("\"8204\"", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.processResume()
  gg.refineAddress("\"408\"", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  revert = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("\"95\"", gg.TYPE_DWORD)
  local t = gg.getResults(10, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.addListItems(t)
  t = nil
  gg.clearResults()
end
function RED625()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("8199", gg.TYPE_DWORD)
  gg.clearResults()
end
function YELL845()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function YELL625()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8196D;8192D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end
function WHITEALL()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function BLACKALL()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("-999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function RED835()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function YELL835()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("8198", gg.TYPE_DWORD)
  gg.clearResults()
end
function RED845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function WHITE845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("256;8200;26", 4, false, 536870912, 0, -1)
  gg.searchNumber("8200", 4, false, 536870912, 0, -1)
  gg.getResults(5)
  gg.editAll("5", 4)
  gg.clearResults()
end
function YELL855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("8198", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1000)
  gg.editAll("8199", gg.TYPE_DWORD)
  gg.clearResults()
end
function GREEN845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function BLUE845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0B0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
end
function WHITE855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("0A0")
  gg.getResults(10)
  gg.editAll("8197", gg.TYPE_DWORD)
  gg.clearResults()
end
function RED855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.clearResults()
end
function FIXWH()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function FIXWH2()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_BAD)
  gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
end
function WH855V2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-2 145 644 340", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("7E0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("-2 147 483 636", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("4F8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults() 
ColorMenu()
end
function WH6XX()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-2 147 086 191", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("4C8", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("-2 145 644 352", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("7E0", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1 168 777 216", gg.TYPE_DWORD)
gg.clearResults()
ColorMenu()
end
function FIXSCOPE()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", 16)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(120)
gg.editAll("9999", 16)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("4140D;1.1202011e-19~1.1202013e-19;1.1202015e-19~1.1202017e-19;2::", 16, false, gg.SIGN_EQUAL, 0, -1)                                                                                                                                                                                                                                                                                --SosnA
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(102)
gg.editAll("99999", 16)
gg.clearResults()
end
function WH425()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2.9427268e-44;2.0;3.0828566e-44;-1.0;3.2229865e-44;3.3631163e-44;3.643376e-44:97", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.searchNumber("3.1529215e-43;2.0F;3.1669345e-43F;3.1809475e-43:49", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll("120", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("227;1,073,741,824;1,073,741,824;-1,082,130,432;1,073,741,824:49", 4, false, 536870912, 0, -1)
  gg.searchNumber("1,073,741,824", 4, false, 536870912, 0, -1)
  gg.getResults(100)
  gg.editAll("1,123,024,896", 4)
  gg.clearResults()
  ColorMenu()
end
function WH430()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH625()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH6252()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.79227989e21;-5.56955884e-40;2.0;1.39125666e-19;2.0:9285", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(50)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH636()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH660()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  ColorMenu()
end
function WH675()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("274,677,779D;2.25000452995;2;1.6623054e-19", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("218D;3.7615819e-37;2;-1;1", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("95D;2;9.2194229e-41", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(15)
  gg.editAll("130", 16)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("206D;3.7615819e-37;2;-1;1", 16, false, 536870912, 0, -1)
  gg.searchNumber("2", 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll("130", 16)
  gg.clearResults()
  ColorMenu()
end
function WH6752()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("200")
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("930")
  gg.getResults(999)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH710()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH810()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH820()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH835()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH845()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("200", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(25)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("930", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(25)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function WH855()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("95D;2;9.2194229e-41::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end
function ALLD()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO or gg.REGION_BAD)
  gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  ColorMenu()
end

function exit()
gg.setVisible(true)
os.exit()
end

startscript()
while true do
 if gg.isVisible(true) then
   HOMEDM = 1
   gg.setVisible(false)
 end
 if HOMEDM == 1 then
   HOME()
 end
end
