if game.PlaceId == 2788229376 then

local Rayfield = loadstring(game:HttpGet('https://[Log in to view URL]'))()

local Window = Rayfield:CreateWindow({
   Name = "🔫Da hood script🔫",
   LoadingTitle = "dahood",
   LoadingSubtitle = "by szzn",
   ConfigurationSaving = {
      Enabled = false,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "szznlocal"
   },
   Discord = {
      Enabled = true,
      Invite = "szzn", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Dahood - Key",
      Subtitle = "Link in discord server",
      Note = "Join Server From Misc Tab",
      FileName = "dahoodkey", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"https://[Log in to view URL]"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab("😶‍🌫️ Aim", nil) -- Title, Image
local MainSection = MainTab:CreateSection("Main")

    Rayfield:Notify({
   Title = "You executed the script",
   Content = "Very good gui",
