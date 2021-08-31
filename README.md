--Bu script tamamen Deku Tr'ye aittir eğer çalmaya çalışan veya ismini değiştiren hakkında hukuki süreç başlatılacaktır.

local DekuHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local WelcometoDekuHub = Instance.new("TextLabel")
local PetSimulatorX = Instance.new("TextButton")

DekuHub.Name = "Deku Hub"
DekuHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DekuHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = DekuHub
Frame.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Frame.Position = UDim2.new(0.159894377, 0, 0.158597618, 0)
Frame.Size = UDim2.new(0, 460, 0, 341)

WelcometoDekuHub.Name = "Welcome to Deku Hub"
WelcometoDekuHub.Parent = Frame
WelcometoDekuHub.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
WelcometoDekuHub.BorderColor3 = Color3.fromRGB(75, 75, 75)
WelcometoDekuHub.Size = UDim2.new(0, 460, 0, 61)
WelcometoDekuHub.Font = Enum.Font.SourceSans
WelcometoDekuHub.Text = "Deku Hub'a Hoş Geldin!"
WelcometoDekuHub.TextColor3 = Color3.fromRGB(163, 163, 163)
WelcometoDekuHub.TextScaled = true
WelcometoDekuHub.TextSize = 14.000
WelcometoDekuHub.TextWrapped = true

PetSimulatorX.Name = "Pet Simulator X"
PetSimulatorX.Parent = Frame
PetSimulatorX.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
PetSimulatorX.BorderColor3 = Color3.fromRGB(75, 75, 75)
PetSimulatorX.Position = UDim2.new(0, 0, 0.178226724, 0)
PetSimulatorX.Size = UDim2.new(0, 109, 0, 38)
PetSimulatorX.Font = Enum.Font.SourceSans
PetSimulatorX.Text = "Pet Simulator X"
PetSimulatorX.TextColor3 = Color3.fromRGB(163, 163, 163)
PetSimulatorX.TextSize = 14.000

-- Scripts:

local function VTECVF_fake_script() -- PetSimulatorX.LocalScript 
	local script = Instance.new('LocalScript', PetSimulatorX)

	script.parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/TurfuGoldy/GoldenScripts/main/EzPets.lua"))()
	end)
end
coroutine.wrap(VTECVF_fake_script)()
