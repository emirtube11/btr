local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/AikaV3rm/UiLib/master/Lib.lua')))()

local w = library:CreateWindow("Item Menu") -- Creates the window

local b = w:CreateFolder("Spawn Item") -- Creates the folder(U will put here your buttons,etc)

b:Dropdown("Select Item",{"Apple","Cookie","BloxyCola","EpicPizza"},true,function(mob) --true/false, replaces the current title "Dropdown" with the option that t
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer(mob)
end)

b:Button("Op Food",function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
end)

local s = library:CreateWindow("Role Menu") -- Creates the window

local g = s:CreateFolder("Change Role")

g:Button("Police",function()

local A_1 = "Gun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)

end)

g:Button("SWAT",function()

local A_1 = "SwatGun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)

end)

g:Button("Lollipop",function()

 
local A_1 = "Lollipop"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1)


end)

g:Button("Teddy",function()

 
-- Script generated by R2Sv2
-- R2Sv2 developed by Luckyxero
 
local A_1 = "TeddyBloxpin"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.MakeRole
Event:FireServer(A_1, A_2)



end)

g:Button("Chips",function()

 
-- Script generated by R2Sv2
-- R2Sv2 developed by Luckyxero
 
local A_1 = "Chips"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.MakeRole
Event:FireServer(A_1, A_2)



end)
