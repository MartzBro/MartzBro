local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local Window = Library.CreateLib("MartinHub (Not Finished)", "Ocean")

-- Tabs

local Tab1 = Window:NewTab("Player")
local Tab1Section = Tab1:NewSection("Hecks")
-- Buttons/Windows/Idk

Tab1Section:NewButton("Inf Jumps", "Enables Inf Jumps", function()
    local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)
end)

Tab1Section:NewToggle("Fov", "Changes Fov", function(state)
    if state then
        game.Workspace.CurrentCamera.FieldOfView = 120
    else
        game.Workspace.CurrentCamera.FieldOfView = 80
    end
end)

Tab1Section:NewSlider("Speed", "Sussy Speed", 250, 120, function(v)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
end)

local Tab1Section = Tab1:NewSection("R15 Animation (FE)")

Tab1Section:NewButton("(R15) Permanent Animation e (FE)", "Click To Enable", function()
loadstring(game:HttpGet("https://pastebin.com/raw/ChfHpM02"))()
end)

Tab1Section:NewButton("(R15) Gui Perm Animation (FE)", "Click To Enable", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Animation-Hub/main/Animation%20Gui", true))()
end)

local Tab1Section = Tab1:NewSection("Hitbox")

Tab1Section:NewButton("LargerHitbox", "Click To Enable", function()
loadstring(game:HttpGet("https://pastebin.com/raw/FAY1au9v"))()
end)

local Tab1Section = Tab1:NewSection("Godmode")

Tab1Section:NewButton("Godmode Work For All Games (R6 Only)", "Click To Enable", function()
loadstring(game:HttpGet("https://pastebin.com/raw/WrrBWZpb"))()
end)

-----

local Tab1 = Window:NewTab("Scripts")
local Tab1Section = Tab1:NewSection("Scripts")

Tab1Section:NewButton("British", "Click To Show Hub", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/BH%20v2%20Protecc"))()
end)

Tab1Section:NewButton("ProHub", "Click To Show Hub", function()
loadstring(game:HttpGet(("https://cdn.discordapp.com/attachments/922823751127683082/994188489358835752/Protected.lua"), true))()
end)

Tab1Section:NewButton("RedGhostHub", "Click To Show Hub", function()
loadstring(game:HttpGet('https://pastebin.com/raw/WFKSRG6m'))();
end)

Tab1Section:NewButton("VHub", "Click To Show Hub", function()
loadstring(game:HttpGet(('\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\52\103\102\114\72\120\52\82'),true))()
end)

--Tabs

local Tab1 = Window:NewTab("Bedwars")
local Tab1Section = Tab1:NewSection("Scripts")
-- Buttons/Windows/Idk

Tab1Section:NewButton("Bedwars JN HH V10", "Enables Bedwars JN HH V10", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/JNO10"))()
end)

Tab1Section:NewButton("DarkRai", "Enables DarkRai", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/bedwars/main/Script", true))()
end)

--Tabs

local Tab1 = Window:NewTab("Credits")
local Tab1Section = Tab1:NewSection("Made By Me (Martin)")

local Tab1Section = Tab1:NewSection("Credits To The Owner For The Gui And Hubs")


