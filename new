-- Gui to Lua
-- Version: 3.2

-- Instances:

local ErenHub = Instance.new("ScreenGui")
local ErenHub_2 = Instance.new("Frame")
local uic = Instance.new("UICorner")
local ErenHubLabel1 = Instance.new("TextLabel")
local PageHolder = Instance.new("Frame")
local uic_2 = Instance.new("UICorner")
local Page = Instance.new("ScrollingFrame")
local ToggleFrame = Instance.new("Frame")
local ToggleAutoSteps = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local AutoSteps = Instance.new("TextButton")
local ToggleAutoHoop = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local ToggleAutoRebirths = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Line = Instance.new("Frame")
local Line_2 = Instance.new("Frame")
local Line_3 = Instance.new("Frame")
local Line_4 = Instance.new("Frame")
local AutoHoop = Instance.new("TextButton")
local AutoRebirths = Instance.new("TextButton")
local Page1 = Instance.new("ScrollingFrame")
local uic_3 = Instance.new("UICorner")
local Magmacity = Instance.new("TextButton")
local uic_4 = Instance.new("UICorner")
local Electrocity = Instance.new("TextButton")
local uic_5 = Instance.new("UICorner")
local TabFrame = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local Farm = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Teleport = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local closeopen = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")

--Properties:

ErenHub.Name = "ErenHub"
ErenHub.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ErenHub.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ErenHub_2.Name = "ErenHub"
ErenHub_2.Parent = ErenHub
ErenHub_2.BackgroundColor3 = Color3.fromRGB(7, 57, 98)
ErenHub_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ErenHub_2.BorderSizePixel = 5
ErenHub_2.Position = UDim2.new(0.425036401, 0, 0.399002492, 0)
ErenHub_2.Size = UDim2.new(0, 184, 0, 218)

uic.Name = "uic"
uic.Parent = ErenHub_2

ErenHubLabel1.Name = "ErenHubLabel1"
ErenHubLabel1.Parent = ErenHub_2
ErenHubLabel1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ErenHubLabel1.BackgroundTransparency = 2.000
ErenHubLabel1.BorderColor3 = Color3.fromRGB(0, 0, 0)
ErenHubLabel1.BorderSizePixel = 0
ErenHubLabel1.SelectionImageObject = Page
ErenHubLabel1.Size = UDim2.new(0, 102, 0, 25)
ErenHubLabel1.Font = Enum.Font.RobotoCondensed
ErenHubLabel1.Text = "ErenHub"
ErenHubLabel1.TextColor3 = Color3.fromRGB(255, 255, 255)
ErenHubLabel1.TextSize = 15.000
ErenHubLabel1.TextXAlignment = Enum.TextXAlignment.Left

PageHolder.Name = "PageHolder"
PageHolder.Parent = ErenHub_2
PageHolder.BackgroundColor3 = Color3.fromRGB(7, 57, 98)
PageHolder.BorderColor3 = Color3.fromRGB(0, 0, 0)
PageHolder.BorderSizePixel = 0
PageHolder.Position = UDim2.new(0, 0, 0, 33)
PageHolder.Size = UDim2.new(0, 184, 0, 185)

uic_2.Name = "uic"
uic_2.Parent = PageHolder

Page.Name = "Page"
Page.Parent = PageHolder
Page.Active = true
Page.BackgroundColor3 = Color3.fromRGB(7, 57, 98)
Page.BorderColor3 = Color3.fromRGB(0, 0, 0)
Page.BorderSizePixel = 0
Page.Size = UDim2.new(0, 184, 0, 185)


ToggleFrame.Name = "ToggleFrame"
ToggleFrame.Parent = Page
ToggleFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ToggleFrame.BackgroundTransparency = 5.000
ToggleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ToggleFrame.BorderSizePixel = 0
ToggleFrame.Size = UDim2.new(0, 184, 0, 140)

ToggleAutoSteps.Name = "ToggleAutoSteps"
ToggleAutoSteps.Parent = ToggleFrame
ToggleAutoSteps.BackgroundColor3 = Color3.fromRGB(211, 0, 0)
ToggleAutoSteps.BorderColor3 = Color3.fromRGB(0, 0, 0)
ToggleAutoSteps.BorderSizePixel = 0
ToggleAutoSteps.Position = UDim2.new(0.5053913, 0, 0.0768572092, 0)
ToggleAutoSteps.Size = UDim2.new(0, 19, 0, 23)

UICorner.CornerRadius = UDim.new(0, 4)
UICorner.Parent = ToggleAutoSteps

AutoSteps.Name = "Auto Steps"
AutoSteps.Parent = ToggleFrame
AutoSteps.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoSteps.BackgroundTransparency = 5.000
AutoSteps.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoSteps.BorderSizePixel = 0
AutoSteps.Position = UDim2.new(0, 0, 0.021428572, 0)
AutoSteps.Size = UDim2.new(0, 118, 0, 38)
AutoSteps.Font = Enum.Font.RobotoCondensed
AutoSteps.Text = "Auto Steps"
AutoSteps.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoSteps.TextSize = 20.000
AutoSteps.TextTransparency = 0.100
AutoSteps.TextXAlignment = Enum.TextXAlignment.Left
AutoSteps.MouseButton1Down:Connect(function()
    ToggleEnabled = not ToggleEnabled
    if ToggleEnabled then 
        game:GetService("TweenService"):Create(Toggle,TweenInfo.new(0.25),{BackgroundColor3=Color3.fromRGB(0, 211, 0)}):Play()
    else
        game:GetService("TweenService"):Create(Toggle,TweenInfo.new(0.25),{BackgroundColor3=Color3.fromRGB(211, 0, 0)}):Play()
        getgenv().AutoSteps = false
    end
    pcall(callback,ToggleEnabled)
end)

ToggleAutoHoop.Name = "ToggleAutoHoop"
ToggleAutoHoop.Parent = ToggleFrame
ToggleAutoHoop.BackgroundColor3 = Color3.fromRGB(211, 0, 0)
ToggleAutoHoop.BorderColor3 = Color3.fromRGB(0, 0, 0)
ToggleAutoHoop.BorderSizePixel = 0
ToggleAutoHoop.Position = UDim2.new(0.5053913, 0, 0.326857209, 0)
ToggleAutoHoop.Size = UDim2.new(0, 19, 0, 23)

UICorner_2.CornerRadius = UDim.new(0, 4)
UICorner_2.Parent = ToggleAutoHoop

ToggleAutoRebirths.Name = "ToggleAutoRebirths"
ToggleAutoRebirths.Parent = ToggleFrame
ToggleAutoRebirths.BackgroundColor3 = Color3.fromRGB(211, 0, 0)
ToggleAutoRebirths.BorderColor3 = Color3.fromRGB(0, 0, 0)
ToggleAutoRebirths.BorderSizePixel = 0
ToggleAutoRebirths.Position = UDim2.new(0.553912938, 0, 0.578571439, 0)
ToggleAutoRebirths.Size = UDim2.new(0, 19, 0, 23)

UICorner_3.CornerRadius = UDim.new(0, 4)
UICorner_3.Parent = ToggleAutoRebirths

Line.Name = "Line"
Line.Parent = Page
Line.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Line.BorderColor3 = Color3.fromRGB(0, 0, 0)
Line.BorderSizePixel = 0
Line.Position = UDim2.new(0, 0, 0.116736829, 0)
Line.Size = UDim2.new(0, 184, 0, 1)

Line_2.Name = "Line"
Line_2.Parent = Line
Line_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Line_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Line_2.BorderSizePixel = 0
Line_2.Position = UDim2.new(0, 0, 32, 0)
Line_2.Size = UDim2.new(0, 184, 0, 1)

Line_3.Name = "Line"
Line_3.Parent = Line
Line_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Line_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Line_3.BorderSizePixel = 0
Line_3.Position = UDim2.new(0, 0, 61, 0)
Line_3.Size = UDim2.new(0, 184, 0, 1)

Line_4.Name = "Line"
Line_4.Parent = Line
Line_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Line_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Line_4.BorderSizePixel = 0
Line_4.Position = UDim2.new(0, 0, -41.8832703, 0)
Line_4.Size = UDim2.new(0, 184, 0, 1)

AutoHoop.Name = "Auto Hoop"
AutoHoop.Parent = Page
AutoHoop.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoHoop.BackgroundTransparency = 2.000
AutoHoop.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoHoop.BorderSizePixel = 0
AutoHoop.Position = UDim2.new(0, 0, 0.113513514, 0)
AutoHoop.Size = UDim2.new(0, 117, 0, 31)
AutoHoop.Font = Enum.Font.RobotoCondensed
AutoHoop.Text = "Auto Hoop"
AutoHoop.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoHoop.TextSize = 20.000
AutoHoop.TextXAlignment = Enum.TextXAlignment.Left
AutoHoop.MouseButton1Down:Connect(function()
    ToggleEnabled = not ToggleEnabled
    if ToggleEnabled then 
        game:GetService("TweenService"):Create(Toggle,TweenInfo.new(0.25),{BackgroundColor3=Color3.fromRGB(0, 211, 0)}):Play()
    else
        game:GetService("TweenService"):Create(Toggle,TweenInfo.new(0.25),{BackgroundColor3=Color3.fromRGB(211, 0, 0)}):Play()
        getgenv().AutoSteps = false
    end
    pcall(callback,ToggleEnabled)
end)

AutoRebirths.Name = "Auto Rebirths"
AutoRebirths.Parent = Page
AutoRebirths.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoRebirths.BackgroundTransparency = 1.000
AutoRebirths.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoRebirths.BorderSizePixel = 0
AutoRebirths.Position = UDim2.new(0, 0, 0.200000003, 0)
AutoRebirths.Size = UDim2.new(0, 129, 0, 31)
AutoRebirths.Font = Enum.Font.RobotoCondensed
AutoRebirths.Text = "Auto Rebirths"
AutoRebirths.TextColor3 = Color3.fromRGB(255, 255, 255)
AutoRebirths.TextSize = 20.000
AutoRebirths.TextXAlignment = Enum.TextXAlignment.Left
AutoRebirths.MouseButton1Down:Connect(function()
    ToggleEnabled = not ToggleEnabled
    if ToggleEnabled then 
        game:GetService("TweenService"):Create(Toggle,TweenInfo.new(0.25),{BackgroundColor3=Color3.fromRGB(0, 211, 0)}):Play()
    else
        game:GetService("TweenService"):Create(Toggle,TweenInfo.new(0.25),{BackgroundColor3=Color3.fromRGB(211, 0, 0)}):Play()
        getgenv().AutoSteps = false
    end
    pcall(callback,ToggleEnabled)
end)

Page1.Name = "Page1"
Page1.Parent = PageHolder
Page1.Active = true
Page1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Page1.BackgroundTransparency = 5.000
Page1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Page1.BorderSizePixel = 0
Page1.Position = UDim2.new(0, 0, 0.0324324332, 0)
Page1.Size = UDim2.new(0, 185, 0, 179)
Page1.Visible = false


uic_3.Name = "uic"
uic_3.Parent = Page1

Magmacity.Name = "Magma city"
Magmacity.Parent = Page1
Magmacity.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Magmacity.BorderColor3 = Color3.fromRGB(0, 0, 0)
Magmacity.BorderSizePixel = 0
Magmacity.Position = UDim2.new(0, 0, 0.02016172, 0)
Magmacity.Size = UDim2.new(0, 185, 0, 26)
Magmacity.Font = Enum.Font.RobotoCondensed
Magmacity.Text = "Magma city"
Magmacity.TextColor3 = Color3.fromRGB(255, 255, 255)
Magmacity.TextSize = 14.000
Magmacity.MouseButton1Down:Connect(function()
    local plr = game.Players.LocalPlayer
    local char = plr.Character
    char.HumanoidRootPart.CFrame = CFrame.new(-537.767456, 3.95088959, 386.226837, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)
uic_4.CornerRadius = UDim.new(0, 4)
uic_4.Name = "uic"
uic_4.Parent = Magmacity

Electrocity.Name = "Electro city"
Electrocity.Parent = Page1
Electrocity.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Electrocity.BorderColor3 = Color3.fromRGB(0, 0, 0)
Electrocity.BorderSizePixel = 0
Electrocity.Position = UDim2.new(0, 0, 0.0919544101, 0)
Electrocity.Size = UDim2.new(0, 185, 0, 26)
Electrocity.Font = Enum.Font.RobotoCondensed
Electrocity.Text = "Electro city"
Electrocity.TextColor3 = Color3.fromRGB(255, 255, 255)
Electrocity.TextSize = 14.000
Electrocity.MouseButton1Down:Connect(function()
    char.HumanoidRootPart.CFrame = CFrame.new(3682.60254, 71.5308151, 5592.50879, -0.0193620101, 3.62180188e-08, -0.999812543, 4.99353519e-08, 1, 3.52577771e-08, 0.999812543, -4.92433294e-08, -0.0193620101)
end)

uic_5.CornerRadius = UDim.new(0, 4)
uic_5.Name = "uic"
uic_5.Parent = Electrocity

TabFrame.Name = "TabFrame"
TabFrame.Parent = ErenHub_2
TabFrame.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TabFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TabFrame.BorderSizePixel = 0
TabFrame.Position = UDim2.new(0.451086968, 0, 0.0137614682, 0)
TabFrame.Size = UDim2.new(0, 101, 0, 30)

UICorner_4.Parent = TabFrame

Farm.Name = "Farm"
Farm.Parent = TabFrame
Farm.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Farm.BackgroundTransparency = 5.000
Farm.BorderColor3 = Color3.fromRGB(0, 0, 0)
Farm.BorderSizePixel = 0
Farm.Position = UDim2.new(0, 0, 0.0666666701, 0)
Farm.Size = UDim2.new(0, 56, 0, 25)
Farm.Font = Enum.Font.RobotoCondensed
Farm.Text = "Farm"
Farm.TextColor3 = Color3.fromRGB(255, 255, 255)
Farm.TextSize = 14.000
Farm.MouseButton1Down:Connect(function()
    for i,v in pairs(PagesHolder:GetChildren()) do
        if v:IsA("ErenHub") then
            v.Visible = false
        end
        Page.Visible = true
    end
    game:GetService("TweenService"):Create(TabButton,TweenInfo.new(0.25),{BackgroundTransparency=0.60}):Play()
    wait(0.01)
    game:GetService("TweenService"):Create(TabButton,TweenInfo.new(0.25),{BackgroundTransparency=0.80}):Play()
end)

UICorner_5.Parent = Farm

Teleport.Name = "Teleport"
Teleport.Parent = TabFrame
Teleport.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Teleport.BackgroundTransparency = 5.000
Teleport.BorderColor3 = Color3.fromRGB(0, 0, 0)
Teleport.BorderSizePixel = 0
Teleport.Position = UDim2.new(0.455445558, 0, 0.0666666701, 0)
Teleport.Size = UDim2.new(0, 56, 0, 25)
Teleport.Font = Enum.Font.RobotoCondensed
Teleport.Text = "Teleport"
Teleport.TextColor3 = Color3.fromRGB(255, 255, 255)
Teleport.TextSize = 14.000
Teleport.MouseButton1Down:Connect(function()
    for i,v in pairs(PagesHolder:GetChildren()) do
        if v:IsA("ErenHub") then
            v.Visible = false
        end
        Page1.Visible = true
    end
    game:GetService("TweenService"):Create(TabButton,TweenInfo.new(0.25),{BackgroundTransparency=0.60}):Play()
    wait(0.01)
    game:GetService("TweenService"):Create(TabButton,TweenInfo.new(0.25),{BackgroundTransparency=0.80}):Play()
end)

UICorner_6.Parent = Teleport

closeopen.Name = "close / open"
closeopen.Parent = ErenHub
closeopen.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
closeopen.BorderColor3 = Color3.fromRGB(0, 0, 0)
closeopen.BorderSizePixel = 0
closeopen.Position = UDim2.new(0.123726346, 0, 0.329177052, 0)
closeopen.Size = UDim2.new(0, 38, 0, 42)
closeopen.Font = Enum.Font.SourceSans
closeopen.Text = ""
closeopen.TextColor3 = Color3.fromRGB(0, 0, 0)
closeopen.TextSize = 14.000
closeopen.Parent.MouseButton1Click:Connect(function()
    local mk = script.Parent.Parent.ErenHub
	mk.Visible = not mk.Visible
	end)

UICorner_7.Parent = closeopen
