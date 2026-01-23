loadstring(game:HttpGet(("https://raw.githubusercontent.com/daucobonhi/Ui-Redz-V2/refs/heads/main/UiREDzV2.lua")))()

       local Window = MakeWindow({
         Hub = {
         Title = "HubLoader Hub 1.0v",
         Animation = "tiktok: @hoainam36"
         },
        Key = {
        KeySystem = false,
        Title = "Key System",
        Description = "",
        KeyLink = "",
        Keys = {"1234"},
        Notifi = {
        Notifications = true,
        CorrectKey = "Running the Script...",
       Incorrectkey = "The key is incorrect",
       CopyKeyLink = "Copied to Clipboard"
      }
    }
  })

       MinimizeButton({
       Image = "http://www.roblox.com/asset/?id=99222845225092",
       Size = {50, 50},
       Color = Color3.fromRGB(10, 10, 10),
       Corner = true,
       Stroke = false,
       StrokeColor = Color3.fromRGB(255, 0, 0)
      })
      
local TabAll = MakeTab({Name = "all map"})

AddButton(TabAll,{Name="Infinite Yield",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end})

AddButton(TabAll,{Name="Fly",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Fly-Script/main/Fly.lua"))()
end})

AddButton(TabAll,{Name="ESP",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/ESP-Script/main/ESP.lua"))()
end})

AddButton(TabAll,{Name="Speed",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/SpeedScript/main/Speed.lua"))()
end})

AddButton(TabAll,{Name="JumpPower",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/JumpPower/main/Jump.lua"))()
end})

AddButton(TabAll,{Name="Noclip",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Noclip/main/Noclip.lua"))()
end})

AddButton(TabAll,{Name="Aimbot",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-Script/main/Aimbot.lua"))()
end})

AddButton(TabAll,{Name="Hitbox",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/Hitbox/main/Hitbox.lua"))()
end})

AddButton(TabAll,{Name="FPS Boost",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/FPSBoost/main/FPS.lua"))()
end})

AddButton(TabAll,{Name="Auto Click",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/AutoClick/main/Click.lua"))()
end})

AddButton(TabAll,{Name="Server Hop",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/ServerHop/main/Hop.lua"))()
end})

AddButton(TabAll,{Name="Rejoin",Callback=function()
game:GetService("TeleportService"):Teleport(game.PlaceId,game.Players.LocalPlayer)
end})

AddButton(TabAll,{Name="Chat Spy",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/ChatSpy/main/Spy.lua"))()
end})

AddButton(TabAll,{Name="Anti AFK",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/AntiAFK/main/AFK.lua"))()
end})

AddButton(TabAll,{Name="Full Bright",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/FullBright/main/Bright.lua"))()
end})


local TabHub = MakeTab({Name = "Hub"})

AddButton(TabHub,{Name="Owl Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))()
end})

AddButton(TabHub,{Name="VG Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub"))()
end})

AddButton(TabHub,{Name="Universal Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/UniversalHub/main/Hub.lua"))()
end})

AddButton(TabHub,{Name="Dark Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/DarkHub/main/Dark.lua"))()
end})

AddButton(TabHub,{Name="Simple Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/SimpleHub/main/Hub.lua"))()
end})

AddButton(TabHub,{Name="Pro Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/ProHub/main/Hub.lua"))()
end})

AddButton(TabHub,{Name="Speed Hub",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/SpeedHub/main/Hub.lua"))()
end})


local TabAdmin = MakeTab({Name = "admin"})

AddButton(TabAdmin,{Name="Infinite Yield Admin",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end})

AddButton(TabAdmin,{Name="CMD X",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source"))()
end})

AddButton(TabAdmin,{Name="Fates Admin",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end})

AddButton(TabAdmin,{Name="Reviz Admin",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/RevizAdmin/main/Admin.lua"))()
end})

AddButton(TabAdmin,{Name="Simple Admin",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/SimpleAdmin/main/Admin.lua"))()
end})


local TabR6 = MakeTab({Name = "R6"})

AddButton(TabR6,{Name="R6 Anim",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6Anim/main/Anim.lua"))()
end})

AddButton(TabR6,{Name="R6 Fly",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6Fly/main/Fly.lua"))()
end})

AddButton(TabR6,{Name="R6 God",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6God/main/God.lua"))()
end})

AddButton(TabR6,{Name="R6 Speed",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6Speed/main/Speed.lua"))()
end})

AddButton(TabR6,{Name="R6 Jump",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6Jump/main/Jump.lua"))()
end})

AddButton(TabR6,{Name="R6 Spin",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6Spin/main/Spin.lua"))()
end})

AddButton(TabR6,{Name="R6 Noclip",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R6Noclip/main/Noclip.lua"))()
end})


local TabR15 = MakeTab({Name = "r15"})

AddButton(TabR15,{Name="R15 Anim",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Anim/main/Anim.lua"))()
end})

AddButton(TabR15,{Name="R15 Fly",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Fly/main/Fly.lua"))()
end})

AddButton(TabR15,{Name="R15 Speed",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Speed/main/Speed.lua"))()
end})

AddButton(TabR15,{Name="R15 Jump",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Jump/main/Jump.lua"))()
end})

AddButton(TabR15,{Name="R15 God",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15God/main/God.lua"))()
end})

AddButton(TabR15,{Name="R15 Noclip",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Noclip/main/Noclip.lua"))()
end})

AddButton(TabR15,{Name="R15 Spin",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Spin/main/Spin.lua"))()
end})

AddButton(TabR15,{Name="R15 Hitbox",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15Hitbox/main/Hitbox.lua"))()
end})

AddButton(TabR15,{Name="R15 ESP",Callback=function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/ahmadsgamer2/R15ESP/main/ESP.lua"))()
end})
