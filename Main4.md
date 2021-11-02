local key = _G.Key
local check = "https://whitelistseenhubv2.000webhostapp.com/Check3.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/suwanlag/DEHED-HUB/main/script4.lua"))()
else
game.Players.LocalPlayer:Kick("ไม่มีkeyรันหาแม่มึงอ่ะไอโง่")
end
