local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "👻Test Script👻",
   LoadingTitle = "Zeus Hub",
   LoadingSubtitle = "by Zeus",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Zeus Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "👻Test Script👻",
      Subtitle = "Key:Zeus",
      Note = "⚡Zeus Hub",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"https://pastebin.com/raw/8hJd53h0"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab("⚡Stories", 4483362458) -- Title, Image
local MainSection = MainTab:CreateSection("Main")

Rayfield:Notify({
   Title = "You use script Zeus Hub!",
   Content = "Very good Gui",
   Duration = 5,
   Image = 4483362458,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Okay!",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})

local Button = MainTab:CreateButton({
   Name = "Wood",
   Callback = function()
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-237.4879, 4.44611931, -190.680099, -0.928261817, -4.34536886e-08, 0.37192744, -3.13612922e-08, 1, 3.85618186e-08, -0.37192744, 2.41313387e-08, -0.928261817)
   end,
})

local Button = MainTab:CreateButton({
   Name = "crowbar",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-238.813309, 5.93063879, -244.34581, 0.87641722, 2.28962858e-08, -0.481552571, -4.66402419e-08, 1, -3.73376139e-08, 0.481552571, 5.51830546e-08, 0.87641722)
   end,
})

local Button = MainTab:CreateButton({
   Name = "key s23",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-243.921967, 19.3864212, -106.513573, -0.957077444, -5.09080689e-09, 0.289832234, 8.82530438e-10, 1, 2.04789394e-08, -0.289832234, 1.98557171e-08, -0.957077444)
   end,
})

local Button = MainTab:CreateButton({
   Name = "key s34",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-252.307434, 19.3629074, -53.2392845, -0.933750331, -5.02248838e-08, -0.357925057, -3.0318084e-08, 1, -6.12289242e-08, 0.357925057, -4.6320924e-08, -0.933750331)
   end,
})

local Button = MainTab:CreateButton({
   Name = "rope",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-270.244934, 19.3629055, -84.9978409, -0.331019908, 9.74645076e-08, 0.943623781, 1.26162449e-08, 1, -9.88617259e-08, -0.943623781, -2.08202113e-08, -0.331019908)
   end,
})

local Button = MainTab:CreateButton({
   Name = "storage room",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-241.914444, 40.5553665, -226.159195, -0.432703167, 3.2493066e-08, 0.901536465, 9.44944389e-08, 1, 9.3118544e-09, -0.901536465, 8.92194549e-08, -0.432703167)
   end,
})

local Button = MainTab:CreateButton({
   Name = "Hammer",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-260.81308, 40.5633736, -208.856445, -0.672253311, -6.90609583e-11, 0.740321159, 2.71896052e-08, 1, 2.47829792e-08, -0.740321159, 3.67894799e-08, -0.672253311)
   end,
})

local Button = MainTab:CreateButton({
   Name = "toilet",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-256.743835, 40.4888763, -12.3250122, -0.186537683, 8.31748963e-08, 0.982447803, -3.52440459e-08, 1, -9.13526748e-08, -0.982447803, -5.16661522e-08, -0.186537683)
   end,
})

local Button = MainTab:CreateButton({
   Name = "toilet key",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-273.023285, 40.4888802, -18.884243, 0.998522162, 4.42964065e-09, 0.0543456934, -5.63536862e-09, 1, 2.20330225e-08, -0.0543456934, -2.230672e-08, 0.998522162)
   end,
})

local Button = MainTab:CreateButton({
   Name = "4th",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-261.001038, 40.1312065, -65.1517944, 0.984280407, -6.46832774e-08, 0.176612884, 7.42837116e-08, 1, -4.77469335e-08, -0.176612884, 6.01158305e-08, 0.984280407)
   end,
})

local Button = MainTab:CreateButton({
   Name = "551",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-241.788391, 72.9742508, -223.481247, -0.904109776, 1.49580988e-08, 0.427300245, 3.06182208e-08, 1, 2.97779668e-08, -0.427300245, 4.00057232e-08, -0.904109776)
   end,
})

local Button = MainTab:CreateButton({
   Name = "553 Spoiler",
   Callback = function()
   game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-252.036301, 74.4905472, -129.986145, 0.998537302, -0.0189114902, 0.0506518744, -3.36786798e-09, 0.936832666, 0.349777877, -0.0540671498, -0.349266261, 0.935462356)
   end,
})

local OtherTab = Window:CreateTab("🏴‍☠️Other script", 4483362458) -- Title, Image
local Section = OtherTab:CreateSection("God script⚡")

local Button = OtherTab:CreateButton({
   Name = "Infinite Jump",
   Callback = function()
       --Toggles the infinite jump between on or off on every script run
_G.infinjump = not _G.infinjump

if _G.infinJumpStarted == nil then
	--Ensures this only runs once to save resources
	_G.infinJumpStarted = true
	
	--Notifies readiness
	game.StarterGui:SetCore("SendNotification", {Title="Youtube Hub"; Text="Infinite Jump Activated!"; Duration=5;})

	--The actual infinite jump
	local plr = game:GetService('Players').LocalPlayer
	local m = plr:GetMouse()
	m.KeyDown:connect(function(k)
		if _G.infinjump then
			if k:byte() == 32 then
			humanoid = game:GetService'Players'.LocalPlayer.Character:FindFirstChildOfClass('Humanoid')
			humanoid:ChangeState('Jumping')
			wait()
			humanoid:ChangeState('Seated')
			end
		end
	end)
end
   end,
})

local Slider = OtherTab:CreateSlider({
   Name = "WalkSpeed Slider",
   Range = {1, 350},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "sliderws", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = (Value)
   end,
})

local Slider = OtherTab:CreateSlider({
   Name = "JumpPower",
   Range = {1, 350},
   Increment = 1,
   Suffix = "Speed",
   CurrentValue = 16,
   Flag = "sliderjp", -- A flag is the identifier for the configuration file, make sure every element has a different flag if you're using configuration saving to ensure no overlaps
   Callback = function(Value)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = (Value)
   end,
})

local Button = OtherTab:CreateButton({
   Name = "Full Bright",
   Callback = function()
   if not _G.FullBrightExecuted then

	_G.FullBrightEnabled = false

	_G.NormalLightingSettings = {
		Brightness = game:GetService("Lighting").Brightness,
		ClockTime = game:GetService("Lighting").ClockTime,
		FogEnd = game:GetService("Lighting").FogEnd,
		GlobalShadows = game:GetService("Lighting").GlobalShadows,
		Ambient = game:GetService("Lighting").Ambient
	}

	game:GetService("Lighting"):GetPropertyChangedSignal("Brightness"):Connect(function()
		if game:GetService("Lighting").Brightness ~= 1 and game:GetService("Lighting").Brightness ~= _G.NormalLightingSettings.Brightness then
			_G.NormalLightingSettings.Brightness = game:GetService("Lighting").Brightness
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").Brightness = 1
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("ClockTime"):Connect(function()
		if game:GetService("Lighting").ClockTime ~= 12 and game:GetService("Lighting").ClockTime ~= _G.NormalLightingSettings.ClockTime then
			_G.NormalLightingSettings.ClockTime = game:GetService("Lighting").ClockTime
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").ClockTime = 12
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("FogEnd"):Connect(function()
		if game:GetService("Lighting").FogEnd ~= 786543 and game:GetService("Lighting").FogEnd ~= _G.NormalLightingSettings.FogEnd then
			_G.NormalLightingSettings.FogEnd = game:GetService("Lighting").FogEnd
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").FogEnd = 786543
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("GlobalShadows"):Connect(function()
		if game:GetService("Lighting").GlobalShadows ~= false and game:GetService("Lighting").GlobalShadows ~= _G.NormalLightingSettings.GlobalShadows then
			_G.NormalLightingSettings.GlobalShadows = game:GetService("Lighting").GlobalShadows
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").GlobalShadows = false
		end
	end)

	game:GetService("Lighting"):GetPropertyChangedSignal("Ambient"):Connect(function()
		if game:GetService("Lighting").Ambient ~= Color3.fromRGB(178, 178, 178) and game:GetService("Lighting").Ambient ~= _G.NormalLightingSettings.Ambient then
			_G.NormalLightingSettings.Ambient = game:GetService("Lighting").Ambient
			if not _G.FullBrightEnabled then
				repeat
					wait()
				until _G.FullBrightEnabled
			end
			game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
		end
	end)

	game:GetService("Lighting").Brightness = 1
	game:GetService("Lighting").ClockTime = 12
	game:GetService("Lighting").FogEnd = 786543
	game:GetService("Lighting").GlobalShadows = false
	game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)

	local LatestValue = true
	spawn(function()
		repeat
			wait()
		until _G.FullBrightEnabled
		while wait() do
			if _G.FullBrightEnabled ~= LatestValue then
				if not _G.FullBrightEnabled then
					game:GetService("Lighting").Brightness = _G.NormalLightingSettings.Brightness
					game:GetService("Lighting").ClockTime = _G.NormalLightingSettings.ClockTime
					game:GetService("Lighting").FogEnd = _G.NormalLightingSettings.FogEnd
					game:GetService("Lighting").GlobalShadows = _G.NormalLightingSettings.GlobalShadows
					game:GetService("Lighting").Ambient = _G.NormalLightingSettings.Ambient
				else
					game:GetService("Lighting").Brightness = 1
					game:GetService("Lighting").ClockTime = 12
					game:GetService("Lighting").FogEnd = 786543
					game:GetService("Lighting").GlobalShadows = false
					game:GetService("Lighting").Ambient = Color3.fromRGB(178, 178, 178)
				end
				LatestValue = not LatestValue
			end
		end
	end)
end

_G.FullBrightExecuted = true
_G.FullBrightEnabled = not _G.FullBrightEnabled
   end,
})

local Button = OtherTab:CreateButton({
   Name = "Unlock Firstperson",
   Callback = function()
   game.Players.LocalPlayer.CameraMode = Enum.CameraMode.Classic game.Players.LocalPlayer.CameraMaxZoomDistance = 128 game.Players.LocalPlayer.CameraMinZoomDistance = 0.5
   end,
})

local Button = OtherTab:CreateButton({
   Name = "infiniteyield",
   Callback = function()
   loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
   end,
})

local Button = OtherTab:CreateButton({
   Name = "God kill",
   Callback = function()
   -- Gui to Lua
-- Version: 3.2

-- Instances:

local KillGui = Instance.new("ScreenGui")
local Opener = Instance.new("TextButton")
local UIGradient = Instance.new("UIGradient")
local Frame = Instance.new("ImageLabel")
local Player = Instance.new("TextBox")
local UIGradient_2 = Instance.new("UIGradient")
local Kill = Instance.new("TextButton")
local Cancel = Instance.new("TextButton")
local LKill = Instance.new("TextButton")
local UIGradient_3 = Instance.new("UIGradient")

--Properties:

KillGui.Name = "KillGui"
KillGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
KillGui.ResetOnSpawn = false

Opener.Name = "Opener"
Opener.Parent = KillGui
Opener.BackgroundColor3 = Color3.fromRGB(80, 255, 116)
Opener.BackgroundTransparency = 1.000
Opener.BorderSizePixel = 0
Opener.Position = UDim2.new(0.890184641, 0, 0.665688097, 0)
Opener.Size = UDim2.new(0, 113, 0, 50)
Opener.ZIndex = 2
Opener.Font = Enum.Font.SourceSans
Opener.Text = "Open"
Opener.TextColor3 = Color3.fromRGB(255, 255, 255)
Opener.TextScaled = true
Opener.TextSize = 14.000
Opener.TextWrapped = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.23, Color3.fromRGB(238, 0, 255)), ColorSequenceKeypoint.new(0.48, Color3.fromRGB(0, 0, 255)), ColorSequenceKeypoint.new(0.63, Color3.fromRGB(32, 244, 255)), ColorSequenceKeypoint.new(0.78, Color3.fromRGB(4, 255, 0)), ColorSequenceKeypoint.new(0.89, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 0, 0))}
UIGradient.Parent = Opener

Frame.Name = "Frame"
Frame.Parent = KillGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.753321111, 0, 0.741761386, 0)
Frame.Size = UDim2.new(0, 253, 0, 170)
Frame.Visible = false
Frame.Image = "rbxassetid://2851926732"
Frame.ImageColor3 = Color3.fromRGB(72, 255, 96)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(12, 12, 12, 12)

Player.Name = "Player"
Player.Parent = Frame
Player.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Player.BackgroundTransparency = 0.750
Player.BorderSizePixel = 0
Player.Position = UDim2.new(0.0967741907, 0, 0.152100846, 0)
Player.Size = UDim2.new(0, 200, 0, 50)
Player.ZIndex = 2
Player.Font = Enum.Font.FredokaOne
Player.PlaceholderText = "Player To Kill"
Player.Text = ""
Player.TextColor3 = Color3.fromRGB(255, 255, 255)
Player.TextScaled = true
Player.TextSize = 14.000
Player.TextWrapped = true

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.23, Color3.fromRGB(238, 0, 255)), ColorSequenceKeypoint.new(0.48, Color3.fromRGB(0, 0, 255)), ColorSequenceKeypoint.new(0.63, Color3.fromRGB(32, 244, 255)), ColorSequenceKeypoint.new(0.78, Color3.fromRGB(4, 255, 0)), ColorSequenceKeypoint.new(0.89, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 0, 0))}
UIGradient_2.Parent = Player

Kill.Name = "Kill"
Kill.Parent = Frame
Kill.BackgroundColor3 = Color3.fromRGB(141, 255, 142)
Kill.BackgroundTransparency = 1.000
Kill.BorderSizePixel = 0
Kill.Position = UDim2.new(0, 0, 0.700840294, 0)
Kill.Size = UDim2.new(0, 73, 0, 50)
Kill.ZIndex = 2
Kill.Font = Enum.Font.SourceSans
Kill.Text = "Kill"
Kill.TextColor3 = Color3.fromRGB(255, 255, 255)
Kill.TextScaled = true
Kill.TextSize = 14.000
Kill.TextWrapped = true

Cancel.Name = "Cancel"
Cancel.Parent = Frame
Cancel.BackgroundColor3 = Color3.fromRGB(141, 255, 142)
Cancel.BackgroundTransparency = 1.000
Cancel.BorderSizePixel = 0
Cancel.Position = UDim2.new(0.705645204, 0, 0.700840294, 0)
Cancel.Size = UDim2.new(0, 73, 0, 50)
Cancel.ZIndex = 2
Cancel.Font = Enum.Font.SourceSans
Cancel.Text = "Cancel"
Cancel.TextColor3 = Color3.fromRGB(255, 255, 255)
Cancel.TextScaled = true
Cancel.TextSize = 14.000
Cancel.TextWrapped = true

LKill.Name = "LKill"
LKill.Parent = Frame
LKill.BackgroundColor3 = Color3.fromRGB(141, 255, 142)
LKill.BackgroundTransparency = 1.000
LKill.BorderSizePixel = 0
LKill.Position = UDim2.new(0.342741907, 0, 0.700840294, 0)
LKill.Size = UDim2.new(0, 73, 0, 50)
LKill.ZIndex = 2
LKill.Font = Enum.Font.SourceSans
LKill.Text = "Loopkill"
LKill.TextColor3 = Color3.fromRGB(255, 255, 255)
LKill.TextScaled = true
LKill.TextSize = 14.000
LKill.TextWrapped = true

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 0, 0)), ColorSequenceKeypoint.new(0.23, Color3.fromRGB(238, 0, 255)), ColorSequenceKeypoint.new(0.48, Color3.fromRGB(0, 0, 255)), ColorSequenceKeypoint.new(0.63, Color3.fromRGB(32, 244, 255)), ColorSequenceKeypoint.new(0.78, Color3.fromRGB(4, 255, 0)), ColorSequenceKeypoint.new(0.89, Color3.fromRGB(255, 255, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 0, 0))}
UIGradient_3.Parent = Frame

-- Scripts:

local function HJEL_fake_script() -- KillGui.LocalScript 
	local script = Instance.new('LocalScript', KillGui)

	script.Parent.Opener.MouseButton1Click:Connect(function()
		script.Parent.Frame.Visible = true
	end)
	
	script.Parent.Frame.Cancel.MouseButton1Click:Connect(function()
		script.Parent.Frame.Visible = false
	end)
	
	script.Parent.Frame.Kill.MouseButton1Click:Connect(function()
		game.Players:FindFirstChild(script.Parent.Frame.Player.Text).Character.Humanoid.Health = 0
		script.Parent.Frame.Visible = false
	end)
	
	script.Parent.Frame.LKill.MouseButton1Click:Connect(function()
		while true do
			game.Players:WaitForChild(script.Parent.Frame.Player.Text).Character.Humanoid.Health = 0
			wait(1)
		end
		
		script.Parent.Frame.Visible = false
	end)
end
coroutine.wrap(HJEL_fake_script)()
   end,
})
