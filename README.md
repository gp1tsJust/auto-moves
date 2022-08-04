

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local on = Instance.new("TextButton")
local off = Instance.new("TextButton")
local titolo = Instance.new("TextLabel")
local X = Instance.new("TextButton")
local open = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(72, 72, 72)
Frame.BorderColor3 = Color3.fromRGB(30, 30, 30)
Frame.Position = UDim2.new(0, 0, 0.475260407, 0)
Frame.Size = UDim2.new(0, 171, 0, 110)

on.Name = "on"
on.Parent = Frame
on.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
on.Position = UDim2.new(0.0514749065, 0, 0.396614552, 0)
on.Size = UDim2.new(0, 67, 0, 21)
on.Font = Enum.Font.SourceSans
on.Text = "On"
on.TextColor3 = Color3.fromRGB(0, 0, 0)
on.TextScaled = true
on.TextSize = 14.000
on.TextWrapped = true

off.Name = "off"
off.Parent = Frame
off.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
off.Position = UDim2.new(0.548550904, 0, 0.396614552, 0)
off.Size = UDim2.new(0, 67, 0, 21)
off.Font = Enum.Font.SourceSans
off.Text = "Off"
off.TextColor3 = Color3.fromRGB(0, 0, 0)
off.TextScaled = true
off.TextSize = 14.000
off.TextWrapped = true

titolo.Name = "titolo"
titolo.Parent = Frame
titolo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
titolo.Position = UDim2.new(0, 0, -0.00745738624, 0)
titolo.Size = UDim2.new(0, 170, 0, 31)
titolo.Font = Enum.Font.SourceSans
titolo.Text = "Auto Moves"
titolo.TextColor3 = Color3.fromRGB(0, 0, 0)
titolo.TextScaled = true
titolo.TextSize = 14.000
titolo.TextWrapped = true

X.Name = "X"
X.Parent = Frame
X.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
X.Position = UDim2.new(0.86402303, 0, -0.00772705069, 0)
X.Size = UDim2.new(0, 22, 0, 31)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.fromRGB(0, 0, 0)
X.TextScaled = true
X.TextSize = 14.000
X.TextWrapped = true

open.Name = "open"
open.Parent = ScreenGui
open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open.Position = UDim2.new(0, 0, 0.118844688, 0)
open.Size = UDim2.new(0, 62, 0, 22)
open.Font = Enum.Font.SourceSans
open.Text = "open"
open.TextColor3 = Color3.fromRGB(0, 0, 0)
open.TextScaled = true
open.TextSize = 14.000
open.TextWrapped = true

UICorner.CornerRadius = UDim.new(0.200000003, 0)
UICorner.Parent = open

-- Scripts:

local function XDWBH_fake_script() -- on.Script 
	local script = Instance.new('Script', on)

	function Click(mouse)
		getgenv().on = true
		
		while getgenv().on == true do
			getgenv().on = true
			
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Meteor Crash"])
			game.Players.LocalPlayer.Character["Meteor Crash"]:Activate()
			wait ()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Anger Rush"])
			game.Players.LocalPlayer.Character["Anger Rush"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Neo Wolf Fang Fist"])
			game.Players.LocalPlayer.Character["Neo Wolf Fang Fist"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Wolf Fang Fist"])
			game.Players.LocalPlayer.Character["Wolf Fang Fist"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Mach Kick"])
			game.Players.LocalPlayer.Character["Mach Kick"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["TS Molotov"])
			game.Players.LocalPlayer.Character["TS Molotov"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Vital Strike"])
			game.Players.LocalPlayer.Character["Vital Strike"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Strong Kick"])
			game.Players.LocalPlayer.Character["Strong Kick"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Kick Barrage"])
			game.Players.LocalPlayer.Character["Kick Barrage"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["Deadly Dance"])
			game.Players.LocalPlayer.Character["Deadly Dance"]:Activate()
			wait()
			game.Players.LocalPlayer.Character.Humanoid:EquipTool(game.Players.LocalPlayer.Backpack["God Slicer"])
			game.Players.LocalPlayer.Character["God Slicer"]:Activate()
			wait()
			
	
		end
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(XDWBH_fake_script)()
local function FUVXWDK_fake_script() -- off.Script 
	local script = Instance.new('Script', off)

	function Click(mouse)
	
		getgenv().on = false
	
	end
	
	
	script.Parent.MouseButton1Down:connect(Click)
end
coroutine.wrap(FUVXWDK_fake_script)()
local function ELYVQ_fake_script() -- X.CloseScript 
	local script = Instance.new('LocalScript', X)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.PlayerGui.ScreenGui.Frame.Visible = false
	end)
end
coroutine.wrap(ELYVQ_fake_script)()
local function XSZVOTF_fake_script() -- open.OpenScript 
	local script = Instance.new('LocalScript', open)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.PlayerGui.ScreenGui.Frame.Visible = true
	end)
end
coroutine.wrap(XSZVOTF_fake_script)()
