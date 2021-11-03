local ScreenGui = Instance.new("ScreenGui")
local ButtonInf = Instance.new("ImageLabel")
local InfMoney = Instance.new("Sound")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ButtonInf.Parent = ScreenGui
ButtonInf.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ButtonInf.Position = UDim2.new(0.2, 0, 0.1, 0)
ButtonInf.Size = UDim2.new(0, 770, 0, 770)
ButtonInf.Image = "rbxassetid://7669061804"


InfMoney.Name = "1000000000000000000000000000000000000000000000000000000000000000"
InfMoney.SoundId = "rbxassetid://7669033962"
InfMoney.Volume = 100
InfMoney.Looped = true
InfMoney.archivable = false
InfMoney.Parent = game.Workspace

InfMoney:Play()
