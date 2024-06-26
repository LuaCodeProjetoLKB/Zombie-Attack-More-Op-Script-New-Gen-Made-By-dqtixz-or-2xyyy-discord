warn("Copy With No Permisson = No Skill :D")
game.StarterGui:SetCore("SendNotification", {
Title = "Z-A / Zombie Attack - https://discord.gg/daXpGWF2SV",
Text = "Script Made By 2xyyy discord suport: Mobile, Solara, Krampus(Down)",
Duration = 3.5,
})
wait(0.1)
game.StarterGui:SetCore("SendNotification", {
Title = "Logs Script:",
Text = "Anti-Afk, Bugs Fixed, Script +",
Duration = 3.5,
})
wait(1.5)
wait(0.1)
game.StarterGui:SetCore("SendNotification", {
Title = "Loading Script...",
Text = "Z-A Loading...",
Duration = 2.3,
})
wait(2.5)
local SolaraScriptZA = loadstring(game:HttpGet("https://raw.githubusercontent.com/dqtixz/Library-UI-Projeto-LKA-Scriptblox-Custom/main/Free"))()
local Main = SolaraScriptZA:CreateTab("Main")
local Combat = SolaraScriptZA:CreateTab("Combat")
local Crates = SolaraScriptZA:CreateTab("Crates")
local Credits = SolaraScriptZA:CreateTab("Credits")
local CombatCg = Combat:CreateSection("Main")
local MainSection = Main:CreateSection("Farm")
local ConfigSection = Main:CreateSection("Config")
local Crates = Crates:CreateSection("Crates")
local HDVBFD = Credits:CreateSection("Credits")
--[[
if _G.Settings == true then
  _G.farm2 = false-- true / false Auto Farm
_G.groundDistance = 0 -- <> Value <> Auto Farm +/- Up / Down
_G.dist = 100000 -- <> Value <> Search-Zombie Distance
_G.HeadSize = 2.5 -- <> Value <> Hitbox
_G.autoequip = false-- true / false Auto Equip Tools + Duplicate Guns More Damage OP
_G.AutoGetPowerups = false -- true / false Auto Get powerups Motolov, Granade ect...]]
--[[elseif _G.Settings == false then
  Settings()
end]]
--[[
local function Settings()
_G.farm2 = false-- true / false Auto Farm
_G.groundDistance = 0 -- <> Value <> Auto Farm +/- Up / Down
_G.dist = 100000 -- <> Value <> Search-Zombie Distance
_G.HeadSize = 2.5 -- <> Value <> Hitbox
_G.autoequip = false-- true / false Auto Equip Tools + Duplicate Guns More Damage OP
_G.AutoGetPowerups = false -- true / false Auto Get powerups Motolov, Granade ect...
-- _G.AutoBuyGuns = false -- Future Updates...
-- _G.AutoUpdateGuns = false -- Future Updates...
end]]

HDVBFD:CreateButton("Rainbow (Beta-V1)", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "Rainbow Active",
Text = "(Client)",
Duration = 2.3,
})
wait(0.1)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Função para gerar uma cor aleatória com valores mais altos
local function randomColor()
    return Color3.new(math.random(0, 255)/255, math.random(0, 255)/255, math.random(0, 255)/255)
end

-- Função para aplicar uma cor suavemente
local function lerpColor(startColor, endColor, alpha)
    return startColor:Lerp(endColor, alpha)
end

-- Tempo de transição (em segundos)
local transitionTime = 0.5

-- Remover camisa e calça do jogador
character.Shirt:Destroy()
character.Pants:Destroy()

-- Loop infinito para alterar as cores do corpo
while true do
    local startTime = tick()
    local endTime = startTime + transitionTime
    
    local startColor = randomColor()
    local endColor = randomColor()
    
    while tick() < endTime do
        local elapsedTime = tick() - startTime
        local alpha = elapsedTime / transitionTime
        
        for _, part in ipairs(character:GetDescendants()) do
            if part:IsA("BasePart") then
                part.Color = lerpColor(startColor, endColor, alpha)
                part.Transparency = 0.25
                part.Material = Enum.Material.ForceField -- Aqui está a linha que adiciona o material ForceField
            end
        end
        
        wait()
    end
end
end)

HDVBFD:CreateButton("Rainbow (Beta-V2)", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "Rainbow Active",
Text = "(Client)",
Duration = 2.3,
})
wait(0.1)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Função para gerar uma cor aleatória com valores mais altos
local function randomColor()
    return Color3.new(math.random(0, 255)/255, math.random(0, 255)/255, math.random(0, 255)/255)
end

-- Função para aplicar uma cor suavemente
local function lerpColor(startColor, endColor, alpha)
    return startColor:Lerp(endColor, alpha)
end

-- Tempo de transição (em segundos)
local transitionTime = 0.42

-- Remover camisa e calça do jogador
character.Shirt:Destroy()
character.Pants:Destroy()

-- Loop infinito para alterar as cores do corpo
while true do
    local startTime = tick()
    local endTime = startTime + transitionTime
    
    local startColor = randomColor()
    local endColor = randomColor()
    
    while tick() < endTime do
        local elapsedTime = tick() - startTime
        local alpha = elapsedTime / transitionTime
        
        for _, part in ipairs(character:GetDescendants()) do
            if part:IsA("BasePart") then
                part.Color = lerpColor(startColor, endColor, alpha)
                part.Transparency = 0.35
                part.Material = Enum.Material.ForceField -- Aqui está a linha que adiciona o material ForceField
            end
        end
        
        wait()
    end
end
end)

HDVBFD:CreateButton("Rainbow (Beta-V3)", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "Rainbow Active",
Text = "(Client)",
Duration = 2.3,
})
wait(0.1)
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

-- Função para gerar uma cor aleatória com valores mais altos
local function randomColor()
    return Color3.new(math.random(0, 255)/255, math.random(0, 255)/255, math.random(0, 255)/255)
end

-- Função para aplicar uma cor suavemente
local function lerpColor(startColor, endColor, alpha)
    return startColor:Lerp(endColor, alpha)
end

-- Tempo de transição (em segundos)
local transitionTime = 0.33

-- Remover camisa e calça do jogador
character.Shirt:Destroy()
character.Pants:Destroy()

-- Loop infinito para alterar as cores do corpo
while true do
    local startTime = tick()
    local endTime = startTime + transitionTime
    
    local startColor = randomColor()
    local endColor = randomColor()
    
    while tick() < endTime do
        local elapsedTime = tick() - startTime
        local alpha = elapsedTime / transitionTime
        
        for _, part in ipairs(character:GetDescendants()) do
            if part:IsA("BasePart") then
                part.Color = lerpColor(startColor, endColor, alpha)
                part.Transparency = 0.5
                part.Material = Enum.Material.ForceField -- Aqui está a linha que adiciona o material ForceField
            end
        end
        
        wait()
    end
end
end)

HDVBFD:CreateButton("Esp (Beta)", function()
    game.StarterGui:SetCore("SendNotification", {
Title = "Esp Active",
Text = "(Client)",
Duration = 2.3,
})
wait(0.1)
 -- Função para adicionar ESP (Nomes acima da cabeça) com destaque para inimigos
local function addEnemyESP(enemy)
    local BillboardGui = Instance.new("BillboardGui")
    BillboardGui.Name = "EnemyESP"
    BillboardGui.Size = UDim2.new(0, 100, 0, 40)
    BillboardGui.Adornee = enemy
    BillboardGui.AlwaysOnTop = true
    BillboardGui.StudsOffset = Vector3.new(0, 3, 0)
    BillboardGui.Parent = enemy
    
    local TextLabel = Instance.new("TextLabel")
    TextLabel.BackgroundTransparency = 1
    TextLabel.Size = UDim2.new(1, 0, 1, 0)
    TextLabel.TextColor3 = Color3.new(1, 0, 0) -- Cor do nome
    TextLabel.TextStrokeTransparency = 0.5
    TextLabel.TextStrokeColor3 = Color3.new(0, 0, 0) -- Cor do contorno
    TextLabel.TextScaled = true
    TextLabel.Font = Enum.Font.SourceSansBold
    TextLabel.Text = "Zombie" -- Texto exibido (pode ser o nome do inimigo)
    TextLabel.Parent = BillboardGui
    
    -- Adiciona um destaque ao redor do nome
    local Highlight = Instance.new("ImageLabel")
    Highlight.Name = "Highlight"
    Highlight.BackgroundTransparency = 1
    Highlight.Size = UDim2.new(1, 6, 1, 6)
    Highlight.Position = UDim2.new(-0.5, -3, -0.5, -3)
    Highlight.Image = "rbxassetid://4748513315" -- Imagem de destaque (pode ser um arquivo local)
    Highlight.ImageColor3 = Color3.new(1, 1, 1) -- Cor do destaque (branco)
    Highlight.Parent = BillboardGui
end

-- Função para adicionar ESP a todos os inimigos existentes
local function addAllEnemyESP()
    local enemies = workspace.enemies:GetChildren()
    for _, enemy in ipairs(enemies) do
        addEnemyESP(enemy)
    end
end

-- Adicionar ESP aos inimigos existentes
addAllEnemyESP()

-- Evento para adicionar ESP aos inimigos recém-criados
workspace.enemies.ChildAdded:Connect(function(enemy)
    addEnemyESP(enemy)
end)

-- Função para adicionar ESP com destaque para chefes
local function addBossESP(boss)
    local BillboardGui = Instance.new("BillboardGui")
    BillboardGui.Name = "BossESP"
    BillboardGui.Size = UDim2.new(0, 100, 0, 40)
    BillboardGui.Adornee = boss
    BillboardGui.AlwaysOnTop = true
    BillboardGui.StudsOffset = Vector3.new(0, 3, 0)
    BillboardGui.Parent = boss
    
    local TextLabel = Instance.new("TextLabel")
    TextLabel.BackgroundTransparency = 1
    TextLabel.Size = UDim2.new(1, 0, 1, 0)
    TextLabel.TextColor3 = Color3.new(0, 1, 0) -- Cor do nome
    TextLabel.TextStrokeTransparency = 0.5
    TextLabel.TextStrokeColor3 = Color3.new(0, 0, 0) -- Cor do contorno
    TextLabel.TextScaled = true
    TextLabel.Font = Enum.Font.SourceSansBold
    TextLabel.Text = "Boss" -- Texto exibido (pode ser o nome do chefe)
    TextLabel.Parent = BillboardGui
    
    -- Adiciona um destaque ao redor do nome
    local Highlight = Instance.new("ImageLabel")
    Highlight.Name = "Highlight"
    Highlight.BackgroundTransparency = 1
    Highlight.Size = UDim2.new(1, 6, 1, 6)
    Highlight.Position = UDim2.new(-0.5, -3, -0.5, -3)
    Highlight.Image = "rbxassetid://4748513315" -- Imagem de destaque (pode ser um arquivo local)
    Highlight.ImageColor3 = Color3.new(1, 1, 1) -- Cor do destaque (branco)
    Highlight.Parent = BillboardGui
end

-- Função para adicionar ESP com destaque para todos os chefes existentes
local function addAllBossESP()
    local bosses = game.Workspace.BossFolder:GetChildren()
    for _, boss in ipairs(bosses) do
        addBossESP(boss)
    end
end

-- Adicionar ESP com destaque para os chefes existentes
addAllBossESP()

-- Evento para adicionar ESP com destaque para os chefes recém-criados
game.Workspace.BossFolder.ChildAdded:Connect(function(boss)
    addBossESP(boss)
end)

end)

HDVBFD:CreateButton("Credits (Click)", function()
game.StarterGui:SetCore("SendNotification", {
Title = "Made By 2xyyy Discord or https://discord.gg/daXpGWF2SV",
Text = "Want help scripting? if you have any function like auto buy guns or others call me on discord - Suport: Solara, Mobile, Krampus",
Duration = 5,
})
end)

HDVBFD:CreateButton("Credits (Click-loop)", function()
  while true do
game.StarterGui:SetCore("SendNotification", {
Title = "Made By 2xyyy Discord",
Text = "Want help scripting? if you have any function like auto buy guns or others call me on discord - Suport: Solara, Mobile, Krampus",
Duration = 5,
})
wait(5) end
end)

HDVBFD:CreateButton("Version Script", function()
game.StarterGui:SetCore("SendNotification", {
Title = "Script Status: Online",
--Text = "Last Update 24/05/2024 - (brazil) - script Version: 0.2.9 - antiban = Dont talk on chat and no ban :D",
--Text = "Script Remake: Config Script, Powerups, Ect...",
Duration = 5,
Text = "Last Update 24/05/2024 Script - (brazil) - script Version: 0.2.9 Remake: Config Script, Powerups, Ect...",
})
end)

MainSection:CreateToggle("Auto-Farm", function(value)
   _G.farm2 = value
end)
MainSection:CreateToggle("Auto-GetPowersups (V1)", function(value)
_G.AutoGetPowerups = value
end)

MainSection:CreateButton("Auto-GetPowersups (V2)", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "GetPowersups-Auto",
Text = "Active",
Duration = 5,
})
  spawn(function()
  while true do
powerups = game.workspace.Powerups
print(powerups)
for i,v in pairs(powerups:GetChildren()) do 
print(v.Part.TouchInterest)
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart,v.Part,0)
end
task.wait()
  end
  
  end)
end)

--[[MainSection:CreateButton("Auto-Equip (V2)", function()
  while true do
 local player = game.Players.LocalPlayer
    local backpack = player.Backpack

    for _,item in pairs(backpack:GetChildren()) do
        if item:IsA("Tool") then
            item.Parent = player.Character
        end
    end
    wait(1) end
end)]]

MainSection:CreateToggle("Auto-Equip (V1)", function(value)
   _G.autoequip = value
end)

MainSection:CreateSlider("Walkspeed", 0, 500, 16, false, function(value)
 -- game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = value
 game:GetService('Players').LocalPlayer.Character.Humanoid.WalkSpeed = value
end)

MainSection:CreateSlider("Jumppower", 0, 500, 50, false, function(value)
game:GetService('Players').LocalPlayer.Character.Humanoid.JumpPower = value
end)

ConfigSection:CreateLabel("Farm-Warn", "-------------------")
ConfigSection:CreateLabel("Farm-Warn", "Not Recomend Change")
ConfigSection:CreateLabel("Farm-Warn", "(Search-Zombie Dist)")

ConfigSection:CreateButton("AntiAfk", function()
wait(0.5)local ba=Instance.new("ScreenGui")
local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,0,0,0)
ca.Font=Enum.Font.SourceSansSemibold;ca.Text=""ca.TextColor3=Color3.new(0,1,1)
ca.TextSize=22;da.Parent=ca
da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
da.Size=UDim2.new(0,0,0,0)_b.Parent=da
_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
_b.Size=UDim2.new(0,0,0,0)_b.Font=Enum.Font.Arial;_b.Text=""
_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
ab.Size=UDim2.new(0,0,0,0)ab.Font=Enum.Font.ArialBold;ab.Text="Anti-AFK status: Active"
ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
game:service'Players'.LocalPlayer.Idled:connect(function()
bb:CaptureController()bb:ClickButton2(Vector2.new())
ab.Text=""wait(2)ab.Text=""end)
wait(0.1)
game.StarterGui:SetCore("SendNotification", {
Title = "Active",
Text = "Anti-Afk",
Duration = 5,
})
end)

ConfigSection:CreateSlider("Ground Distance +", 0, 150, 0, false, function(value)
   _G.groundDistance = value
end)

ConfigSection:CreateSlider("Ground Distance -", -150, 0, 0, false, function(value)
   _G.groundDistance = value
end)

ConfigSection:CreateSlider("Search-Zombie Dist", 0, 250000, 100000, false, function(value)
   _G.dist = value
end)

CombatCg:CreateSlider("Hitbox", 3, 50, 3, false, function(value)
    _G.HeadSize = value
end)

CombatCg:CreateButton("Give All Guns (Beta)", function()
  	for _,Thing in pairs(game.ReplicatedStorage.Guns:GetChildren()) do
if Thing:IsA("Tool") then
Thing.Parent = game.Players.LocalPlayer.Backpack
end
end
wait(0.1)
game.StarterGui:SetCore("SendNotification", {
Title = "player Give:",
Text = "Guns (Client)",
Duration = 2.3,
})
end)

CombatCg:CreateButton("Give All Knife (Beta)", function()
	for _,Thing in pairs(game.ReplicatedStorage.Knives:GetChildren()) do
if Thing:IsA("Tool") then
Thing.Parent = game.Players.LocalPlayer.Backpack
end
end
wait(0.1)
game.StarterGui:SetCore("SendNotification", {
Title = "player Give:",
Text = "Knife (Client)",
Duration = 2.3,
})
end)

Crates:CreateButton("Auto-Open #1 - 1", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Open",
Text = "Basic #1",
Duration = 5,
})
wait(0.5)
while true do
local args = {
    [1] = "unbox_box",
    [2] = "Basic #1"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
wait(0.1) end
end)

Crates:CreateButton("Auto-Open #2 - 1", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Open",
Text = "Basic #2",
Duration = 5,
})
wait(0.5)
while true do
local args = {
    [1] = "unbox_box",
    [2] = "Basic #2"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
wait(0.1) end
end)

Crates:CreateButton("Auto-Open #3 - 1", function()
game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Open",
Text = "Basic #3",
Duration = 5,
})
wait(0.5)
while true do
local args = {
    [1] = "unbox_box",
    [2] = "Basic #3"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
wait(0.1) end
end)

Crates:CreateButton("Auto-Open #4 - 3", function()
    game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Open",
Text = "Uncommon - 3 Keys",
Duration = 5,
})
wait(0.5)
while true do
local args = {
    [1] = "unbox_box",
    [2] = "Uncommon"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
wait(0.1) end
end)

Crates:CreateButton("Auto-Open #5 - 10", function()
    game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Open",
Text = "Rare - 10 Keys",
Duration = 5,
})
wait(0.5)
while true do
local args = {
    [1] = "unbox_box",
    [2] = "Rare"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
wait(0.1) end
end)

Crates:CreateButton("Auto-Open #6 - 30", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Open",
Text = "Legendary - 30 Keys",
Duration = 5,
})
wait(0.5)
while true do
local args = {
    [1] = "unbox_box",
    [2] = "Legendary"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
wait(0.1) end
end)
--
Crates:CreateButton("Open #1 - 1", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "",
Text = "Basic #1 - 1 Keys",
Duration = 5,
})
wait(0.1)
local args = {
    [1] = "unbox_box",
    [2] = "Basic #1"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
end)

Crates:CreateButton("Open #2 - 1", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "",
Text = "Basic #2 - 1 Keys",
Duration = 5,
})
wait(0.1)
local args = {
    [1] = "unbox_box",
    [2] = "Basic #2"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
end)

Crates:CreateButton("Open #3 - 1", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "",
Text = "Basic #3 - 1 Keys",
Duration = 5,
})
wait(0.1)
local args = {
    [1] = "unbox_box",
    [2] = "Basic #3"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
end)

Crates:CreateButton("Open #4 - 3", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "",
Text = "Uncommon - 3 Keys",
Duration = 5,
})
wait(0.1)
local args = {
    [1] = "unbox_box",
    [2] = "Uncommon"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
end)

Crates:CreateButton("Open #5 - 10", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "",
Text = "Rare - 10 Keys",
Duration = 5,
})
wait(0.1)
local args = {
    [1] = "unbox_box",
    [2] = "Rare"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
end)

Crates:CreateButton("Open #6 - 30", function()
  game.StarterGui:SetCore("SendNotification", {
Title = "",
Text = "Legendary - 30 Keys",
Duration = 5,
})
wait(0.1)
local args = {
    [1] = "unbox_box",
    [2] = "Legendary"
}

game:GetService("ReplicatedStorage").RemoteEventContainer.CommunicationF:InvokeServer(unpack(args))
end)

    while wait() do
       local bosses = game.Workspace.BossFolder:GetChildren()
    for _, v in ipairs(bosses) do
        if game.Workspace.enemies:FindFirstChild("Zombie") then
            for i,v in pairs(game.Workspace.enemies:GetChildren()) do
                wait()
                if v:FindFirstChild("Head") then
                    v.Head.CanCollide = false
                    v.Head.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
                    v.Head.CFrame = v.Torso.CFrame * CFrame.new(0,_G.HeadSize/2,0)
                end
            end
        end
    end

local function modifyHitbox()
    -- Ajustando o hitbox dos inimigos
    local enemies = workspace.enemies:GetChildren()
    for _, v in ipairs(enemies) do
        if v:IsA("Model") and v:FindFirstChild("HumanoidRootPart") then
            v.HumanoidRootPart.Size = Vector3.new(_G.HeadSize, _G.HeadSize, _G.HeadSize)
            v.HumanoidRootPart.Material = "Neon"
            v.HumanoidRootPart.BrickColor = BrickColor.new("Really blue")
            v.HumanoidRootPart.Transparency = 0.92
            v.HumanoidRootPart.CanCollide = false
        end
    end
    
    -- Ajustando o hitbox dos chefes (bosses)
    local bosses = game.Workspace.BossFolder:GetChildren()
    for _, v in ipairs(bosses) do
        if v:IsA("Model") and v:FindFirstChild("HumanoidRootPart") then
            v.HumanoidRootPart.Size = Vector3.new(_G.HeadSize, _G.HeadSize, _G.HeadSize)
            v.HumanoidRootPart.Material = "Neon"
            v.HumanoidRootPart.BrickColor = BrickColor.new("Really blue")
            v.HumanoidRootPart.Transparency = 0.92
            v.HumanoidRootPart.CanCollide = false
        end
    end
end

spawn(function()
    while true do
        modifyHitbox()
        wait(0.1)
    end
end)

local function autoequip()
    local player = game.Players.LocalPlayer
    local backpack = player.Backpack

    for _,item in pairs(backpack:GetChildren()) do
        if item:IsA("Tool") then
            item.Parent = player.Character
        end
    end
end

local function autogetpowerupscript()
powerups = game.workspace.Powerups
print(powerups)
for i,v in pairs(powerups:GetChildren()) do 
print(v.Part.TouchInterest)
firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart,v.Part,0)
    end
end

spawn(function()
    while true do
        if _G.AutoGetPowerups then
            autogetpowerupscript()
        end
        wait(0.1)
    end
end)

--[[spawn(function()
   -- while true do
        if _G.autogetpowerups ~= true then
       --   while value do
            autogetpowerupscript()
      --      end
        end
        wait(0.1)
  --  end
end)]]

--[[spawn(function()
  while false ~= value do
    if _G.autogetpowerups ~= true then
    end
    wait(0.1)
  end
  end)]]

spawn(function()
    while true do
        if _G.autoequip then
            autoequip()
        end
        wait(0.1)
    end
end)

local Player = game:GetService("Players").LocalPlayer

local function getNearest()
    local nearest, dist = nil, _G.dist
    for _,v in pairs(game.Workspace.BossFolder:GetChildren()) do
        if v:FindFirstChild("Head") then
            local m = (Player.Character.Head.Position - v.Head.Position).magnitude
            if m < dist then
                dist = m
                nearest = v
            end
        end
    end
    for _,v in pairs(game.Workspace.enemies:GetChildren()) do
        if v:FindFirstChild("Head") then
            local m = (Player.Character.Head.Position - v.Head.Position).magnitude
            if m < dist then
                dist = m
                nearest = v
            end
        end
    end
    return nearest
end

Player.Chatted:Connect(function(m)
    local message = m:lower()
    if message == ";unfarm" or message == ";unFarm" or message == ";uf" then
        _G.farm2 = false
              game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Farm",
Text = "false.",
Duration = 2.3,
})
    elseif message == ";farm" or message == ";Farm" or message == ";f" then
        _G.farm2 = true
                game.StarterGui:SetCore("SendNotification", {
Title = "Auto-Farm",
Text = "true.",
Duration = 2.3,
})
    elseif message == ";powerup" or message == ";Powerup" or message == ";Powerups" or message == ";powerups" or message == ";pw" or message == ";up" then
        _G.AutoGetPowerups = true
                game.StarterGui:SetCore("SendNotification", {
Title = "powerups",
Text = "true.",
Duration = 2.3,
})
    elseif message == ";unpowerup" or message == ";unPowerup" or message == ";unPowerups" or message == ";unpowerups" or message == ";unpw" or message == ";unup" then
        _G.AutoGetPowerups = false
        game.StarterGui:SetCore("SendNotification", {
Title = "powerups",
Text = "false.",
Duration = 2.3,
})
    elseif message == ";autoequip" or message == ";Autoequip" or message == ";at" or message == ";At" or message == ";Equip" or message == "equip" then
        _G.autoequip = true
        game.StarterGui:SetCore("SendNotification", {
Title = "autoequip",
Text = "true.",
Duration = 2.3,
})
    elseif message == ";unautoequip" or message == ";unAutoequip" or message == ";unat" or message == ";unAt" or message == ";unEquip" or message == "unequip" then
        _G.autoequip = false
        game.StarterGui:SetCore("SendNotification", {
Title = "autoequip",
Text = "false.",
Duration = 2.3,
})
    elseif message:sub(1, 5) == ";ds+ " then
        local value = tonumber(message:sub(6))
        if value and value >= 1 and value <= 150 then
            _G.groundDistance = value
        end
    elseif message:sub(1, 5) == ";ds- " then
        local value = tonumber(message:sub(6))
        if value and value >= 1 and value <= 150 then
            _G.groundDistance = -value
        elseif message:sub(1, 5) == ";dt " then
        local value = tonumber(message:sub(6))
        if value and value >= 1 and value <= 100000 then
          _G.dist = value
           elseif message:sub(1, 5) == ";head " or "Head " or ";headsize " or ";Headsize " or "HeadSize " or ";H " or ";HS " or ";h " or ";H " or "Hitbox " or "hitbox " then
        local value = tonumber(message:sub(6))
        if value and value >= 3 and value <= 50 then
          _G.HeadSize = value
         end
        end
     end
  end
end)



_G.globalTarget = nil
game:GetService("RunService").RenderStepped:Connect(function()
    if _G.farm2 == true then
        local target = getNearest()
        if target and target:FindFirstChild("Head") then
            game:GetService("Workspace").CurrentCamera.CFrame = CFrame.new(game:GetService("Workspace").CurrentCamera.CFrame.p, target.Head.Position)
            Player.Character.HumanoidRootPart.CFrame =
            (target.HumanoidRootPart.CFrame * CFrame.new(0, _G.groundDistance, 9))
            _G.globalTarget = target
        end
    end
end)

spawn(function() -- Player Velocity
    while wait() do
        game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(0,0,0)
        game.Players.LocalPlayer.Character.Torso.Velocity = Vector3.new(0,0,0)
    end
end)

while wait() do -- _G. == true and _G. ~= nil (zombie) FindFirstChild Head (Zombie)
    if _G.farm2 == true and _G.globalTarget ~= nil and _G.globalTarget:FindFirstChild("Head") and Player.Character:FindFirstChildOfClass("Tool") then -- Script
        local target = _G.globalTarget -- _G.
        game.ReplicatedStorage.Gun:FireServer({ -- Event
            ["Normal"] = Vector3.new(0, 0, 0), -- Vector3
            ["Direction"] = target.Head.Position, -- Position
            ["Name"] = Player.Character:FindFirstChildOfClass("Tool").Name, -- Tool Player
            ["Hit"] = target.Head, -- HeadShot
            ["Origin"] = target.Head.Position, -- Position Head
            ["Pos"] = target.Head.Position, -- Position Head
        }) -- close
        wait() -- wait
    end
end
end
