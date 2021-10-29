local key = _G.Key
local check = "https://whitelistseenhubv2.000webhostapp.com/Check4.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/suwanlag/DEHED-HUB/main/script3.lua"))()
else
game.Players.LocalPlayer:Kick("Invalid Key! Please Rejoin And Try Again.")
end
