--Bu script tamamen Deku Tr'ye aittir eğer çalmaya çalışan veya ismini değiştiren hakkında hukuki süreç başlatılacaktır.


local DekuHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local WelcometoDekuHub = Instance.new("TextLabel")
local ShindoLife = Instance.new("TextButton")
local PetSimulatorX = Instance.new("TextButton")



DekuHub.Name = "Deku Hub"
DekuHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DekuHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = DekuHub
Frame.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Frame.Position = UDim2.new(0.658124447, 0, 0.681135178, 0)
Frame.Size = UDim2.new(0, 386, 0, 191)

WelcometoDekuHub.Name = "Welcome to Deku Hub"
WelcometoDekuHub.Parent = Frame
WelcometoDekuHub.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
WelcometoDekuHub.BorderColor3 = Color3.fromRGB(75, 75, 75)
WelcometoDekuHub.Size = UDim2.new(0, 381, 0, 34)
WelcometoDekuHub.Font = Enum.Font.SourceSans
WelcometoDekuHub.Text = "Deku Hub'a Hoş Geldin!"
WelcometoDekuHub.TextColor3 = Color3.fromRGB(163, 163, 163)
WelcometoDekuHub.TextScaled = true
WelcometoDekuHub.TextSize = 14.000
WelcometoDekuHub.TextWrapped = true

ShindoLife.Name = "Shindo Life"
ShindoLife.Parent = Frame
ShindoLife.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
ShindoLife.BorderColor3 = Color3.fromRGB(75, 75, 75)
ShindoLife.Position = UDim2.new(0, 0, 0.178226724, 0)
ShindoLife.Size = UDim2.new(0, 90, 0, 25)
ShindoLife.Font = Enum.Font.SourceSans
ShindoLife.Text = "Shindo Life"
ShindoLife.TextColor3 = Color3.fromRGB(163, 163, 163)
ShindoLife.TextSize = 14.000

PetSimulatorX.Name = "Pet Simulator X"
PetSimulatorX.Parent = Frame
PetSimulatorX.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
PetSimulatorX.BorderColor3 = Color3.fromRGB(75, 75, 75)
PetSimulatorX.Position = UDim2.new(0.236344218, 0, 0.178226724, 0)
PetSimulatorX.Size = UDim2.new(0, 90, 0, 25)
PetSimulatorX.Font = Enum.Font.SourceSans
PetSimulatorX.Text = "Pet Simulator X"
PetSimulatorX.TextColor3 = Color3.fromRGB(163, 163, 163)
PetSimulatorX.TextSize = 14.000

-- Scripts:

local function IIHVFHB_fake_script() -- ShindoLife.LocalScript 
	local script = Instance.new('LocalScript', ShindoLife)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/6Wumpus6/SpyHub/main/ShindoLife"))()
	end)
end
coroutine.wrap(IIHVFHB_fake_script)()
local function RKTTL_fake_script() -- PetSimulatorX.LocalScript 
	local script = Instance.new('LocalScript', PetSimulatorX)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/TurfuGoldy/GoldenScripts/main/EzPets.lua"))()
	end)
end
coroutine.wrap(RKTTL_fake_script)()
