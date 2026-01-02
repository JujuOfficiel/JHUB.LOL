local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "👑 JHub 👑 - Version Prenium - Clé : 23071806",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "JHub....",
   LoadingSubtitle = "Chargement....",
   ShowText = "Open Jhub", -- for mobile users to unhide rayfield, change if you'd like
   Theme = "AmberGlow", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   ToggleUIKeybind = "K", -- The keybind to toggle the UI visibility (string like "K" or Enum.KeyCode)

   DisableRayfieldPrompts = true,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = false,
      FolderName = JHub_Configuration_Prenium, -- Create a custom folder for your hub/game
      FileName = "JHub_Configuration"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Entre ta clé Prenium",
      Subtitle = "La clé est seulement donnée par Juju",
      Note = "Entre la clé qui t'a été donnée, si tu ne l'a pas, force mdr", -- Use this to tell the user how to get a key
      FileName = "JHub_Congif_Clé", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"23071806"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("📜Informations",104365492568677) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Juju Hub", Content = "Bon Cheat, si un script demande une clé ou ne marche plus, prévenez moi"})
local Paragraph = Tab:CreateParagraph({Title = "Version Actuelle", Content = "V1.0.0"})

local Paragraph = Tab:CreateParagraph({Title = "Createur du Script", Content = "@jujuofficiel"})
local Paragraph = Tab:CreateParagraph({Title = "Crédit pour l'Aimbot Neptune", Content = "neptune Scripts (.gg/neptunecomeback)"})

local Button = Tab:CreateButton({
   Name = "Fermer JHub",
   Callback = function()
   Rayfield:Destroy()
   end,
})

local Tab = Window:CreateTab("🎲Scripts Universel", 104365492568677) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Aimbot, ESP et Hitbox",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ItsIYce/Iyce/refs/heads/main/main.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "VAPE",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/AsuraXowner/SentinelVAPE/refs/heads/main/NewMainScript.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dex",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/peyton2465/Dex/master/out.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Aimbot pour mobile",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Aimbot-Mobile-34677"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Bring Parts",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/JujuOfficiel/bring-parts/refs/heads/main/bring%20parts"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Neptune Aimbot",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/new-gugus/aimbot-neptune/refs/heads/main/aimbot.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Shift Lock pour mobile",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Mobile-Console-20843"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Freecam",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Freecam'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Boutons qui simulent une touche de clavier",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Mobile-Keyboard-Script-20056"))()
   end,
})

local Tab = Window:CreateTab("🎮Jeux",104365492568677) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Brookhaven : Sander XY",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Sander-XY-35845"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "99 Nuits dans la forêt",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/VapeVoidware/VWExtra/main/NightsInTheForest.lua", true))("t.me/i_s_m_max")
   end,
})

local Button = Tab:CreateButton({
   Name = "Basically FNF : Autoplayer",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Basically-FNF:-Remix-AutoPlayer-Lite-9989"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Doors : Lolhax",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Robloxexploiterz/Release-Lolhax/refs/heads/main/LX%20Doors%20v3.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Murder VS Sheriff Duels : Lx39",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Murder-vs-sheriff-by-Lx39-17130"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "M.E.G Réalité Infinie : MegMenu",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/UPDATE-M.E.G.-Endless-Reality-MegMenu-32222"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Blade Ball : Auto Parry",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Avorrietz/Ghostobfuscate/refs/heads/main/SGC"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Brookhaven : Darkbones",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Brookhaven-30409"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fisch : Speed Hub X",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dead Rails : Lunor",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/Catto-YFCN/Lunor_Dependencies/refs/heads/main/Loader'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fling Things and people : RuHub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Fling-Things-and-People-RuHub-OP-FTAP-Script-35067"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Piggy : StarHack",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/StarHackScripts/StarHack-Hub-Deepstar-Hub/refs/heads/main/StarHack%20Hub%20-%20Piggy%20Pro%20Hub.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "RIVALS : Duckhub (Seulement pour mobile)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/RIVALS-Best-Script-Duck-Hub-29813"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ability Wars : ElysiumX",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/KylnDantas/ElysiumX/refs/heads/main/Loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "MM2 : Xhub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/XMainHub/freemium/refs/heads/main/execute"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dead Rails : OP Gui",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptBeLike/Tera-DeadRails/refs/heads/main/Meteor%20V1"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Prison Life : Triger Admin",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Prison-Life-Tiger-Admin-40262"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Natural Disaster Survival : NullFire",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-NullFire-NDS-24033"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Jailbreak : OP Script",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Jailbreak-Season-25-BEST-OP-UNDETECTED-SCRIPT-SILENT-AIM-ESP-AUTO-ARREST-CAR-MOD-31827"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Da Hood : Zins",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/Zinzs/luascripting/main/canyoutellitsadahoodscriptornot.lua'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Cave Diving Experience : Menu",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/JujuOfficiel/cavediving/refs/heads/main/cavediving'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Base Battles : Etendre les Hitbox",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   -- loop
game:GetService("RunService").Stepped:Connect(function()
    -- gets all players in the server
    for _, player in next, game:GetService("Players"):GetPlayers() do
        -- checks if the player found was not the local player, so the local player doesnt get his hitbox extended
        if player ~= game:GetService("Players").LocalPlayer then
            -- finds humanoid root part, then changes transparecy and can collide so you can walk through the hitbox and it wont be wonky
            local hrp = player.Character and player.Character:FindFirstChild("HumanoidRootPart")
            if hrp then
                hrp.CanCollide = false
                hrp.Transparency = 0.1  -- Biraz şəffaflıq əlavə et
                
                -- changes the humanoidrootpart size (basically the main code)
                if hrp.Size ~= Vector3.new(20, 20, 20) then
                    hrp.Size = Vector3.new(20, 20, 20)
                end
                
                
                hrp.Material = Enum.Material.Neon
                hrp.BrickColor = BrickColor.new("Bright red") 
                
                
                -- hrp.BrickColor = BrickColor.new("Bright blue") 
            end
        end
    end
end)
   end,
})

local Button = Tab:CreateButton({
   Name = "Zombie Attack : Petit Script des familles",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Exécuté",
   Content = "Si ca marche pas préviens moi",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/rrixh/zombieattaxk/main/az_lulaslollipop",true))();
   end,
})
