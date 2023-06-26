local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Scipt for the boys", HidePremium = false, IntroText = "Private Gui for The boys" , SaveConfig = true, ConfigFolder = "OrionTest"})


local MainTab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


MainTab:AddButton({
	Name = "Fly",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
  	end    
})


MainTab:AddButton({
	Name = "noclip",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/NGTk7zr6'))()
  	end    
})


MainTab:AddButton({
	Name = "Super-Human",
	Callback = function()
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 120
  	end    
})



MainTab:AddButton({
	Name = "Super-Human off",
	Callback = function()
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
  	end  
})


MainTab:AddButton({
	Name = "ESP",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/ayNS6NEv'))()
  	end    
})


MainTab:AddButton({
	Name = "Reset",
	Callback = function()
        game.Players.LocalPlayer.Character.Head:Destroy()
  	end    
})






local OthersTab = Window:MakeTab({
	Name = "Others",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


OthersTab:AddButton({
	Name = "Admin Script",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/zB42diMA'))()
  	end    
})


OthersTab:AddButton({
	Name = "Frakture",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/L1ghtingBolt/FraktureSS/master/unobfuscated.lua"))()
  	end    
})


OthersTab:AddButton({
	Name = "All Scripts in One",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/RMg07cmz'))()
  	end    
})


OthersTab:AddButton({
	Name = "Vhub",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/V31nc/2642/Created/VHub"))()
  	end    
})


OthersTab:AddButton({
	Name = "Anti AFK",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/KazeOnTop/Rice-Anti-Afk/main/Wind", true))()
  	end    
})


OthersTab:AddButton({
	Name = "Mobile Key Bored",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
  	end    
})


local GamesTab = Window:MakeTab({
	Name = "Games",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


GamesTab:AddButton({
	Name = "Prison Life",
	Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/VnijhyG4'))()
  	end    
})


GamesTab:AddButton({
	Name = "Bloxburg",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/PainfulDestroyer/Roblox/main/Scar%20Hub"))()
  	end    
})


GamesTab:AddButton({
	Name = "Seal Build Build a Boat",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/max2007killer/auto-build-not-limit/main/autobuild.txt"))()
    end
})


GamesTab:AddButton({
	Name = "Build a Boat",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/XRoLLu/UWU/main/BUILD%20A%20BOAT%20FOR%20TREASURE.lua'))()
    end
})


GamesTab:AddButton({
	Name = "Pet Simulator X",
	Callback = function()
        loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/a82cd5447cbbc4c7be0e8db405555787.lua"))()
    end
})


GamesTab:AddButton({
	Name = "Prison Life Admin",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/H17S32/Tiger_Admin/main/Script'))() 
    end
})


