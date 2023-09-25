--------------------------------------------
TITLE: HeatHub,
Creator: heatdev,
Discord Name: heatdev_,
Version: Version 1,
UI: Orion Library,
Skidded: No,
Contains 3rd Party Scripts: Yes,
--------------------------------------------
Looking For Developers: Yes,
Looking For Contributers: Yes,
--------------------------------------------
--[HeatHub V1]
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "HeatHub V1 [DA HOOD]", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Fake Ranking ",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Makes you send a message like: ;rank all [Rank]"
}) 

Tab:AddButton({
	Name = "Head Admin",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(";rank all Head Admin                                                                                 {System}: Successfully Ranked All Users!" ,"All")
  	end    
})


Tab:AddButton({
	Name = "Admin",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(";rank all Admin                                                                                 {System}: Successfully Ranked All Users!" ,"All")
  	end    
})

-- Main --
local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Infinte Jump",
	Callback = function()
        game:GetService("UserInputService").JumpRequest:connect(function()
            game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")       
        end)
  	end    
})
Tab:AddButton({
	Name = "Infinite Yield",
	Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
  	end    
})
Tab:AddButton({
	Name = "Nyula",
	Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/nyulachan/nyula/main/nyuladhm", true))()
  	end    
})
-- Emojis --
local Tab = Window:MakeTab({
	Name = "Emojis",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "🤣",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("🤣" ,"All")
  	end    
})
Tab:AddButton({
	Name = "😀",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😀" ,"All")
  	end    
})
Tab:AddButton({
	Name = "😁",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😁" ,"All")
  	end    
})
Tab:AddButton({
	Name = "😂",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😂" ,"All")
  	end    
})
Tab:AddButton({
	Name = "😄",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😄" ,"All")
  	end    
})
Tab:AddButton({
	Name = "😅",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("😅" ,"All")
  	end    
})
-- Rizz Lines --
local Tab = Window:MakeTab({
	Name = "Rizz Lines",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddButton({
	Name = "Stair Rizz",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Are you Stairs? Because you need you need some railing 😉" ,"All")
  	end    
})
Tab:AddButton({
	Name = "Balloon Rizz",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Are you a Balloon? Because im tryna blow you up 😉" ,"All")
  	end    
})
Tab:AddButton({
	Name = "Grade Rizz",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Are you a Grade? Because I think your a A+ 😉" ,"All")
  	end    
})
Tab:AddButton({
	Name = "Developer Rizz",
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Are you a Developer? Because I'm Tryna Build on you 😉" ,"All")
  	end    
})
-- Toxic --
local Tab = Window:MakeTab({
	Name = "Stomp Message",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddBind({
	Name = "Shadow Boxing",
	Default = Enum.KeyCode.P,
	Hold = false,
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("⬇️" ,"All")
        wait(0.5)
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("⬆️" ,"All")
        wait(0.5)
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("➡️" ,"All")

	end    
})

Tab:AddBind({
	Name = "No Comp",
	Default = Enum.KeyCode.U,
	Hold = false,
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Clipped, No Comp 🤣" ,"All")
        
	end    
})
Tab:AddBind({
	Name = "Error404",
	Default = Enum.KeyCode.I,
	Hold = false,
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Error404 Couldn't find skill_aim 💀" ,"All")
        
	end    
})
Tab:AddBind({
	Name = "6ix9ine",
	Default = Enum.KeyCode.O,
	Hold = false,
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Are you dumb? Stupid or dumb Huh?" ,"All")
        
	end    
})
Tab:AddBind({
	Name = "Say Cheese 📸",
	Default = Enum.KeyCode.G,
	Hold = false,
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Say Cheese 🤡" ,"All")
		wait(0.5)
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("📸" ,"All")
	end    
})
Tab:AddBind({
	Name = "Shadow Wizard Gang",
	Default = Enum.KeyCode.H,
	Hold = false,
	Callback = function()
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("Shadow Wizard Money Gang 🧙" ,"All")
		wait(0.5)
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("We love casting spells 🧙" ,"All")
	end    
})
local Tab = Window:MakeTab({
	Name = "Fake Emojis",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
Tab:AddLabel("How to use.")
Tab:AddLabel("Press your keybind.")
Tab:AddLabel("Then Send your message!")
Tab:AddBind({
	Name = "💎",
	Default = Enum.KeyCode.P,
	Hold = false,
	Callback = function()
		game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("[💎]:" ,"All")
	end    
})
Tab:AddBind({
	Name = "🏆",
	Default = Enum.KeyCode.C,
	Hold = false,
	Callback = function()
		game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("[🏆]:" ,"All")
	end    
})
Tab:AddBind({
	Name = "👑",
	Default = Enum.KeyCode.X,
	Hold = false,
	Callback = function()
		game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("[👑]:" ,"All")
	end    
})
Tab:AddBind({
	Name = "🛡️",
	Default = Enum.KeyCode.V,
	Hold = false,
	Callback = function()
		game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("[🛡️]:" ,"All")
	end    
})
Tab:AddBind({
	Name = "🔨",
	Default = Enum.KeyCode.N,
	Hold = false,
	Callback = function()
		game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("[🔨]:" ,"All")
	
	end    
})
Tab:AddBind({
	Name = "📸",
	Default = Enum.KeyCode.M,
	Hold = false,
	Callback = function()
		game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer("[📸]:" ,"All")
	end    
})
