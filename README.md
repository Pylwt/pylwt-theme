local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()
local w = library:CreateWindow("Cosmos Hub")
local b = w:CreateFolder("Click Here")
b:Label("Choose A Theme",{
TextSize = 25; -- Self Explaining
TextColor = Color3.fromRGB(255,255,255);
BgColor = Color3.fromRGB(69,69,69);
}) 
b:Button("OG Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/OG-Pylwt/main/README.md", true))()
end)
b:Button("RGB Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/RGB-Pylwt/main/README.md", true))()
end)
b:Button("Light Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/light/main/theme", true))()

end)
b:Button("Grape Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/grape/main/theme", true))()

end)
b:Button("Blood Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/blood/main/theme", true))()

end)
b:Button("Ocean Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/ocean/main/theme", true))()

end)
b:Button("Midnight Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/midnight/main/theme", true))()

end)
b:Button("Sentinel Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/sentinel/main/theme", true))()

end)
b:Button("Synapse Theme",function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Pylwt/synapse/main/theme", true))()

end)
b:DestroyGui()
