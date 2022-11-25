local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
 
--Properties:
 
ScreenGui.Parent = game:GetService("CoreGui")
 
Frame.Name = "Frame"
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(-0.254758418, 0, -0.37299037, 0)
Frame.Size = UDim2.new(0, 2061, 0, 1048)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(57, 57, 57)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120
 
TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.419472903, 0, 0.443729907, 0)
TextLabel.Size = UDim2.new(0, 219, 0, 70)
TextLabel.Font = Enum.Font.SpecialElite
TextLabel.Text = "Dargon x hub"
TextLabel.TextColor3 = Color3.fromRGB(247, 72, 119)
TextLabel.TextSize = 100.000
TextLabel.TextStrokeTransparency = 0.000
wait(3)
game.CoreGui:FindFirstChild("ScreenGui"):Destroy()

local Allowed = loadstring(game:HttpGet("https://pastebin.com/raw/xSMRnJ6f", true))()
if Allowed[game.Players.LocalPlayer.UserId] then
print("You are whitelist")
else
print("You are not whitelist")
end
getgenv().Settings = {
['Name'] = 'Dragon X Hub',
['Intro'] = true,
['Keybind'] = 'T'
}

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/kickTh/New-Ui/main/Shadow%20Lib%20v2.txt", true))()


local Tab1 = Library:CreateTab('Main')

Tab1:Label('Label')
Tab1:Button('Keyborad', function()loadstring(game:HttpGet("https://raw.githubusercontent.com/advxzivhsjjdhxhsidifvsh/mobkeyboard/main/main.txt", true))()
 
end)
Tab1:Label('Label')
Tab1:Button('mink v4', function()loadstring(game:HttpGet("https://raw.githubusercontent.com/chirin111/MinkV4/main/README.md"))();
end)
Tab1:Toggle('Fast attack', false, function(vu)
_G.Toggle = loadstring(game:HttpGet("https://pastebin.com/raw/1ssrkVwW"))();
end)
