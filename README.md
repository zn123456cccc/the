# local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Infinite Rarities Script (WIP)", "Ocean")

 

local startergui = game:GetService("StarterGui")

 

    -- Main

    

    local Main = Window:NewTab("Main")

    local MainSection = Main:NewSection("This is a Edit/Improvement Of Someone elses Work")

    local MainSection = Main:NewSection("Here Is the original pulled form his Youtube ")

    local MainSection = Main:NewSection("Stoic Poison https://pastebin.com/FmDXZBSz")

 

    MainSection:NewButton("Prestige TP", "Makes you tp to prestige", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Prestige"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

    MainSection:NewButton("Rarity Roll TP", "Makes you tp to RarityGet", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

    

    MainSection:NewButton("Sacrifice TP", "Makes you tp to Sacrifice", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

    

    MainSection:NewButton("Ascend TP", "Makes you tp to the Ascend button", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Ascend"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

    MainSection:NewButton("Transcend TP", "Makes you tp to the Transcend button", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace.APMapExpansion2["Transcend"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

MainSection:NewButton("SP Luck Upgrade TP", "Makes you tp to the luck upgrade button", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

MainSection:NewButton("Bulk Roll TP", "Makes you tp to the Bulk Roll button", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

MainSection:NewButton("SP Multiplier TP", "Makes you tp to the SP Multiplier button", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

MainSection:NewButton("Roll Cooldown TP", "Makes you tp to the Roll Cooldown button", function()

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

 

local Farm = Window:NewTab("Farm")

    local MainSection = Farm:NewSection("Use An Auto Clicker For Every 5 Seconds Or So")

    local MainSection = Farm:NewSection("Please Give Feedback For Fixs/Upgrades")

    local MainSection = Farm:NewSection("You Should Probably Hold Space For More Accuracy")

 

    MainSection:NewButton("Auto Ascend (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame  

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

     wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame   

    wait(1)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Ascend"] 

player.HumanoidRootPart.CFrame = part.CFrame            

    wait (0.5)

end)

 

 MainSection:NewButton("Auto Prestige (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1) 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame   

    wait(1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Prestige"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Upgrades (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1) 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Transcend (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1) 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace.APMapExpansion2["Transcend"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

     MainSection:NewButton("Auto Ascend No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Ascend"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Prestige No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

   wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local part = game.Workspace["Prestige"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Upgrades No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Transcend No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (1)

player.HumanoidRootPart.CFrame = part.CFrame

local part = game.Workspace.APMapExpansion2["Transcend"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

local Farm = Window:NewTab("Farm But Faster")

    local MainSection = Farm:NewSection("Use An Auto Clicker For Every 2.5 Seconds Or So")

    local MainSection = Farm:NewSection("Please Give Feedback For Fixs/Upgrades")

    local MainSection = Farm:NewSection("You Should Probably Hold Space For More Accuracy")

 

    MainSection:NewButton("Auto Ascend (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame  

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

     wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame   

    wait(0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Ascend"] 

player.HumanoidRootPart.CFrame = part.CFrame            

    wait (0.5)

end)

 

 MainSection:NewButton("Auto Prestige (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5) 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame   

    wait(0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Prestige"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Upgrades (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5) 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Transcend (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.1)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeBr"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5) 

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeRcd"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace.APMapExpansion2["Transcend"] 

player.HumanoidRootPart.CFrame = part.CFrame

    end)

 

     MainSection:NewButton("Auto Ascend No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

        local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

    local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Ascend"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Prestige No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

   wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local part = game.Workspace["Prestige"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Upgrades No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

 MainSection:NewButton("Auto Transcend No BR/RC (You Have To Hold Jump To Work)", "Makes you tp to prestige and RarityGet", function()

        local player = game.Players.LocalPlayer.Character

 

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["Sacrifice"] 

player.HumanoidRootPart.CFrame = part.CFrame

wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeLuck"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["UpgradeSPM"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

local player = game.Players.LocalPlayer.Character

local part = game.Workspace["RarityGet"] 

player.HumanoidRootPart.CFrame = part.CFrame

    wait (0.5)

player.HumanoidRootPart.CFrame = part.CFrame

local part = game.Workspace.APMapExpansion2["Transcend"] 

player.HumanoidRootPart.CFrame = part.CFrame

end)

 

local Farm = Window:NewTab("More Compact Version")

    local MainSection = Farm:NewSection("https://pastebin.com/L6abDw5F")
