local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("King Hub", "DarkTheme") 


--ARSENAL

local Tab = Window:NewTab("ARSENAL")
ARSENAL = Tab:NewSection("ARSENAL")

ARSENAL:NewButton("DarkHub", "Goodluck", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/RandomAdamYT/DarkHub/master/Init'), true))()
end)

--Blox Fruit

local Tab = Window:NewTab("Blox fruit")
BloxFruit = Tab:NewSection("Blox Fruit")

BloxFruit:NewButton("EvilHub", "Goodluck", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Natthawat69/EvilHub-FREE/main/Script.lua"))()
 end)

 BloxFruit:NewButton("MammozHub", "Goodluck", function()
    library = {
    LeftFrameGradient = ColorSequence.new {
        ColorSequenceKeypoint.new(0.00, Color3.fromRGB(45, 32, 120)),
        ColorSequenceKeypoint.new(1.00, Color3.fromRGB(81, 90, 167))
    },
    BackGround = Color3.fromRGB(33, 33, 56),
    Button = Color3.fromRGB(66, 59, 144),
    Button2 = Color3.fromRGB(29, 29, 89),
    TitleText = Color3.fromRGB(121, 121, 216)
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/toeydeklnw/HUB-obfuscator/main/mammoz.lua"))()
end)

BloxFruit:NewButton("PolarHub", "Goodluck", function()
    _G.Keys = "PolarhubIStheBest" 
_G.Color = Color3.fromRGB(222, 37, 0)
loadstring(game:HttpGet("https://polarhub.xyz/xenon.lua"))()
end)

BloxFruit:NewButton("MheeHub", "Goodluck", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/BunnySalf/Hentai/main/MHEEHUB",true))()
 end)




