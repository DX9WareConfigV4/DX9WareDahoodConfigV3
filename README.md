local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/cat"))() --you can go into the github link and copy all of it and modify it for yourself.
local Window = Library:CreateWindow("Dx9Ware Config V3", Vector2.new(492, 598), Enum.KeyCode.RightControl) --you can change your UI keybind
local AimingTab = Window:CreateTab("DX9Ware Settings") --you can rename this tab to whatever you want --you can also change the tabs code, for example "AimingTab" can be changed to "FunnyCoolTab" etc.


local testSection = AimingTab:CreateSector("First Section", "left")  --you can  change the section code, for example "testsection" can be changed to "FunnyCoolSection" etc.

testSection:AddToggle("AutoAimbotConfig1", false, function(first)
    print("ejejejejejeje")
end)

testSection:AddButton("AutoDahoodConfig", function(IhateGayPeople)
    print("Dx9Ware Streamable1")
end)

testSection:AddSlider("AimbotLegitness(Use85)", 0, 120, 2000, 1, function(State)
    
end)

testSection:AddTextbox("AutoBotSettings", nil, function(State)

end)

testSection:AddDropdown("Dropdown", {"ConfigFools", "Nukiyo", "Aqua", "HellBladi"}, "FPSGUIUSER2020", true, function(dropdown)

end)

local ColorToggle = testSection:AddToggle("Zae DX9Ware Config 1", false, function(e)

end)

ColorToggle:AddColorpicker(Color3.fromRGB(75, 0,130), function(ztx)
   
end)

local ToggleBind = testSection:AddToggle("Plutos DX9Ware Config 1", false, function(e)

end)

ToggleBind:AddKeybind()

AimingTab:CreateConfigSystem("right")
