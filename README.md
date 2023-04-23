local Mercury = loadstring(game:HttpGet("https://raw.githubusercontent.com/buslate/AA/main/README.md"))()
local GUI = Mercury:Create{
    Name = "BusLate TP",
    Size = UDim2.fromOffset(600, 400),
    Theme = Mercury.Themes.Dark,
    Link = "https://Lovemum"
}
local Tab = GUI:Tab{
	Name = "Teleport Tab",
	Icon = "rbxassetid://13170451197"
}
Tab:Button{
	Name = "Lobby",
	Description = nil,
	Callback = function() 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2118.929931640625, 48.30112075805664, -4487.89697265625)
end
}
Tab:Button{
	Name = "Pirate",
	Description = nil,
	Callback = function() 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-675.433349609375, 37.891265869140625, -3407.065185546875)
end
}
Tab:Button{
	Name = "Small Marines",
	Description = nil,
	Callback = function() 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2374.393798828125, 39.81367111206055, -2720.684814453125)
end
}
Tab:Button{
	Name = "Sunji",
	Description = nil,
	Callback = function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4161.08447265625, 108.5559310913086, -2978.4208984375)
end
}
GUI:Notification{
	Title = "Alert",
	Text = "LoveNual",
	Duration = 5,
	Callback = function() end
}
