local Rayfield = loadstring(game:HttpGet("https://sirius.menu/gen2"))()

local window = Rayfield:CreateWindow({ 
    Name = "Your Natural Disaster Hub", 
    Subtitle = "By Inky", 
    Theme = "amethyst", 
    Configuration = { 
        AutoSave = true, 
        AutoLoad = true, 
        FileName = "Your Natural Disaster Hub" 
    } 
})

local homeTab = window:CreateTab({ Name = "Home", Icon = 93364949241311 })

homeTab:CreateSection({ Name = "Featured" })

homeTab:CreateButton({ Name = "Infinite Yield", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/edgeiy/infiniteyield/master/source"))() 
end })

homeTab:CreateButton({ Name = "Nameless Admin", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ltseverydayyou/Nameless-Admin/main/Source.lua"))() 
end })

homeTab:CreateButton({ Name = "Dex Explorer", Callback = function() 
    loadstring(game:HttpGet("https://github.com/AZYsGithub/DexPlusPlus/releases/latest/download/out.lua"))() 
end })

homeTab:CreateButton({ Name = "Remote Spy", Callback = function() 
    loadstring(game:HttpGet("https://github.com/exxtremestuffs/SimpleSpySource/raw/master/SimpleSpy.lua"))() 
end })

homeTab:CreateSlider({ 
    Name = "Walkspeed", 
    Range = { 20, 150 }, 
    Increment = 1, 
    CurrentValue = 16, 
    Suffix = " studs", 
    Callback = function(Value) 
        local player = game:GetService("Players").LocalPlayer 
        if player and player.Character and player.Character:FindFirstChildOfClass("Humanoid") then 
            player.Character:FindFirstChildOfClass("Humanoid").WalkSpeed = Value 
        end 
    end 
})

local scriptsTab = window:CreateTab({ Name = "Scripts", Icon = 93364949241311 })

scriptsTab:CreateSection({ Name = "Scripts" })

scriptsTab:CreateButton({ Name = "Super Ring V6", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/chesslovers69/Super-ring-parts-v6/refs/heads/main/Bylukaslol"))()
end })

scriptsTab:CreateButton({ Name = "Fe Fake Vr", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/rizz65667-svg/FeVr/refs/heads/main/Fe%20vr"))()
end })

local toolsTab = window:CreateTab({ Name = "Tools", Icon = 93364949241311 })

toolsTab:CreateSection({ Name = "Tools" })

toolsTab:CreateButton({ Name = "Fly 1", Callback = function() 
    loadstring(game:HttpGet("https://pastefy.app/9bilwWLP/raw"))() 
end })

toolsTab:CreateButton({ Name = "Fly 2", Callback = function() 
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fly-script-v3-16742"))() 
end })

local guiTab = window:CreateTab({ Name = "Gui", Icon = 93364949241311 })

guiTab:CreateSection({ Name = "Guis" })

guiTab:CreateButton({ Name = "Coolkid Gui V1", Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-c00lkidds-op-trolling-gui-of-nds-30335"))()
end })

local hubsTab = window:CreateTab({ Name = "Hubs", Icon = 93364949241311 })

hubsTab:CreateSection({ Name = "Hubs" })

hubsTab:CreateButton({ Name = "AceZaxy Hub", Callback = function() 
  loadstring(game:HttpGet("https://raw.githubusercontent.com/morenoffproScriptsRoblox/Acezaxyv4/refs/heads/main/README.md", true))()
end })

hubsTab:CreateButton({ Name = "Ps hub", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Lucas047rds/Disaster-Hub/refs/heads/main/README.md"))() 
end })

local trollingTab = window:CreateTab({ Name = "Trolling", Icon = 93364949241311 })

trollingTab:CreateSection({ Name = "Trolling" })

trollingTab:CreateButton({ Name = "Dropkick Fling", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/platinww/CrustyMain/refs/heads/main/universal/DropKick.lua"))() 
end })

trollingTab:CreateButton({ Name = "Fling Gui 1", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GoldenCheats/natural-disaster-script/refs/heads/main/NATURAL%20DISASTER%20FLING%20V2"))()
end })

trollingTab:CreateButton({ Name = "Fling Gui 2", Callback = function() 
    loadstring(game:HttpGet("https://raw.githubusercontent.com/sypcerr/scripts/refs/heads/main/UFGUI", true))() 
end })
