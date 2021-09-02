--Bu script tamamen Deku Tr'ye aittir eğer çalmaya çalışan veya ismini değiştiren hakkında hukuki süreç başlatılacaktır.





-- Gui to Lua
-- Version: 3.2

-- Instances:

local DekuHub = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local WelcometoDekuHub = Instance.new("TextLabel")

--Properties:

DekuHub.Name = "Deku Hub"
DekuHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
DekuHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = DekuHub
Frame.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
Frame.Position = UDim2.new(0.137758926, 0, 0.118530832, 0)
Frame.Size = UDim2.new(0, 476, 0, 103)

WelcometoDekuHub.Name = "Welcome to Deku Hub"
WelcometoDekuHub.Parent = Frame
WelcometoDekuHub.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
WelcometoDekuHub.BorderColor3 = Color3.fromRGB(75, 75, 75)
WelcometoDekuHub.Size = UDim2.new(0, 475, 0, 102)
WelcometoDekuHub.Font = Enum.Font.SourceSans
WelcometoDekuHub.Text = "Deku hub'ın bedava sürümü bulunmamaktadır lütfen satın alınız."
WelcometoDekuHub.TextColor3 = Color3.fromRGB(163, 163, 163)
WelcometoDekuHub.TextScaled = true
WelcometoDekuHub.TextSize = 14.000
WelcometoDekuHub.TextWrapped = true







