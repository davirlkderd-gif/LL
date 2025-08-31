#-- Script "Você Tomou Scam"
local ScreenGui = Instance.new("ScreenGui")
local TextLabel = Instance.new("TextLabel")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

TextLabel.Parent = ScreenGui
TextLabel.Size = UDim2.new(1, 0, 1, 0)
TextLabel.BackgroundTransparency = 1
TextLabel.Text = "VOCÊ TOMOU SCAM"
TextLabel.TextColor3 = Color3.new(1, 0, 0) -- vermelho
TextLabel.TextScaled = true
TextLabel.Font = Enum.Font.SourceSansBold
