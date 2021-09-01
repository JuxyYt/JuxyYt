--Bu script tamamen Deku Tr'ye aittir eğer çalmaya çalışan veya ismini değiştiren hakkında hukuki süreç başlatılacaktır.









local DekuHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local WelcometoDekuHub = Instance.new("TextLabel")
local ShindoLife = Instance.new("TextButton")
local PetSimulatorX = Instance.new("TextButton")
local AnimeFightersMurderMystery = Instance.new("TextButton")
local StandAwakening = Instance.new("TextButton")
local ShindoLifewar = Instance.new("TextButton")



DekuHub.Name = "Deku Hub"
DekuHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DekuHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = DekuHub
Frame.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Frame.Position = UDim2.new(0.684673071, 0, 0.696160197, 0)
Frame.Size = UDim2.new(0, 356, 0, 182)

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

AnimeFightersMurderMystery.Name = "Anime Fighters-Murder Mystery"
AnimeFightersMurderMystery.Parent = Frame
AnimeFightersMurderMystery.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
AnimeFightersMurderMystery.BorderColor3 = Color3.fromRGB(75, 75, 75)
AnimeFightersMurderMystery.Position = UDim2.new(0.468911916, 0, 0.17822665, 0)
AnimeFightersMurderMystery.Size = UDim2.new(0, 178, 0, 25)
AnimeFightersMurderMystery.Font = Enum.Font.SourceSans
AnimeFightersMurderMystery.Text = "Anime Fighters-Murder Mystery 2"
AnimeFightersMurderMystery.TextColor3 = Color3.fromRGB(163, 163, 163)
AnimeFightersMurderMystery.TextSize = 14.000

StandAwakening.Name = "Stand Awakening"
StandAwakening.Parent = Frame
StandAwakening.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
StandAwakening.BorderColor3 = Color3.fromRGB(75, 75, 75)
StandAwakening.Position = UDim2.new(0.00777202053, 0, 0.309116691, 0)
StandAwakening.Size = UDim2.new(0, 88, 0, 25)
StandAwakening.Font = Enum.Font.SourceSans
StandAwakening.Text = "Stand Awakening"
StandAwakening.TextColor3 = Color3.fromRGB(163, 163, 163)
StandAwakening.TextSize = 14.000

ShindoLifewar.Name = "Shindo Life war"
ShindoLifewar.Parent = Frame
ShindoLifewar.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
ShindoLifewar.BorderColor3 = Color3.fromRGB(75, 75, 75)
ShindoLifewar.Position = UDim2.new(0.235751301, 0, 0.309116691, 0)
ShindoLifewar.Size = UDim2.new(0, 137, 0, 25)
ShindoLifewar.Font = Enum.Font.SourceSans
ShindoLifewar.Text = "Shindo Life War Mode AF"
ShindoLifewar.TextColor3 = Color3.fromRGB(163, 163, 163)
ShindoLifewar.TextSize = 14.000

-- Scripts:

local function RHVMJ_fake_script() -- ShindoLife.LocalScript 
	local script = Instance.new('LocalScript', ShindoLife)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/reavscripts/sl2-hub/main/autofarm"))()
	end)
end
coroutine.wrap(RHVMJ_fake_script)()
local function QEAVKB_fake_script() -- PetSimulatorX.LocalScript 
	local script = Instance.new('LocalScript', PetSimulatorX)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/TurfuGoldy/GoldenScripts/main/EzPets.lua"))()
	end)
end
coroutine.wrap(QEAVKB_fake_script)()
local function QZSSUXN_fake_script() -- AnimeFightersMurderMystery.LocalScript 
	local script = Instance.new('LocalScript', AnimeFightersMurderMystery)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game.HttpGet(game, "https://raw.githubusercontent.com/KiJinGaming/FreeScript/main/KJHub.lua"))();
	end)
end
coroutine.wrap(QZSSUXN_fake_script)()
local function MAJBAF_fake_script() -- StandAwakening.LocalScript 
	local script = Instance.new('LocalScript', StandAwakening)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Bebo-Mods/BeboScripts/main/StandAwekening.lua"))()
	end)
end
coroutine.wrap(MAJBAF_fake_script)()
local function EJMK_fake_script() -- ShindoLifewar.LocalScript 
	local script = Instance.new('LocalScript', ShindoLifewar)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/reavscripts/sl2-hub/main/war
	end)
end
coroutine.wrap(EJMK_fake_script)()



