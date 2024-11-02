-- Monstrum's Gui to Lua\n-- Version: 3.2

-- Instances:

local Reversal = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local functions = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIStroke = Instance.new("UIStroke")
local functionsBar = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local UIStroke_2 = Instance.new("UIStroke")
local AutoFarmButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UIStroke_3 = Instance.new("UIStroke")
local Reversal_2 = Instance.new("TextLabel")
local UIStroke_4 = Instance.new("UIStroke")
local UICorner_4 = Instance.new("UICorner")
local QuestsFrame = Instance.new("Frame")
local QuestsText = Instance.new("TextLabel")
local UIStroke_5 = Instance.new("UIStroke")
local UICorner_5 = Instance.new("UICorner")
local Quests = Instance.new("Frame")
local UIStroke_6 = Instance.new("UIStroke")
local UICorner_6 = Instance.new("UICorner")
local Cloud = Instance.new("TextButton")
local Target = Instance.new("TextButton")
local Soccer = Instance.new("TextButton")
local Ramp = Instance.new("TextButton")
local FindMe = Instance.new("TextButton")
local Dragon = Instance.new("TextButton")
local DragonText = Instance.new("TextLabel")
local SoccerText = Instance.new("TextLabel")
local TheBox = Instance.new("TextButton")
local ThinIce = Instance.new("TextButton")
local QuestsDeco = Instance.new("Frame")
local UICorner_7 = Instance.new("UICorner")
local UIStroke_7 = Instance.new("UIStroke")
local TeleportButton = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local UIStroke_8 = Instance.new("UIStroke")
local AutoFarmFrame = Instance.new("Frame")
local AutoFarm = Instance.new("TextLabel")
local UIStroke_9 = Instance.new("UIStroke")
local UICorner_9 = Instance.new("UICorner")
local AutoFarmV1 = Instance.new("Frame")
local UICorner_10 = Instance.new("UICorner")
local UIStroke_10 = Instance.new("UIStroke")
local AutoFarmV1Text = Instance.new("TextLabel")
local AutoFarmButtonOffOnV1 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local UIStroke_11 = Instance.new("UIStroke")
local settings = Instance.new("Frame")
local AutoFarmV1TextResetVelocity = Instance.new("TextLabel")
local AutoFarmV1TextCollectchest = Instance.new("TextLabel")
local AutoFarmButtonSettingsResetVelocityOffOn = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local UIStroke_12 = Instance.new("UIStroke")
local AutoFarmButtonSettingsCollectchestOffOn = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local UIStroke_13 = Instance.new("UIStroke")
local UICorner_14 = Instance.new("UICorner")
local UIStroke_14 = Instance.new("UIStroke")
local AutoFarmV1TextGetGold = Instance.new("TextLabel")
local AutoFarmButtonSettingsGetGoldOffOn = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local UIStroke_15 = Instance.new("UIStroke")
local AutoFarmCandyV1 = Instance.new("Frame")
local UICorner_16 = Instance.new("UICorner")
local UIStroke_16 = Instance.new("UIStroke")
local AutoFarmCandyV1_2 = Instance.new("TextLabel")
local AutoFarmCandyButtonOffOn = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local UIStroke_17 = Instance.new("UIStroke")
local AutoFarmV2 = Instance.new("Frame")
local UICorner_18 = Instance.new("UICorner")
local UIStroke_18 = Instance.new("UIStroke")
local AutoFarmV2Text = Instance.new("TextLabel")
local AutoFarmButtonOffOnV2 = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local UIStroke_19 = Instance.new("UIStroke")
local settings_2 = Instance.new("Frame")
local AutoFarmV2TextCollectchest = Instance.new("TextLabel")
local AutoFarmButtonSettingsCollectchestOffOn_2 = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local UIStroke_20 = Instance.new("UIStroke")
local UICorner_21 = Instance.new("UICorner")
local UIStroke_21 = Instance.new("UIStroke")
local AutoFarmV2TextGetGold = Instance.new("TextLabel")
local AutoFarmButtonSettingsGetGoldOffOn_2 = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local UIStroke_22 = Instance.new("UIStroke")
local QuestsButton = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local UIStroke_23 = Instance.new("UIStroke")
local TelleportsFrame = Instance.new("Frame")
local Telleports = Instance.new("TextLabel")
local UIStroke_24 = Instance.new("UIStroke")
local UICorner_24 = Instance.new("UICorner")
local StagesV1 = Instance.new("Frame")
local UIStroke_25 = Instance.new("UIStroke")
local UICorner_25 = Instance.new("UICorner")
local Stage5 = Instance.new("TextButton")
local Stage2 = Instance.new("TextButton")
local Stage3 = Instance.new("TextButton")
local Stage7 = Instance.new("TextButton")
local Stage4 = Instance.new("TextButton")
local Stage1 = Instance.new("TextButton")
local Stage6 = Instance.new("TextButton")
local Stage8 = Instance.new("TextButton")
local Stage9 = Instance.new("TextButton")
local endstage = Instance.new("TextButton")
local Stage10 = Instance.new("TextButton")
local TeamsV1Deco = Instance.new("Frame")
local UICorner_26 = Instance.new("UICorner")
local UIStroke_26 = Instance.new("UIStroke")
local TeamsText = Instance.new("TextLabel")
local UICorner_27 = Instance.new("UICorner")
local UIStroke_27 = Instance.new("UIStroke")
local TeamsV1 = Instance.new("Frame")
local UIStroke_28 = Instance.new("UIStroke")
local UICorner_28 = Instance.new("UICorner")
local White = Instance.new("TextButton")
local Blue = Instance.new("TextButton")
local Green = Instance.new("TextButton")
local Red = Instance.new("TextButton")
local Black = Instance.new("TextButton")
local Yellow = Instance.new("TextButton")
local Magenta = Instance.new("TextButton")
local StagesText = Instance.new("TextLabel")
local UICorner_29 = Instance.new("UICorner")
local UIStroke_29 = Instance.new("UIStroke")
local StagesV1Deco = Instance.new("Frame")
local UICorner_30 = Instance.new("UICorner")
local UIStroke_30 = Instance.new("UIStroke")
local AutoBuyButton = Instance.new("TextButton")
local UICorner_31 = Instance.new("UICorner")
local UIStroke_31 = Instance.new("UIStroke")
local AutoBuyFrame = Instance.new("Frame")
local AutoBuy = Instance.new("TextLabel")
local UIStroke_32 = Instance.new("UIStroke")
local UICorner_32 = Instance.new("UICorner")
local ChestsV1Deco = Instance.new("Frame")
local UICorner_33 = Instance.new("UICorner")
local UIStroke_33 = Instance.new("UIStroke")
local ChestsText = Instance.new("TextLabel")
local UICorner_34 = Instance.new("UICorner")
local UIStroke_34 = Instance.new("UIStroke")
local ChestsV1 = Instance.new("Frame")
local UIStroke_35 = Instance.new("UIStroke")
local UICorner_35 = Instance.new("UICorner")
local Cammon = Instance.new("TextButton")
local Uncammon = Instance.new("TextButton")
local Rare = Instance.new("TextButton")
local Epic = Instance.new("TextButton")
local Legendary = Instance.new("TextButton")
local OpenMainFrame = Instance.new("TextButton")
local UICorner_36 = Instance.new("UICorner")
local UIStroke_36 = Instance.new("UIStroke")

--Properties:

Reversal.Name = "Reversal"
Reversal.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Reversal.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Reversal.DisplayOrder = 999999999
Reversal.ResetOnSpawn = false

MainFrame.Name = "MainFrame"
MainFrame.Parent = Reversal
MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainFrame.BackgroundTransparency = 1.000
MainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BorderSizePixel = 0
MainFrame.Size = UDim2.new(0, 1132, 0, 578)
MainFrame.Visible = false
MainFrame.ZIndex = 0

functions.Name = "functions"
functions.Parent = MainFrame
functions.AnchorPoint = Vector2.new(0.5, 0.5)
functions.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
functions.BorderColor3 = Color3.fromRGB(0, 0, 0)
functions.BorderSizePixel = 0
functions.Position = UDim2.new(0.577160478, 0, 0.5, 0)
functions.Size = UDim2.new(0.491181672, 0, 0.647668421, 0)

UICorner.Parent = functions

UIStroke.Parent = functions
UIStroke.Thickness = 3.000

functionsBar.Name = "functionsBar"
functionsBar.Parent = MainFrame
functionsBar.AnchorPoint = Vector2.new(0.5, 0.5)
functionsBar.BackgroundColor3 = Color3.fromRGB(117, 117, 117)
functionsBar.BorderColor3 = Color3.fromRGB(0, 0, 0)
functionsBar.BorderSizePixel = 0
functionsBar.Position = UDim2.new(0.259259254, 0, 0.5, 0)
functionsBar.Size = UDim2.new(0.164021164, 0, 0.647668421, 0)
functionsBar.ZIndex = 2

UICorner_2.Parent = functionsBar

UIStroke_2.Parent = functionsBar
UIStroke_2.Thickness = 3.000

AutoFarmButton.Name = "AutoFarmButton"
AutoFarmButton.Parent = MainFrame
AutoFarmButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoFarmButton.BackgroundTransparency = 1.000
AutoFarmButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButton.BorderSizePixel = 0
AutoFarmButton.Position = UDim2.new(0.189999998, 0, 0.266000003, 0)
AutoFarmButton.Size = UDim2.new(0.13844797, 0, 0.0397236608, 0)
AutoFarmButton.ZIndex = 3
AutoFarmButton.Font = Enum.Font.FredokaOne
AutoFarmButton.Text = "AutoFarms"
AutoFarmButton.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButton.TextScaled = true
AutoFarmButton.TextSize = 14.000
AutoFarmButton.TextWrapped = true

UICorner_3.Parent = AutoFarmButton

UIStroke_3.Parent = AutoFarmButton
UIStroke_3.Thickness = 3.000
UIStroke_3.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

Reversal_2.Name = "Reversal"
Reversal_2.Parent = MainFrame
Reversal_2.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
Reversal_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Reversal_2.BorderSizePixel = 0
Reversal_2.Position = UDim2.new(0.177248672, 0, 0.176165804, 0)
Reversal_2.Size = UDim2.new(0.164021164, 0, 0.07772021, 0)
Reversal_2.ZIndex = 3
Reversal_2.Font = Enum.Font.FredokaOne
Reversal_2.Text = "Reversal"
Reversal_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Reversal_2.TextScaled = true
Reversal_2.TextSize = 14.000
Reversal_2.TextWrapped = true

UIStroke_4.Parent = Reversal_2
UIStroke_4.Thickness = 3.000
UIStroke_4.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_4.Parent = Reversal_2

QuestsFrame.Name = "QuestsFrame"
QuestsFrame.Parent = MainFrame
QuestsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
QuestsFrame.BackgroundTransparency = 1.000
QuestsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
QuestsFrame.BorderSizePixel = 0
QuestsFrame.Position = UDim2.new(0.0890652537, 0, 0.265975833, 0)
QuestsFrame.Size = UDim2.new(0.0881834179, 0, 0.0397236608, 0)
QuestsFrame.Visible = false

QuestsText.Name = "QuestsText"
QuestsText.Parent = QuestsFrame
QuestsText.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
QuestsText.BackgroundTransparency = 1.000
QuestsText.BorderColor3 = Color3.fromRGB(0, 0, 0)
QuestsText.BorderSizePixel = 0
QuestsText.Position = UDim2.new(3.62917113, 0, -1.852, 0)
QuestsText.Size = UDim2.new(3.81000018, 0, 1.13043475, 0)
QuestsText.ZIndex = 3
QuestsText.Font = Enum.Font.FredokaOne
QuestsText.Text = "Quests"
QuestsText.TextColor3 = Color3.fromRGB(0, 0, 0)
QuestsText.TextScaled = true
QuestsText.TextSize = 14.000
QuestsText.TextWrapped = true

UIStroke_5.Parent = QuestsText
UIStroke_5.Thickness = 3.000
UIStroke_5.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_5.Parent = QuestsText

Quests.Name = "Quests"
Quests.Parent = QuestsFrame
Quests.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
Quests.BorderColor3 = Color3.fromRGB(0, 0, 0)
Quests.BorderSizePixel = 0
Quests.Position = UDim2.new(2.95000052, 0, -0.323000014, 0)
Quests.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
Quests.ZIndex = 2

UIStroke_6.Parent = Quests
UIStroke_6.Thickness = 3.000
UIStroke_6.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_6.Parent = Quests

Cloud.Name = "Cloud"
Cloud.Parent = Quests
Cloud.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Cloud.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cloud.BorderSizePixel = 0
Cloud.Position = UDim2.new(-0.00106391299, 0, -1.52851874e-06, 0)
Cloud.Size = UDim2.new(0, 66, 0, 30)
Cloud.ZIndex = -1
Cloud.Font = Enum.Font.FredokaOne
Cloud.Text = "Cloud"
Cloud.TextColor3 = Color3.fromRGB(0, 0, 0)
Cloud.TextScaled = true
Cloud.TextSize = 14.000
Cloud.TextWrapped = true

Target.Name = "Target"
Target.Parent = Quests
Target.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Target.BorderColor3 = Color3.fromRGB(0, 0, 0)
Target.BorderSizePixel = 0
Target.Position = UDim2.new(0.124159873, 0, -1.52851874e-06, 0)
Target.Size = UDim2.new(0, 66, 0, 30)
Target.ZIndex = -1
Target.Font = Enum.Font.FredokaOne
Target.Text = "Target"
Target.TextColor3 = Color3.fromRGB(0, 0, 0)
Target.TextScaled = true
Target.TextSize = 14.000
Target.TextWrapped = true

Soccer.Name = "Soccer"
Soccer.Parent = Quests
Soccer.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Soccer.BorderColor3 = Color3.fromRGB(0, 0, 0)
Soccer.BorderSizePixel = 0
Soccer.Position = UDim2.new(0.249383658, 0, -1.52851874e-06, 0)
Soccer.Size = UDim2.new(0, 66, 0, 30)
Soccer.ZIndex = -1
Soccer.Font = Enum.Font.FredokaOne
Soccer.Text = "Soccer"
Soccer.TextColor3 = Color3.fromRGB(0, 0, 0)
Soccer.TextScaled = true
Soccer.TextSize = 14.000
Soccer.TextWrapped = true

Ramp.Name = "Ramp"
Ramp.Parent = Quests
Ramp.BackgroundColor3 = Color3.fromRGB(255, 223, 107)
Ramp.BorderColor3 = Color3.fromRGB(0, 0, 0)
Ramp.BorderSizePixel = 0
Ramp.Position = UDim2.new(0.374607444, 0, -1.52851874e-06, 0)
Ramp.Size = UDim2.new(0, 66, 0, 30)
Ramp.ZIndex = -1
Ramp.Font = Enum.Font.FredokaOne
Ramp.Text = "Ramp"
Ramp.TextColor3 = Color3.fromRGB(0, 0, 0)
Ramp.TextScaled = true
Ramp.TextSize = 14.000
Ramp.TextWrapped = true

FindMe.Name = "FindMe"
FindMe.Parent = Quests
FindMe.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
FindMe.BorderColor3 = Color3.fromRGB(0, 0, 0)
FindMe.BorderSizePixel = 0
FindMe.Position = UDim2.new(0.499831229, 0, -1.52851874e-06, 0)
FindMe.Size = UDim2.new(0, 66, 0, 30)
FindMe.ZIndex = -1
FindMe.Font = Enum.Font.FredokaOne
FindMe.Text = "Find me"
FindMe.TextColor3 = Color3.fromRGB(0, 0, 0)
FindMe.TextScaled = true
FindMe.TextSize = 14.000
FindMe.TextWrapped = true

Dragon.Name = "Dragon"
Dragon.Parent = Quests
Dragon.BackgroundColor3 = Color3.fromRGB(95, 95, 95)
Dragon.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dragon.BorderSizePixel = 0
Dragon.Position = UDim2.new(0.625055015, 0, -1.52851874e-06, 0)
Dragon.Size = UDim2.new(0, 66, 0, 30)
Dragon.ZIndex = -1
Dragon.Font = Enum.Font.FredokaOne
Dragon.Text = "Dragon"
Dragon.TextColor3 = Color3.fromRGB(0, 0, 0)
Dragon.TextScaled = true
Dragon.TextSize = 14.000
Dragon.TextWrapped = true

DragonText.Name = "DragonText"
DragonText.Parent = Quests
DragonText.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
DragonText.BackgroundTransparency = 1.000
DragonText.BorderColor3 = Color3.fromRGB(0, 0, 0)
DragonText.BorderSizePixel = 0
DragonText.Position = UDim2.new(0.624570906, 0, 0.693096101, 0)
DragonText.Size = UDim2.new(0.125707865, 0, 0.232237533, 0)
DragonText.Font = Enum.Font.FredokaOne
DragonText.Text = "Sword require"
DragonText.TextColor3 = Color3.fromRGB(0, 0, 0)
DragonText.TextScaled = true
DragonText.TextSize = 14.000
DragonText.TextWrapped = true

SoccerText.Name = "SoccerText"
SoccerText.Parent = Quests
SoccerText.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
SoccerText.BackgroundTransparency = 1.000
SoccerText.BorderColor3 = Color3.fromRGB(0, 0, 0)
SoccerText.BorderSizePixel = 0
SoccerText.Position = UDim2.new(0.248899579, 0, 0.693096101, 0)
SoccerText.Size = UDim2.new(0.125707865, 0, 0.232237533, 0)
SoccerText.Font = Enum.Font.FredokaOne
SoccerText.Text = "not work"
SoccerText.TextColor3 = Color3.fromRGB(0, 0, 0)
SoccerText.TextScaled = true
SoccerText.TextSize = 14.000
SoccerText.TextWrapped = true

TheBox.Name = "TheBox"
TheBox.Parent = Quests
TheBox.BackgroundColor3 = Color3.fromRGB(0, 170, 255)
TheBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TheBox.BorderSizePixel = 0
TheBox.Position = UDim2.new(0.750278771, 0, -1.52851874e-06, 0)
TheBox.Size = UDim2.new(0, 66, 0, 30)
TheBox.ZIndex = -1
TheBox.Font = Enum.Font.FredokaOne
TheBox.Text = "The box"
TheBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TheBox.TextScaled = true
TheBox.TextSize = 14.000
TheBox.TextWrapped = true

ThinIce.Name = "ThinIce"
ThinIce.Parent = Quests
ThinIce.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
ThinIce.BorderColor3 = Color3.fromRGB(0, 0, 0)
ThinIce.BorderSizePixel = 0
ThinIce.Position = UDim2.new(0.875502586, 0, -1.52851874e-06, 0)
ThinIce.Size = UDim2.new(0, 66, 0, 30)
ThinIce.ZIndex = -1
ThinIce.Font = Enum.Font.FredokaOne
ThinIce.Text = "Thin ice"
ThinIce.TextColor3 = Color3.fromRGB(0, 0, 0)
ThinIce.TextScaled = true
ThinIce.TextSize = 14.000
ThinIce.TextWrapped = true

QuestsDeco.Name = "QuestsDeco"
QuestsDeco.Parent = QuestsFrame
QuestsDeco.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
QuestsDeco.BackgroundTransparency = 1.000
QuestsDeco.BorderColor3 = Color3.fromRGB(0, 0, 0)
QuestsDeco.BorderSizePixel = 0
QuestsDeco.Position = UDim2.new(2.95000005, 0, -0.323000014, 0)
QuestsDeco.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
QuestsDeco.ZIndex = 3

UICorner_7.Parent = QuestsDeco

UIStroke_7.Parent = QuestsDeco
UIStroke_7.Thickness = 3.000
UIStroke_7.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

TeleportButton.Name = "TeleportButton"
TeleportButton.Parent = MainFrame
TeleportButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TeleportButton.BackgroundTransparency = 1.000
TeleportButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TeleportButton.BorderSizePixel = 0
TeleportButton.Position = UDim2.new(0.190000013, 0, 0.317903101, 0)
TeleportButton.Size = UDim2.new(0.13844797, 0, 0.0397236608, 0)
TeleportButton.ZIndex = 3
TeleportButton.Font = Enum.Font.FredokaOne
TeleportButton.Text = "Telleports"
TeleportButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TeleportButton.TextScaled = true
TeleportButton.TextSize = 14.000
TeleportButton.TextWrapped = true

UICorner_8.Parent = TeleportButton

UIStroke_8.Parent = TeleportButton
UIStroke_8.Thickness = 3.000
UIStroke_8.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmFrame.Name = "AutoFarmFrame"
AutoFarmFrame.Parent = MainFrame
AutoFarmFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoFarmFrame.BackgroundTransparency = 1.000
AutoFarmFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmFrame.BorderSizePixel = 0
AutoFarmFrame.Position = UDim2.new(0.0890652537, 0, 0.265975833, 0)
AutoFarmFrame.Size = UDim2.new(0.0881834179, 0, 0.0397236608, 0)
AutoFarmFrame.Visible = false

AutoFarm.Name = "AutoFarm"
AutoFarm.Parent = AutoFarmFrame
AutoFarm.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
AutoFarm.BackgroundTransparency = 1.000
AutoFarm.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarm.BorderSizePixel = 0
AutoFarm.Position = UDim2.new(3.62917113, 0, -1.85176814, 0)
AutoFarm.Size = UDim2.new(3.81000018, 0, 1.13043475, 0)
AutoFarm.ZIndex = 3
AutoFarm.Font = Enum.Font.FredokaOne
AutoFarm.Text = "AutoFarm"
AutoFarm.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarm.TextScaled = true
AutoFarm.TextSize = 14.000
AutoFarm.TextWrapped = true

UIStroke_9.Parent = AutoFarm
UIStroke_9.Thickness = 3.000
UIStroke_9.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_9.Parent = AutoFarm

AutoFarmV1.Name = "AutoFarmV1"
AutoFarmV1.Parent = AutoFarmFrame
AutoFarmV1.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV1.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1.BorderSizePixel = 0
AutoFarmV1.Position = UDim2.new(2.95000005, 0, -0.30399999, 0)
AutoFarmV1.Size = UDim2.new(5.31000042, 0, 1.30434787, 0)

UICorner_10.Parent = AutoFarmV1

UIStroke_10.Parent = AutoFarmV1
UIStroke_10.Thickness = 3.000
UIStroke_10.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmV1Text.Name = "AutoFarmV1Text"
AutoFarmV1Text.Parent = AutoFarmV1
AutoFarmV1Text.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV1Text.BackgroundTransparency = 1.000
AutoFarmV1Text.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1Text.BorderSizePixel = 0
AutoFarmV1Text.Position = UDim2.new(-0.00154610898, 0, 0.0586664826, 0)
AutoFarmV1Text.Size = UDim2.new(0.280602634, 0, 0.866666675, 0)
AutoFarmV1Text.Font = Enum.Font.FredokaOne
AutoFarmV1Text.Text = "AutoFarmMoneyV1"
AutoFarmV1Text.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1Text.TextScaled = true
AutoFarmV1Text.TextSize = 14.000
AutoFarmV1Text.TextWrapped = true

AutoFarmButtonOffOnV1.Name = "AutoFarmButtonOffOnV1"
AutoFarmButtonOffOnV1.Parent = AutoFarmV1
AutoFarmButtonOffOnV1.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonOffOnV1.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonOffOnV1.BorderSizePixel = 0
AutoFarmButtonOffOnV1.Position = UDim2.new(0.292430282, 0, -0.00100000005, 0)
AutoFarmButtonOffOnV1.Size = UDim2.new(0.0564971752, 0, 1, 0)
AutoFarmButtonOffOnV1.ZIndex = 3
AutoFarmButtonOffOnV1.Font = Enum.Font.FredokaOne
AutoFarmButtonOffOnV1.Text = ""
AutoFarmButtonOffOnV1.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonOffOnV1.TextScaled = true
AutoFarmButtonOffOnV1.TextSize = 14.000
AutoFarmButtonOffOnV1.TextWrapped = true

UICorner_11.Parent = AutoFarmButtonOffOnV1

UIStroke_11.Parent = AutoFarmButtonOffOnV1
UIStroke_11.Thickness = 3.000
UIStroke_11.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

settings.Name = "settings"
settings.Parent = AutoFarmV1
settings.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
settings.BorderColor3 = Color3.fromRGB(0, 0, 0)
settings.BorderSizePixel = 0
settings.Position = UDim2.new(5.7573434e-08, 0, 1.27999997, 0)
settings.Size = UDim2.new(0, 530, 0.970089853, 0)

AutoFarmV1TextResetVelocity.Name = "AutoFarmV1TextResetVelocity"
AutoFarmV1TextResetVelocity.Parent = settings
AutoFarmV1TextResetVelocity.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV1TextResetVelocity.BackgroundTransparency = 1.000
AutoFarmV1TextResetVelocity.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1TextResetVelocity.BorderSizePixel = 0
AutoFarmV1TextResetVelocity.Position = UDim2.new(0.0130059011, 0, 0.0502121821, 0)
AutoFarmV1TextResetVelocity.Size = UDim2.new(0.236829251, 0, 0.948786616, 0)
AutoFarmV1TextResetVelocity.Font = Enum.Font.FredokaOne
AutoFarmV1TextResetVelocity.Text = "ResetVelocity"
AutoFarmV1TextResetVelocity.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1TextResetVelocity.TextScaled = true
AutoFarmV1TextResetVelocity.TextSize = 14.000
AutoFarmV1TextResetVelocity.TextWrapped = true

AutoFarmV1TextCollectchest.Name = "AutoFarmV1TextCollectchest"
AutoFarmV1TextCollectchest.Parent = settings
AutoFarmV1TextCollectchest.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV1TextCollectchest.BackgroundTransparency = 1.000
AutoFarmV1TextCollectchest.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1TextCollectchest.BorderSizePixel = 0
AutoFarmV1TextCollectchest.Position = UDim2.new(0.305143297, 0, 0.999999344, 0)
AutoFarmV1TextCollectchest.Size = UDim2.new(0.309693754, 0, -0.958882391, 0)
AutoFarmV1TextCollectchest.Font = Enum.Font.FredokaOne
AutoFarmV1TextCollectchest.Text = "CollectChest"
AutoFarmV1TextCollectchest.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1TextCollectchest.TextScaled = true
AutoFarmV1TextCollectchest.TextSize = 14.000
AutoFarmV1TextCollectchest.TextWrapped = true

AutoFarmButtonSettingsResetVelocityOffOn.Name = "AutoFarmButtonSettingsResetVelocityOffOn"
AutoFarmButtonSettingsResetVelocityOffOn.Parent = settings
AutoFarmButtonSettingsResetVelocityOffOn.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonSettingsResetVelocityOffOn.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsResetVelocityOffOn.BorderSizePixel = 0
AutoFarmButtonSettingsResetVelocityOffOn.Position = UDim2.new(0.249835089, 0, -0.00100000005, 0)
AutoFarmButtonSettingsResetVelocityOffOn.Size = UDim2.new(0.0556699373, 0, 1.00099957, 0)
AutoFarmButtonSettingsResetVelocityOffOn.ZIndex = 3
AutoFarmButtonSettingsResetVelocityOffOn.Font = Enum.Font.FredokaOne
AutoFarmButtonSettingsResetVelocityOffOn.Text = ""
AutoFarmButtonSettingsResetVelocityOffOn.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsResetVelocityOffOn.TextScaled = true
AutoFarmButtonSettingsResetVelocityOffOn.TextSize = 14.000
AutoFarmButtonSettingsResetVelocityOffOn.TextWrapped = true

UICorner_12.Parent = AutoFarmButtonSettingsResetVelocityOffOn

UIStroke_12.Parent = AutoFarmButtonSettingsResetVelocityOffOn
UIStroke_12.Thickness = 3.000
UIStroke_12.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmButtonSettingsCollectchestOffOn.Name = "AutoFarmButtonSettingsCollectchestOffOn"
AutoFarmButtonSettingsCollectchestOffOn.Parent = settings
AutoFarmButtonSettingsCollectchestOffOn.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonSettingsCollectchestOffOn.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsCollectchestOffOn.BorderSizePixel = 0
AutoFarmButtonSettingsCollectchestOffOn.Position = UDim2.new(0.613481402, 0, -0.00100000005, 0)
AutoFarmButtonSettingsCollectchestOffOn.Size = UDim2.new(0.056497179, 0, 1, 0)
AutoFarmButtonSettingsCollectchestOffOn.ZIndex = 3
AutoFarmButtonSettingsCollectchestOffOn.Font = Enum.Font.FredokaOne
AutoFarmButtonSettingsCollectchestOffOn.Text = ""
AutoFarmButtonSettingsCollectchestOffOn.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsCollectchestOffOn.TextScaled = true
AutoFarmButtonSettingsCollectchestOffOn.TextSize = 14.000
AutoFarmButtonSettingsCollectchestOffOn.TextWrapped = true

UICorner_13.Parent = AutoFarmButtonSettingsCollectchestOffOn

UIStroke_13.Parent = AutoFarmButtonSettingsCollectchestOffOn
UIStroke_13.Thickness = 3.000
UIStroke_13.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_14.Parent = settings

UIStroke_14.Parent = settings
UIStroke_14.Thickness = 3.000
UIStroke_14.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmV1TextGetGold.Name = "AutoFarmV1TextGetGold"
AutoFarmV1TextGetGold.Parent = settings
AutoFarmV1TextGetGold.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV1TextGetGold.BackgroundTransparency = 1.000
AutoFarmV1TextGetGold.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1TextGetGold.BorderSizePixel = 0
AutoFarmV1TextGetGold.Position = UDim2.new(0.669294238, 0, 0.931158304, 0)
AutoFarmV1TextGetGold.Size = UDim2.new(0.274880469, 0, -0.958882391, 0)
AutoFarmV1TextGetGold.Font = Enum.Font.FredokaOne
AutoFarmV1TextGetGold.Text = "Get Gold"
AutoFarmV1TextGetGold.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV1TextGetGold.TextScaled = true
AutoFarmV1TextGetGold.TextSize = 14.000
AutoFarmV1TextGetGold.TextWrapped = true

AutoFarmButtonSettingsGetGoldOffOn.Name = "AutoFarmButtonSettingsGetGoldOffOn"
AutoFarmButtonSettingsGetGoldOffOn.Parent = settings
AutoFarmButtonSettingsGetGoldOffOn.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonSettingsGetGoldOffOn.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsGetGoldOffOn.BorderSizePixel = 0
AutoFarmButtonSettingsGetGoldOffOn.Position = UDim2.new(0.944174707, 0, -0.00100000005, 0)
AutoFarmButtonSettingsGetGoldOffOn.Size = UDim2.new(0.0556699373, 0, 1.00099957, 0)
AutoFarmButtonSettingsGetGoldOffOn.ZIndex = 3
AutoFarmButtonSettingsGetGoldOffOn.Font = Enum.Font.FredokaOne
AutoFarmButtonSettingsGetGoldOffOn.Text = ""
AutoFarmButtonSettingsGetGoldOffOn.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsGetGoldOffOn.TextScaled = true
AutoFarmButtonSettingsGetGoldOffOn.TextSize = 14.000
AutoFarmButtonSettingsGetGoldOffOn.TextWrapped = true

UICorner_15.Parent = AutoFarmButtonSettingsGetGoldOffOn

UIStroke_15.Parent = AutoFarmButtonSettingsGetGoldOffOn
UIStroke_15.Thickness = 3.000
UIStroke_15.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmCandyV1.Name = "AutoFarmCandyV1"
AutoFarmCandyV1.Parent = AutoFarmFrame
AutoFarmCandyV1.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmCandyV1.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmCandyV1.BorderSizePixel = 0
AutoFarmCandyV1.Position = UDim2.new(2.95000029, 0, 2.96216321, 0)
AutoFarmCandyV1.Size = UDim2.new(5.31000042, 0, 1.30434787, 0)

UICorner_16.Parent = AutoFarmCandyV1

UIStroke_16.Parent = AutoFarmCandyV1
UIStroke_16.Thickness = 3.000
UIStroke_16.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmCandyV1_2.Name = "AutoFarmCandyV1"
AutoFarmCandyV1_2.Parent = AutoFarmCandyV1
AutoFarmCandyV1_2.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmCandyV1_2.BackgroundTransparency = 1.000
AutoFarmCandyV1_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmCandyV1_2.BorderSizePixel = 0
AutoFarmCandyV1_2.Position = UDim2.new(-0.00154610898, 0, 0.0586664826, 0)
AutoFarmCandyV1_2.Size = UDim2.new(0.280602634, 0, 0.866666675, 0)
AutoFarmCandyV1_2.Font = Enum.Font.FredokaOne
AutoFarmCandyV1_2.Text = "AutoFarmCandyV1"
AutoFarmCandyV1_2.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmCandyV1_2.TextScaled = true
AutoFarmCandyV1_2.TextSize = 14.000
AutoFarmCandyV1_2.TextWrapped = true

AutoFarmCandyButtonOffOn.Name = "AutoFarmCandyButtonOffOn"
AutoFarmCandyButtonOffOn.Parent = AutoFarmCandyV1
AutoFarmCandyButtonOffOn.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmCandyButtonOffOn.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmCandyButtonOffOn.BorderSizePixel = 0
AutoFarmCandyButtonOffOn.Position = UDim2.new(0.292430282, 0, -0.00100000005, 0)
AutoFarmCandyButtonOffOn.Size = UDim2.new(0.0564971752, 0, 1, 0)
AutoFarmCandyButtonOffOn.ZIndex = 3
AutoFarmCandyButtonOffOn.Font = Enum.Font.FredokaOne
AutoFarmCandyButtonOffOn.Text = ""
AutoFarmCandyButtonOffOn.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmCandyButtonOffOn.TextScaled = true
AutoFarmCandyButtonOffOn.TextSize = 14.000
AutoFarmCandyButtonOffOn.TextWrapped = true

UICorner_17.Parent = AutoFarmCandyButtonOffOn

UIStroke_17.Parent = AutoFarmCandyButtonOffOn
UIStroke_17.Thickness = 3.000
UIStroke_17.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmV2.Name = "AutoFarmV2"
AutoFarmV2.Parent = AutoFarmFrame
AutoFarmV2.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV2.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2.BorderSizePixel = 0
AutoFarmV2.Position = UDim2.new(2.93998265, 0, 4.6500001, 0)
AutoFarmV2.Size = UDim2.new(5.31000042, 0, 1.30434787, 0)

UICorner_18.Parent = AutoFarmV2

UIStroke_18.Parent = AutoFarmV2
UIStroke_18.Thickness = 3.000
UIStroke_18.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmV2Text.Name = "AutoFarmV2Text"
AutoFarmV2Text.Parent = AutoFarmV2
AutoFarmV2Text.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV2Text.BackgroundTransparency = 1.000
AutoFarmV2Text.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2Text.BorderSizePixel = 0
AutoFarmV2Text.Position = UDim2.new(-0.00154610898, 0, 0.0586664826, 0)
AutoFarmV2Text.Size = UDim2.new(0.280602634, 0, 0.866666675, 0)
AutoFarmV2Text.Font = Enum.Font.FredokaOne
AutoFarmV2Text.Text = "AutoFarmMoneyV2"
AutoFarmV2Text.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2Text.TextScaled = true
AutoFarmV2Text.TextSize = 14.000
AutoFarmV2Text.TextWrapped = true

AutoFarmButtonOffOnV2.Name = "AutoFarmButtonOffOnV2"
AutoFarmButtonOffOnV2.Parent = AutoFarmV2
AutoFarmButtonOffOnV2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonOffOnV2.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonOffOnV2.BorderSizePixel = 0
AutoFarmButtonOffOnV2.Position = UDim2.new(0.292430282, 0, -0.00100000005, 0)
AutoFarmButtonOffOnV2.Size = UDim2.new(0.0564971752, 0, 1, 0)
AutoFarmButtonOffOnV2.ZIndex = 3
AutoFarmButtonOffOnV2.Font = Enum.Font.FredokaOne
AutoFarmButtonOffOnV2.Text = ""
AutoFarmButtonOffOnV2.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonOffOnV2.TextScaled = true
AutoFarmButtonOffOnV2.TextSize = 14.000
AutoFarmButtonOffOnV2.TextWrapped = true

UICorner_19.Parent = AutoFarmButtonOffOnV2

UIStroke_19.Parent = AutoFarmButtonOffOnV2
UIStroke_19.Thickness = 3.000
UIStroke_19.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

settings_2.Name = "settings"
settings_2.Parent = AutoFarmV2
settings_2.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
settings_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
settings_2.BorderSizePixel = 0
settings_2.Position = UDim2.new(5.7573434e-08, 0, 1.27999997, 0)
settings_2.Size = UDim2.new(0, 530, 0.970089853, 0)

AutoFarmV2TextCollectchest.Name = "AutoFarmV2TextCollectchest"
AutoFarmV2TextCollectchest.Parent = settings_2
AutoFarmV2TextCollectchest.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV2TextCollectchest.BackgroundTransparency = 1.000
AutoFarmV2TextCollectchest.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2TextCollectchest.BorderSizePixel = 0
AutoFarmV2TextCollectchest.Position = UDim2.new(0.00136972102, 0, 0.999999881, 0)
AutoFarmV2TextCollectchest.Size = UDim2.new(0.309693754, 0, -0.958882391, 0)
AutoFarmV2TextCollectchest.Font = Enum.Font.FredokaOne
AutoFarmV2TextCollectchest.Text = "CollectChest"
AutoFarmV2TextCollectchest.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2TextCollectchest.TextScaled = true
AutoFarmV2TextCollectchest.TextSize = 14.000
AutoFarmV2TextCollectchest.TextWrapped = true

AutoFarmButtonSettingsCollectchestOffOn_2.Name = "AutoFarmButtonSettingsCollectchestOffOn"
AutoFarmButtonSettingsCollectchestOffOn_2.Parent = settings_2
AutoFarmButtonSettingsCollectchestOffOn_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonSettingsCollectchestOffOn_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsCollectchestOffOn_2.BorderSizePixel = 0
AutoFarmButtonSettingsCollectchestOffOn_2.Position = UDim2.new(0.30970782, 0, -0.00100001041, 0)
AutoFarmButtonSettingsCollectchestOffOn_2.Size = UDim2.new(0.056497179, 0, 1, 0)
AutoFarmButtonSettingsCollectchestOffOn_2.ZIndex = 3
AutoFarmButtonSettingsCollectchestOffOn_2.Font = Enum.Font.FredokaOne
AutoFarmButtonSettingsCollectchestOffOn_2.Text = ""
AutoFarmButtonSettingsCollectchestOffOn_2.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsCollectchestOffOn_2.TextScaled = true
AutoFarmButtonSettingsCollectchestOffOn_2.TextSize = 14.000
AutoFarmButtonSettingsCollectchestOffOn_2.TextWrapped = true

UICorner_20.Parent = AutoFarmButtonSettingsCollectchestOffOn_2

UIStroke_20.Parent = AutoFarmButtonSettingsCollectchestOffOn_2
UIStroke_20.Thickness = 3.000
UIStroke_20.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_21.Parent = settings_2

UIStroke_21.Parent = settings_2
UIStroke_21.Thickness = 3.000
UIStroke_21.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoFarmV2TextGetGold.Name = "AutoFarmV2TextGetGold"
AutoFarmV2TextGetGold.Parent = settings_2
AutoFarmV2TextGetGold.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
AutoFarmV2TextGetGold.BackgroundTransparency = 1.000
AutoFarmV2TextGetGold.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2TextGetGold.BorderSizePixel = 0
AutoFarmV2TextGetGold.Position = UDim2.new(0.365520656, 0, 0.931158841, 0)
AutoFarmV2TextGetGold.Size = UDim2.new(0.274880469, 0, -0.958882391, 0)
AutoFarmV2TextGetGold.Font = Enum.Font.FredokaOne
AutoFarmV2TextGetGold.Text = "Get Gold"
AutoFarmV2TextGetGold.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmV2TextGetGold.TextScaled = true
AutoFarmV2TextGetGold.TextSize = 14.000
AutoFarmV2TextGetGold.TextWrapped = true

AutoFarmButtonSettingsGetGoldOffOn_2.Name = "AutoFarmButtonSettingsGetGoldOffOn"
AutoFarmButtonSettingsGetGoldOffOn_2.Parent = settings_2
AutoFarmButtonSettingsGetGoldOffOn_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
AutoFarmButtonSettingsGetGoldOffOn_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsGetGoldOffOn_2.BorderSizePixel = 0
AutoFarmButtonSettingsGetGoldOffOn_2.Position = UDim2.new(0.640401125, 0, -0.00100001041, 0)
AutoFarmButtonSettingsGetGoldOffOn_2.Size = UDim2.new(0.0556699373, 0, 1.00099957, 0)
AutoFarmButtonSettingsGetGoldOffOn_2.ZIndex = 3
AutoFarmButtonSettingsGetGoldOffOn_2.Font = Enum.Font.FredokaOne
AutoFarmButtonSettingsGetGoldOffOn_2.Text = ""
AutoFarmButtonSettingsGetGoldOffOn_2.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoFarmButtonSettingsGetGoldOffOn_2.TextScaled = true
AutoFarmButtonSettingsGetGoldOffOn_2.TextSize = 14.000
AutoFarmButtonSettingsGetGoldOffOn_2.TextWrapped = true

UICorner_22.Parent = AutoFarmButtonSettingsGetGoldOffOn_2

UIStroke_22.Parent = AutoFarmButtonSettingsGetGoldOffOn_2
UIStroke_22.Thickness = 3.000
UIStroke_22.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

QuestsButton.Name = "QuestsButton"
QuestsButton.Parent = MainFrame
QuestsButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
QuestsButton.BackgroundTransparency = 1.000
QuestsButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
QuestsButton.BorderSizePixel = 0
QuestsButton.Position = UDim2.new(0.190000013, 0, 0.370000005, 0)
QuestsButton.Size = UDim2.new(0.13844797, 0, 0.0397236608, 0)
QuestsButton.ZIndex = 3
QuestsButton.Font = Enum.Font.FredokaOne
QuestsButton.Text = "Quests"
QuestsButton.TextColor3 = Color3.fromRGB(0, 0, 0)
QuestsButton.TextScaled = true
QuestsButton.TextSize = 14.000
QuestsButton.TextWrapped = true

UICorner_23.Parent = QuestsButton

UIStroke_23.Parent = QuestsButton
UIStroke_23.Thickness = 3.000
UIStroke_23.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

TelleportsFrame.Name = "TelleportsFrame"
TelleportsFrame.Parent = MainFrame
TelleportsFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TelleportsFrame.BackgroundTransparency = 1.000
TelleportsFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TelleportsFrame.BorderSizePixel = 0
TelleportsFrame.Position = UDim2.new(0.0890652537, 0, 0.265975833, 0)
TelleportsFrame.Size = UDim2.new(0.0881834179, 0, 0.0397236608, 0)
TelleportsFrame.Visible = false

Telleports.Name = "Telleports"
Telleports.Parent = TelleportsFrame
Telleports.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
Telleports.BackgroundTransparency = 1.000
Telleports.BorderColor3 = Color3.fromRGB(0, 0, 0)
Telleports.BorderSizePixel = 0
Telleports.Position = UDim2.new(3.62917113, 0, -1.852, 0)
Telleports.Size = UDim2.new(3.81000018, 0, 1.13043475, 0)
Telleports.ZIndex = 3
Telleports.Font = Enum.Font.FredokaOne
Telleports.Text = "Telleports"
Telleports.TextColor3 = Color3.fromRGB(0, 0, 0)
Telleports.TextScaled = true
Telleports.TextSize = 14.000
Telleports.TextWrapped = true

UIStroke_24.Parent = Telleports
UIStroke_24.Thickness = 3.000
UIStroke_24.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_24.Parent = Telleports

StagesV1.Name = "StagesV1"
StagesV1.Parent = TelleportsFrame
StagesV1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
StagesV1.BorderColor3 = Color3.fromRGB(0, 0, 0)
StagesV1.BorderSizePixel = 0
StagesV1.Position = UDim2.new(2.93998289, 0, 4.02651691, 0)
StagesV1.Size = UDim2.new(5.29987574, 0, 1.30400002, 0)
StagesV1.ZIndex = 2

UIStroke_25.Parent = StagesV1
UIStroke_25.Thickness = 3.000
UIStroke_25.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_25.Parent = StagesV1

Stage5.Name = "Stage5"
Stage5.Parent = StagesV1
Stage5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stage5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage5.BorderSizePixel = 0
Stage5.Position = UDim2.new(0.365556091, 0, -2.03856871e-06, 0)
Stage5.Size = UDim2.new(0, 46, 0, 29)
Stage5.ZIndex = -1
Stage5.Font = Enum.Font.SourceSans
Stage5.Text = "5"
Stage5.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage5.TextScaled = true
Stage5.TextSize = 14.000
Stage5.TextWrapped = true

Stage2.Name = "Stage2"
Stage2.Parent = StagesV1
Stage2.BackgroundColor3 = Color3.fromRGB(159, 159, 159)
Stage2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage2.BorderSizePixel = 0
Stage2.Position = UDim2.new(0.0907359049, 0, -2.03856871e-06, 0)
Stage2.Size = UDim2.new(0, 46, 0, 29)
Stage2.ZIndex = -1
Stage2.Font = Enum.Font.SourceSans
Stage2.Text = "2"
Stage2.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage2.TextScaled = true
Stage2.TextSize = 14.000
Stage2.TextWrapped = true

Stage3.Name = "Stage3"
Stage3.Parent = StagesV1
Stage3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stage3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage3.BorderSizePixel = 0
Stage3.Position = UDim2.new(0.18317531, 0, -2.03856871e-06, 0)
Stage3.Size = UDim2.new(0, 46, 0, 29)
Stage3.ZIndex = -1
Stage3.Font = Enum.Font.SourceSans
Stage3.Text = "3"
Stage3.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage3.TextScaled = true
Stage3.TextSize = 14.000
Stage3.TextWrapped = true

Stage7.Name = "Stage7"
Stage7.Parent = StagesV1
Stage7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stage7.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage7.BorderSizePixel = 0
Stage7.Position = UDim2.new(0.550435066, 0, -2.03856871e-06, 0)
Stage7.Size = UDim2.new(0, 46, 0, 29)
Stage7.ZIndex = -1
Stage7.Font = Enum.Font.SourceSans
Stage7.Text = "7"
Stage7.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage7.TextScaled = true
Stage7.TextSize = 14.000
Stage7.TextWrapped = true

Stage4.Name = "Stage4"
Stage4.Parent = StagesV1
Stage4.BackgroundColor3 = Color3.fromRGB(159, 159, 159)
Stage4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage4.BorderSizePixel = 0
Stage4.Position = UDim2.new(0.273116469, 0, -2.03856871e-06, 0)
Stage4.Size = UDim2.new(0, 48, 0, 29)
Stage4.ZIndex = -1
Stage4.Font = Enum.Font.SourceSans
Stage4.Text = "4"
Stage4.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage4.TextScaled = true
Stage4.TextSize = 14.000
Stage4.TextWrapped = true

Stage1.Name = "Stage1"
Stage1.Parent = StagesV1
Stage1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stage1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage1.BorderSizePixel = 0
Stage1.Position = UDim2.new(0, 0, -2.03856871e-06, 0)
Stage1.Size = UDim2.new(0, 46, 0, 29)
Stage1.ZIndex = -1
Stage1.Font = Enum.Font.SourceSans
Stage1.Text = "1"
Stage1.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage1.TextScaled = true
Stage1.TextSize = 14.000
Stage1.TextWrapped = true

Stage6.Name = "Stage6"
Stage6.Parent = StagesV1
Stage6.BackgroundColor3 = Color3.fromRGB(159, 159, 159)
Stage6.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage6.BorderSizePixel = 0
Stage6.Position = UDim2.new(0.457995504, 0, -2.03856871e-06, 0)
Stage6.Size = UDim2.new(0, 46, 0, 29)
Stage6.ZIndex = -1
Stage6.Font = Enum.Font.SourceSans
Stage6.Text = "6"
Stage6.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage6.TextScaled = true
Stage6.TextSize = 14.000
Stage6.TextWrapped = true

Stage8.Name = "Stage8"
Stage8.Parent = StagesV1
Stage8.BackgroundColor3 = Color3.fromRGB(159, 159, 159)
Stage8.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage8.BorderSizePixel = 0
Stage8.Position = UDim2.new(0.642433643, 0, -2.03856871e-06, 0)
Stage8.Size = UDim2.new(0, 46, 0, 29)
Stage8.ZIndex = -1
Stage8.Font = Enum.Font.SourceSans
Stage8.Text = "8"
Stage8.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage8.TextScaled = true
Stage8.TextSize = 14.000
Stage8.TextWrapped = true

Stage9.Name = "Stage9"
Stage9.Parent = StagesV1
Stage9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Stage9.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage9.BorderSizePixel = 0
Stage9.Position = UDim2.new(0.73443222, 0, -2.03856871e-06, 0)
Stage9.Size = UDim2.new(0, 46, 0, 29)
Stage9.ZIndex = -1
Stage9.Font = Enum.Font.SourceSans
Stage9.Text = "9"
Stage9.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage9.TextScaled = true
Stage9.TextSize = 14.000
Stage9.TextWrapped = true

endstage.Name = "endstage"
endstage.Parent = StagesV1
endstage.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
endstage.BorderColor3 = Color3.fromRGB(0, 0, 0)
endstage.BorderSizePixel = 0
endstage.Position = UDim2.new(0.911328137, 0, -2.03856871e-06, 0)
endstage.Size = UDim2.new(0, 46, 0, 29)
endstage.ZIndex = -1
endstage.Font = Enum.Font.SourceSans
endstage.Text = "end"
endstage.TextColor3 = Color3.fromRGB(0, 0, 0)
endstage.TextScaled = true
endstage.TextSize = 14.000
endstage.TextWrapped = true

Stage10.Name = "Stage10"
Stage10.Parent = StagesV1
Stage10.BackgroundColor3 = Color3.fromRGB(159, 159, 159)
Stage10.BorderColor3 = Color3.fromRGB(0, 0, 0)
Stage10.BorderSizePixel = 0
Stage10.Position = UDim2.new(0.823104084, 0, -2.03856871e-06, 0)
Stage10.Size = UDim2.new(0, 46, 0, 29)
Stage10.ZIndex = -1
Stage10.Font = Enum.Font.SourceSans
Stage10.Text = "10"
Stage10.TextColor3 = Color3.fromRGB(0, 0, 0)
Stage10.TextScaled = true
Stage10.TextSize = 14.000
Stage10.TextWrapped = true

TeamsV1Deco.Name = "TeamsV1Deco"
TeamsV1Deco.Parent = TelleportsFrame
TeamsV1Deco.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
TeamsV1Deco.BackgroundTransparency = 1.000
TeamsV1Deco.BorderColor3 = Color3.fromRGB(0, 0, 0)
TeamsV1Deco.BorderSizePixel = 0
TeamsV1Deco.Position = UDim2.new(2.95000052, 0, 0.958999991, 0)
TeamsV1Deco.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
TeamsV1Deco.ZIndex = 3

UICorner_26.Parent = TeamsV1Deco

UIStroke_26.Parent = TeamsV1Deco
UIStroke_26.Thickness = 3.000
UIStroke_26.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

TeamsText.Name = "TeamsText"
TeamsText.Parent = TelleportsFrame
TeamsText.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
TeamsText.BackgroundTransparency = 1.000
TeamsText.BorderColor3 = Color3.fromRGB(0, 0, 0)
TeamsText.BorderSizePixel = 0
TeamsText.Position = UDim2.new(4.06995106, 0, -0.323152155, 0)
TeamsText.Size = UDim2.new(2.90977526, 0, 0.866666555, 0)
TeamsText.Font = Enum.Font.FredokaOne
TeamsText.Text = "Teams"
TeamsText.TextColor3 = Color3.fromRGB(0, 0, 0)
TeamsText.TextScaled = true
TeamsText.TextSize = 14.000
TeamsText.TextWrapped = true

UICorner_27.Parent = TeamsText

UIStroke_27.Parent = TeamsText
UIStroke_27.Thickness = 3.000
UIStroke_27.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

TeamsV1.Name = "TeamsV1"
TeamsV1.Parent = TelleportsFrame
TeamsV1.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
TeamsV1.BackgroundTransparency = 1.000
TeamsV1.BorderColor3 = Color3.fromRGB(0, 0, 0)
TeamsV1.BorderSizePixel = 0
TeamsV1.Position = UDim2.new(2.95000052, 0, 0.958702981, 0)
TeamsV1.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
TeamsV1.ZIndex = 2

UIStroke_28.Parent = TeamsV1
UIStroke_28.Thickness = 3.000
UIStroke_28.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_28.Parent = TeamsV1

White.Name = "White"
White.Parent = TeamsV1
White.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
White.BorderColor3 = Color3.fromRGB(0, 0, 0)
White.BorderSizePixel = 0
White.Position = UDim2.new(5.7573434e-08, 0, -1.52851885e-06, 0)
White.Size = UDim2.new(0, 76, 0, 30)
White.ZIndex = -1
White.Font = Enum.Font.SourceSans
White.Text = ""
White.TextColor3 = Color3.fromRGB(0, 0, 0)
White.TextSize = 14.000

Blue.Name = "Blue"
Blue.Parent = TeamsV1
Blue.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
Blue.BorderColor3 = Color3.fromRGB(0, 0, 0)
Blue.BorderSizePixel = 0
Blue.Position = UDim2.new(0.143410876, 0, -1.52851885e-06, 0)
Blue.Size = UDim2.new(0, 76, 0, 30)
Blue.ZIndex = -1
Blue.Font = Enum.Font.SourceSans
Blue.Text = ""
Blue.TextColor3 = Color3.fromRGB(0, 0, 0)
Blue.TextSize = 14.000

Green.Name = "Green"
Green.Parent = TeamsV1
Green.BackgroundColor3 = Color3.fromRGB(58, 125, 21)
Green.BorderColor3 = Color3.fromRGB(0, 0, 0)
Green.BorderSizePixel = 0
Green.Position = UDim2.new(0.286821693, 0, -1.52851885e-06, 0)
Green.Size = UDim2.new(0, 76, 0, 30)
Green.ZIndex = -1
Green.Font = Enum.Font.SourceSans
Green.Text = ""
Green.TextColor3 = Color3.fromRGB(0, 0, 0)
Green.TextSize = 14.000

Red.Name = "Red"
Red.Parent = TeamsV1
Red.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Red.BorderColor3 = Color3.fromRGB(0, 0, 0)
Red.BorderSizePixel = 0
Red.Position = UDim2.new(0.426356733, 0, -1.52851874e-06, 0)
Red.Size = UDim2.new(0, 77, 0, 30)
Red.ZIndex = -1
Red.Font = Enum.Font.SourceSans
Red.Text = ""
Red.TextColor3 = Color3.fromRGB(0, 0, 0)
Red.TextSize = 14.000

Black.Name = "Black"
Black.Parent = TeamsV1
Black.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Black.BorderColor3 = Color3.fromRGB(0, 0, 0)
Black.BorderSizePixel = 0
Black.Position = UDim2.new(0.569767535, 0, -1.52851874e-06, 0)
Black.Size = UDim2.new(0, 76, 0, 30)
Black.ZIndex = -1
Black.Font = Enum.Font.SourceSans
Black.Text = ""
Black.TextColor3 = Color3.fromRGB(0, 0, 0)
Black.TextSize = 14.000

Yellow.Name = "Yellow"
Yellow.Parent = TeamsV1
Yellow.BackgroundColor3 = Color3.fromRGB(255, 255, 0)
Yellow.BorderColor3 = Color3.fromRGB(0, 0, 0)
Yellow.BorderSizePixel = 0
Yellow.Position = UDim2.new(0.713178277, 0, -1.52851885e-06, 0)
Yellow.Size = UDim2.new(0, 76, 0, 30)
Yellow.ZIndex = -1
Yellow.Font = Enum.Font.SourceSans
Yellow.Text = ""
Yellow.TextColor3 = Color3.fromRGB(0, 0, 0)
Yellow.TextSize = 14.000

Magenta.Name = "Magenta"
Magenta.Parent = TeamsV1
Magenta.BackgroundColor3 = Color3.fromRGB(170, 0, 170)
Magenta.BorderColor3 = Color3.fromRGB(0, 0, 0)
Magenta.BorderSizePixel = 0
Magenta.Position = UDim2.new(0.856589139, 0, -1.52851885e-06, 0)
Magenta.Size = UDim2.new(0, 76, 0, 30)
Magenta.ZIndex = -1
Magenta.Font = Enum.Font.SourceSans
Magenta.Text = ""
Magenta.TextColor3 = Color3.fromRGB(0, 0, 0)
Magenta.TextSize = 14.000

StagesText.Name = "StagesText"
StagesText.Parent = TelleportsFrame
StagesText.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
StagesText.BackgroundTransparency = 1.000
StagesText.BorderColor3 = Color3.fromRGB(0, 0, 0)
StagesText.BorderSizePixel = 0
StagesText.Position = UDim2.new(4.05993319, 0, 2.72559166, 0)
StagesText.Size = UDim2.new(2.90977526, 0, 0.866666555, 0)
StagesText.Font = Enum.Font.FredokaOne
StagesText.Text = "Stages"
StagesText.TextColor3 = Color3.fromRGB(0, 0, 0)
StagesText.TextScaled = true
StagesText.TextSize = 14.000
StagesText.TextWrapped = true

UICorner_29.Parent = StagesText

UIStroke_29.Parent = StagesText
UIStroke_29.Thickness = 3.000
UIStroke_29.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

StagesV1Deco.Name = "StagesV1Deco"
StagesV1Deco.Parent = TelleportsFrame
StagesV1Deco.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
StagesV1Deco.BackgroundTransparency = 1.000
StagesV1Deco.BorderColor3 = Color3.fromRGB(0, 0, 0)
StagesV1Deco.BorderSizePixel = 0
StagesV1Deco.Position = UDim2.new(2.94000006, 0, 4.02699995, 0)
StagesV1Deco.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
StagesV1Deco.ZIndex = 3

UICorner_30.Parent = StagesV1Deco

UIStroke_30.Parent = StagesV1Deco
UIStroke_30.Thickness = 3.000
UIStroke_30.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoBuyButton.Name = "AutoBuyButton"
AutoBuyButton.Parent = MainFrame
AutoBuyButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoBuyButton.BackgroundTransparency = 1.000
AutoBuyButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoBuyButton.BorderSizePixel = 0
AutoBuyButton.Position = UDim2.new(0.190000013, 0, 0.423000008, 0)
AutoBuyButton.Size = UDim2.new(0.13844797, 0, 0.0397236608, 0)
AutoBuyButton.ZIndex = 3
AutoBuyButton.Font = Enum.Font.FredokaOne
AutoBuyButton.Text = "AutoBuy"
AutoBuyButton.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoBuyButton.TextScaled = true
AutoBuyButton.TextSize = 14.000
AutoBuyButton.TextWrapped = true

UICorner_31.Parent = AutoBuyButton

UIStroke_31.Parent = AutoBuyButton
UIStroke_31.Thickness = 3.000
UIStroke_31.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

AutoBuyFrame.Name = "AutoBuyFrame"
AutoBuyFrame.Parent = MainFrame
AutoBuyFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AutoBuyFrame.BackgroundTransparency = 1.000
AutoBuyFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoBuyFrame.BorderSizePixel = 0
AutoBuyFrame.Position = UDim2.new(0.0890652537, 0, 0.265975833, 0)
AutoBuyFrame.Size = UDim2.new(0.0881834179, 0, 0.0397236608, 0)
AutoBuyFrame.Visible = false

AutoBuy.Name = "AutoBuy"
AutoBuy.Parent = AutoBuyFrame
AutoBuy.BackgroundColor3 = Color3.fromRGB(100, 100, 100)
AutoBuy.BackgroundTransparency = 1.000
AutoBuy.BorderColor3 = Color3.fromRGB(0, 0, 0)
AutoBuy.BorderSizePixel = 0
AutoBuy.Position = UDim2.new(3.62917113, 0, -1.852, 0)
AutoBuy.Size = UDim2.new(3.81000018, 0, 1.13043475, 0)
AutoBuy.ZIndex = 3
AutoBuy.Font = Enum.Font.FredokaOne
AutoBuy.Text = "AutoBuy"
AutoBuy.TextColor3 = Color3.fromRGB(0, 0, 0)
AutoBuy.TextScaled = true
AutoBuy.TextSize = 14.000
AutoBuy.TextWrapped = true

UIStroke_32.Parent = AutoBuy
UIStroke_32.Thickness = 3.000
UIStroke_32.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_32.Parent = AutoBuy

ChestsV1Deco.Name = "ChestsV1Deco"
ChestsV1Deco.Parent = AutoBuyFrame
ChestsV1Deco.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
ChestsV1Deco.BackgroundTransparency = 1.000
ChestsV1Deco.BorderColor3 = Color3.fromRGB(0, 0, 0)
ChestsV1Deco.BorderSizePixel = 0
ChestsV1Deco.Position = UDim2.new(2.95000052, 0, 0.958999991, 0)
ChestsV1Deco.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
ChestsV1Deco.ZIndex = 3

UICorner_33.Parent = ChestsV1Deco

UIStroke_33.Parent = ChestsV1Deco
UIStroke_33.Thickness = 3.000
UIStroke_33.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

ChestsText.Name = "ChestsText"
ChestsText.Parent = AutoBuyFrame
ChestsText.BackgroundColor3 = Color3.fromRGB(106, 106, 106)
ChestsText.BackgroundTransparency = 1.000
ChestsText.BorderColor3 = Color3.fromRGB(0, 0, 0)
ChestsText.BorderSizePixel = 0
ChestsText.Position = UDim2.new(4.06995106, 0, -0.323152155, 0)
ChestsText.Size = UDim2.new(2.90977526, 0, 0.866666555, 0)
ChestsText.Font = Enum.Font.FredokaOne
ChestsText.Text = "Chests"
ChestsText.TextColor3 = Color3.fromRGB(0, 0, 0)
ChestsText.TextScaled = true
ChestsText.TextSize = 14.000
ChestsText.TextWrapped = true

UICorner_34.Parent = ChestsText

UIStroke_34.Parent = ChestsText
UIStroke_34.Thickness = 3.000
UIStroke_34.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

ChestsV1.Name = "ChestsV1"
ChestsV1.Parent = AutoBuyFrame
ChestsV1.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
ChestsV1.BorderColor3 = Color3.fromRGB(0, 0, 0)
ChestsV1.BorderSizePixel = 0
ChestsV1.Position = UDim2.new(2.95000052, 0, 0.958702981, 0)
ChestsV1.Size = UDim2.new(5.29987574, 0, 1.30434799, 0)
ChestsV1.ZIndex = 2

UIStroke_35.Parent = ChestsV1
UIStroke_35.Thickness = 3.000
UIStroke_35.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

UICorner_35.Parent = ChestsV1

Cammon.Name = "Cammon"
Cammon.Parent = ChestsV1
Cammon.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Cammon.BorderColor3 = Color3.fromRGB(255, 0, 0)
Cammon.BorderSizePixel = 0
Cammon.Position = UDim2.new(-1.15366838e-07, 0, -1.52851874e-06, 0)
Cammon.Size = UDim2.new(0, 106, 0, 30)
Cammon.ZIndex = -1
Cammon.Font = Enum.Font.FredokaOne
Cammon.Text = "Cammon"
Cammon.TextColor3 = Color3.fromRGB(0, 0, 0)
Cammon.TextScaled = true
Cammon.TextSize = 14.000
Cammon.TextWrapped = true

Uncammon.Name = "Uncammon"
Uncammon.Parent = ChestsV1
Uncammon.BackgroundColor3 = Color3.fromRGB(205, 0, 0)
Uncammon.BorderColor3 = Color3.fromRGB(255, 0, 0)
Uncammon.BorderSizePixel = 0
Uncammon.Position = UDim2.new(0.201858521, 0, -1.52851874e-06, 0)
Uncammon.Size = UDim2.new(0, 106, 0, 30)
Uncammon.ZIndex = -1
Uncammon.Font = Enum.Font.FredokaOne
Uncammon.Text = "Uncammon"
Uncammon.TextColor3 = Color3.fromRGB(0, 0, 0)
Uncammon.TextScaled = true
Uncammon.TextSize = 14.000
Uncammon.TextWrapped = true

Rare.Name = "Rare"
Rare.Parent = ChestsV1
Rare.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Rare.BorderColor3 = Color3.fromRGB(255, 0, 0)
Rare.BorderSizePixel = 0
Rare.Position = UDim2.new(0.403716326, 0, -1.52851874e-06, 0)
Rare.Size = UDim2.new(0, 103, 0, 30)
Rare.ZIndex = -1
Rare.Font = Enum.Font.FredokaOne
Rare.Text = "Rare"
Rare.TextColor3 = Color3.fromRGB(0, 0, 0)
Rare.TextScaled = true
Rare.TextSize = 14.000
Rare.TextWrapped = true

Epic.Name = "Epic"
Epic.Parent = ChestsV1
Epic.BackgroundColor3 = Color3.fromRGB(205, 0, 0)
Epic.BorderColor3 = Color3.fromRGB(255, 0, 0)
Epic.BorderSizePixel = 0
Epic.Position = UDim2.new(0.600119054, 0, -1.52851874e-06, 0)
Epic.Size = UDim2.new(0, 105, 0, 30)
Epic.ZIndex = -1
Epic.Font = Enum.Font.FredokaOne
Epic.Text = "Epic"
Epic.TextColor3 = Color3.fromRGB(0, 0, 0)
Epic.TextScaled = true
Epic.TextSize = 14.000
Epic.TextWrapped = true

Legendary.Name = "Legendary"
Legendary.Parent = ChestsV1
Legendary.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Legendary.BorderColor3 = Color3.fromRGB(255, 0, 0)
Legendary.BorderSizePixel = 0
Legendary.Position = UDim2.new(0.801977217, 0, -1.52851874e-06, 0)
Legendary.Size = UDim2.new(0, 103, 0, 30)
Legendary.ZIndex = -1
Legendary.Font = Enum.Font.FredokaOne
Legendary.Text = "Legendary"
Legendary.TextColor3 = Color3.fromRGB(0, 0, 0)
Legendary.TextScaled = true
Legendary.TextSize = 14.000
Legendary.TextWrapped = true

OpenMainFrame.Name = "OpenMainFrame"
OpenMainFrame.Parent = Reversal
OpenMainFrame.BackgroundColor3 = Color3.fromRGB(103, 103, 103)
OpenMainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
OpenMainFrame.BorderSizePixel = 0
OpenMainFrame.Position = UDim2.new(0.0185840707, 0, 0.884083033, 0)
OpenMainFrame.Size = UDim2.new(0, 50, 0, 50)
OpenMainFrame.Font = Enum.Font.DenkOne
OpenMainFrame.Text = "R"
OpenMainFrame.TextColor3 = Color3.fromRGB(0, 0, 0)
OpenMainFrame.TextScaled = true
OpenMainFrame.TextSize = 14.000
OpenMainFrame.TextWrapped = true

UICorner_36.Parent = OpenMainFrame

UIStroke_36.Parent = OpenMainFrame
UIStroke_36.Thickness = 3.000
UIStroke_36.ApplyStrokeMode = Enum.ApplyStrokeMode.Border

-- Scripts:

local function OODD_script() -- QuestsFrame.QuestsScriptComplete 
	local script = Instance.new('LocalScript', QuestsFrame)

	script.Parent.Quests.Cloud.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(1)
		wait(0.1)
		if Playerteam == teams["white"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.WhiteZone:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["black"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.BlackZone:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["blue"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["Really blueZone"]:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["red"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["Really redZone"]:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["green"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.CamoZone:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["yellow"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["New YellerZone"]:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["magenta"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.MagentaZone:WaitForChild("Quest").Cloud.Part1.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
	end)
	script.Parent.Quests.Target.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(2)
		wait(0.1)
		if Playerteam == teams["white"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.WhiteZone:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["black"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.BlackZone:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["blue"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["Really blueZone"]:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["red"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["Really redZone"]:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["green"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.CamoZone:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["yellow"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["New YellerZone"]:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["magenta"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.MagentaZone:WaitForChild("Quest").Target:FindFirstChild("Part").CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
	end)
	script.Parent.Quests.Soccer.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(8)
		wait(0.1)
	end)
	script.Parent.Quests.Ramp.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(3)
		wait(0.1)
		if Playerteam == teams["white"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712WHITE") then
				workspace:FindFirstChild("356a192b7913b04c545712WHITE"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(-48.353508, 73.815239, -222.006744)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712WHITE"
			hrp.CFrame = part.CFrame
			hrp.CFrame = workspace:FindFirstChild("356a192b7913b04c545712WHITE")
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["black"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712BLACK") then
				workspace:FindFirstChild("356a192b7913b04c545712BLACK"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(-205.465546, 73.815239, -77.3190384)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712BLACK"
			hrp.CFrame = part.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["blue"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712BLACK") then
				workspace:FindFirstChild("356a192b7913b04c545712BLACK"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(98.334198, 73.815239, 294.705383)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712BLACK"
			hrp.CFrame = part.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["red"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712RED") then
				workspace:FindFirstChild("356a192b7913b04c545712RED"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(98.334198, 73.815239, -63.4945984)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712RED"
			hrp.CFrame = part.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["green"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712GREEN") then
				workspace:FindFirstChild("356a192b7913b04c545712GREEN"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(-205.465546, 73.815239, 280.680969)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712GREEN"
			hrp.CFrame = part.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["yellow"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712YELLOW") then
				workspace:FindFirstChild("356a192b7913b04c545712YELLOW"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(-205.465546, 73.815239, 638.68103)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712YELLOW"
			hrp.CFrame = part.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["magenta"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			if workspace:FindFirstChild("356a192b7913b04c545712MAGENTA") then
				workspace:FindFirstChild("356a192b7913b04c545712MAGENTA"):Destroy()
			end
			local part = Instance.new("Part")
			part.Parent = workspace
			part.Position = Vector3.new(98.334137, 73.815239, 652.905396)
			part.Anchored = true
			part.Size = Vector3.new(10, 10, 10)
			part.CanCollide = false
			part.Transparency = 0.7
			part.Name = "356a192b7913b04c545712MAGENTA"
			hrp.CFrame = part.CFrame
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
	end)
	script.Parent.Quests.FindMe.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(4)
		wait(0.1)
		if Playerteam == teams["white"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.WhiteZone:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace.WhiteZone:WaitForChild("Quest").Butter.PPart == nil
		end
		if Playerteam == teams["black"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.BlackZone:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace.BlackZone:WaitForChild("Quest").Butter.PPart == nil
		end
		if Playerteam == teams["blue"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace["Really blueZone"]:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace["Really blueZone"]:WaitForChild("Quest").Butter.PPart == nil
		end
		if Playerteam == teams["red"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace["Really redZone"]:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace["Really redZone"]:WaitForChild("Quest").Butter.PPart == nil
		end
		if Playerteam == teams["green"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.CamoZone:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace.CamoZone:WaitForChild("Quest").Butter.PPart == nil
		end
		if Playerteam == teams["yellow"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace["New YellerZone"]:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace["New YellerZone"]:WaitForChild("Quest").Butter.PPart == nil
		end
		if Playerteam == teams["magenta"] then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.MagentaZone:WaitForChild("Quest").Butter.PPart.CFrame + Vector3.new(0, 5, 0)
				hrp.Anchored = true
				wait(0.1)
				hrp.Anchored = false
			until workspace.MagentaZone:WaitForChild("Quest").Butter.PPart == nil
		end
	end)
	script.Parent.Quests.Dragon.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(5)
		wait(0.1)
		if Playerteam == teams["white"] then
			workspace.WhiteZone.VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.WhiteZone.Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace.WhiteZone.Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["black"] then
			workspace.WhiteZone.VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.BlackZone.Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace.BlackZone.Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["blue"] then
			workspace["Really blueZone"].VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["Really blueZone"]:WaitForChild("Quest").Cloud.Part1.CFrame
			repeat
				hrp.CFrame = workspace["Really blueZone"].Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace["Really blueZone"].Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["red"] then
			workspace["Really redZone"].VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace["Really redZone"].Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace["Really redZone"].Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["green"] then
			workspace.CamoZone.VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace.CamoZone:WaitForChild("Quest").Cloud.Part1.CFrame
			repeat
				hrp.CFrame = workspace.CamoZone.Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace.CamoZone.Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["yellow"] then
			workspace["New YellerZone"].VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			hrp.CFrame = workspace["New YellerZone"]:WaitForChild("Quest").Cloud.Part1.CFrame
			repeat
				hrp.CFrame = workspace["New YellerZone"].Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace["New YellerZone"].Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
		if Playerteam == teams["magenta"] then
			workspace.MagentaZone.VoteLaunchRE:FireServer()
			wait(0.25)
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(0.05)
			repeat
				hrp.CFrame = workspace.MagentaZone.Quest.Dragon.HumanoidRootPart.CFrame
				local args = {
					[1] = true
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
				wait(0)
				local args = {
					[1] = false
				}
				game:GetService("Players").LocalPlayer.Character.Cutlass.ThrustEvent:FireServer(unpack(args))
			until workspace.MagentaZone.Quest.Dragon.Humanoid.Health == 0
			wait(0.1)
			hrp.CFrame = workspace.BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		end
	end)
	script.Parent.Quests.TheBox.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		workspace.ClearAllPlayersBoatParts:FireServer()
		wait(0.5)
		workspace.QuestMakerEvent:FireServer(6)
		wait(0.1)
		if Playerteam == teams["white"] then
			workspace.WhiteZone.VoteLaunchRE:FireServer()
		end
		if Playerteam == teams["black"] then
			workspace.WhiteZone.VoteLaunchRE:FireServer()
		end
		if Playerteam == teams["blue"] then
			workspace["Really blueZone"].VoteLaunchRE:FireServer()
		end
		if Playerteam == teams["red"] then
			workspace["Really redZone"].VoteLaunchRE:FireServer()
		end
		if Playerteam == teams["green"] then
			workspace.CamoZone.VoteLaunchRE:FireServer()
		end
		if Playerteam == teams["yellow"] then
			workspace["New YellerZone"].VoteLaunchRE:FireServer()
		end
		if Playerteam == teams["magenta"] then
			workspace.MagentaZone.VoteLaunchRE:FireServer()
		end
		wait(0.25)
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		local Aanchor = 0.75
		local Banchor = 1.35 
		local Canchor = 0 
		local stagescounter = 1
		local stages = {game.Workspace.BoatStages.NormalStages.CaveStage1.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage2.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage3.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage4.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage5.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage6.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage7.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage8.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage9.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage10.StonePart.CFrame}
		if workspace:FindFirstChild("356a192b7913b04c5457") then
			workspace:FindFirstChild("356a192b7913b04c5457"):Destroy()
		end
		local part = Instance.new("Part")
		part.Parent = workspace
		part.Position = Vector3.new(76, -7, 1212)
		part.Anchored = true
		part.Size = Vector3.new(10, 10, 10)
		part.CanCollide = false
		part.Transparency = 0.7
		part.Name = "356a192b7913b04c5457"
		hrp.CFrame = part.CFrame
		wait(Aanchor)
		hrp.Anchored = true
		wait(Banchor)
		hrp.Anchored = false
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(Canchor)
		repeat
			hrp.CFrame = stages[stagescounter] + Vector3.new(0, 0, 50)
			wait(Aanchor)
			hrp.Anchored = true
			wait(Banchor)
			hrp.Anchored = false
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			wait(Canchor)
			stagescounter += 1
		until stagescounter == 10
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.GoldenChest.Trigger.CFrame
	end)
	script.Parent.Quests.ThinIce.MouseButton1Click:Connect(function()
		local Playerteam = game.Players.LocalPlayer.Team
		local teams = game:GetService("Teams")
		wait(0.1)
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		local Aanchor = 0.75
		local Banchor = 2.35
		local Canchor = 0 
		local stagescounter = 1
		local stages = {game.Workspace.BoatStages.NormalStages.CaveStage1.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage2.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage3.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage4.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage5.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage6.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage7.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage8.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage9.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage10.StonePart.CFrame}
		if workspace:FindFirstChild("356a192b7913b04c5457") then
			workspace:FindFirstChild("356a192b7913b04c5457"):Destroy()
		end
		local part = Instance.new("Part")
		part.Parent = workspace
		part.Position = Vector3.new(76, -7, 1212)
		part.Anchored = true
		part.Size = Vector3.new(10, 10, 10)
		part.CanCollide = false
		part.Transparency = 0.7
		part.Name = "356a192b7913b04c5457"
		hrp.CFrame = part.CFrame
		wait(Aanchor)
		hrp.Anchored = true
		wait(Banchor)
		hrp.Anchored = false
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(Canchor)
		repeat
			hrp.CFrame = stages[stagescounter] + Vector3.new(0, 0, 50)
			wait(Aanchor)
			hrp.Anchored = true
			wait(Banchor)
			hrp.Anchored = false
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			wait(Canchor)
			stagescounter += 1
		until stagescounter == 10
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
	end)
end
coroutine.wrap(OODD_script)()
local function XKVEUN_script() -- MainFrame.TelleportsButtonOpenCloseScript 
	local script = Instance.new('LocalScript', MainFrame)

	script.Parent.TeleportButton.MouseButton1Click:Connect(function()
		if script.Parent.TelleportsFrame.Visible == true then
			script.Parent.TelleportsFrame.Visible = false
		else
			script.Parent.TelleportsFrame.Visible = true
			script.Parent.AutoFarmFrame.Visible = false
			script.Parent.QuestsFrame.Visible = false
			script.Parent.AutoBuyFrame.Visible = false
		end
	end)
end
coroutine.wrap(XKVEUN_script)()
local function AJATKY_script() -- MainFrame.DragScript 
	local script = Instance.new('LocalScript', MainFrame)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(AJATKY_script)()
local function DCWBK_script() -- AutoFarmButtonOffOnV1.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonOffOnV1)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(DCWBK_script)()
local function YDNL_script() -- AutoFarmButtonSettingsResetVelocityOffOn.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsResetVelocityOffOn)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(YDNL_script)()
local function OQFUNE_script() -- AutoFarmButtonSettingsCollectchestOffOn.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsCollectchestOffOn)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(OQFUNE_script)()
local function CMYTPWA_script() -- AutoFarmButtonSettingsGetGoldOffOn.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsGetGoldOffOn)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(CMYTPWA_script)()
local function XNEUFLM_script() -- AutoFarmButtonSettingsGetGoldOffOn.GetGoldAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsGetGoldOffOn)

	while wait(0.1) do
		if script.Parent.BackgroundColor3 == Color3.fromRGB(0, 255, 0) then
			workspace.ClaimRiverResultsGold:FireServer()
		end
	end
end
coroutine.wrap(XNEUFLM_script)()
local function JILTYM_script() -- AutoFarmV1.AutoFarmSciptGettingSettingsAndOffOnV1 
	local script = Instance.new('LocalScript', AutoFarmV1)

	function autofarmV1()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild("HumanoidRootPart")
		local humanoid = game.Players.LocalPlayer.Character.Humanoid
		local Aanchor = 0.75
		local Banchor = 1.35 
		local Canchor = 0 
		local stagescounter = 1
		local chestCollecting = true
		local resetvelocity = true
		if script.Parent.settings.AutoFarmButtonSettingsCollectchestOffOn.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			chestCollecting = false
		else
			chestCollecting = true
		end
		if script.Parent.settings.AutoFarmButtonSettingsResetVelocityOffOn.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			resetvelocity = false
		else
			resetvelocity = true
		end
		local stages = {game.Workspace.BoatStages.NormalStages.CaveStage1.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage2.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage3.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage4.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage5.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage6.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage7.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage8.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage9.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage10.StonePart.CFrame}
		if workspace:FindFirstChild("356a192b7913b04c5457") then
			workspace:FindFirstChild("356a192b7913b04c5457"):Destroy()
		end
		local part = Instance.new("Part")
		part.Parent = workspace
		part.Position = Vector3.new(76, -7, 1212)
		part.Anchored = true
		part.Size = Vector3.new(10, 10, 10)
		part.CanCollide = false
		part.Transparency = 0.7
		part.Name = "356a192b7913b04c5457"
		hrp.CFrame = part.CFrame
		wait(Aanchor)
		hrp.Anchored = true
		wait(Banchor)
		hrp.Anchored = false
		if humanoid.Health == 0 then
			return
		end
		if resetvelocity == true then
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			wait(Canchor)
		end
		repeat
			if humanoid.Health == 0 then
				return
			end
			if script.Parent.settings.AutoFarmButtonSettingsResetVelocityOffOn.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
				resetvelocity = false
			else
				resetvelocity = true
			end
			hrp.CFrame = stages[stagescounter] + Vector3.new(0, 0, 50)
			wait(Aanchor)
			hrp.Anchored = true
			wait(Banchor)
			hrp.Anchored = false
			if resetvelocity == true then
				hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
				wait(Canchor)
			end
			stagescounter += 1
			if stagescounter == 2 then
				if script.Parent.settings.AutoFarmButtonSettingsCollectchestOffOn.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
					chestCollecting = false
				else
					chestCollecting = true
				end
				if chestCollecting == true then
					hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.GoldenChest.Trigger.CFrame
				end
				wait(1)
			end
			if script.Parent.AutoFarmButtonOffOnV1.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
				return
			end
		until stagescounter == 10
		if script.Parent.settings.AutoFarmButtonSettingsCollectchestOffOn.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			chestCollecting = false
		else
			chestCollecting = true
		end
		if chestCollecting == true then
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.GoldenChest.Trigger.CFrame
			wait(17)
		end
		humanoid.Health = 0
	end
	game.Players.LocalPlayer.CharacterAdded:Connect(function()
		repeat
			wait(0)
		until game.Players.LocalPlayer.Character
		wait(3)
		if script.Parent.AutoFarmButtonOffOnV1.BackgroundColor3 == Color3.fromRGB(0, 255, 0) then
			autofarmV1()
		end
	end)
	script.Parent.AutoFarmButtonOffOnV1.MouseButton1Click:Connect(function()
		if script.Parent.AutoFarmButtonOffOnV1.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			game.Players.LocalPlayer.Character.Humanoid.Health = 0
		end
	end)
end
coroutine.wrap(JILTYM_script)()
local function FJYQ_script() -- AutoFarmCandyButtonOffOn.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmCandyButtonOffOn)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(FJYQ_script)()
local function FMZOZXD_script() -- AutoFarmCandyV1.AutoFarmSciptGettingSettingsAndOffOn 
	local script = Instance.new('LocalScript', AutoFarmCandyV1)

	while wait(0.1) do
		if script.Parent.AutoFarmCandyButtonOffOn.BackgroundColor3 == Color3.fromRGB(0, 255, 0) then
			local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
			if workspace.Houses:FindFirstChild("TrickOrTreatHouse") then
				hrp.Anchored = false
				hrp.CFrame = workspace.Houses:FindFirstChild("TrickOrTreatHouse"):WaitForChild("Door"):WaitForChild("DoorInnerTouch").CFrame
			else
				hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
			end
		end
	end
end
coroutine.wrap(FMZOZXD_script)()
local function UKECA_script() -- AutoFarmButtonOffOnV2.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonOffOnV2)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(UKECA_script)()
local function NJFSKM_script() -- AutoFarmButtonSettingsCollectchestOffOn_2.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsCollectchestOffOn_2)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(NJFSKM_script)()
local function WSETZG_script() -- AutoFarmButtonSettingsGetGoldOffOn_2.ChangeColorAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsGetGoldOffOn_2)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			script.Parent.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
		else
			script.Parent.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
		end
	end)
end
coroutine.wrap(WSETZG_script)()
local function IGADITM_script() -- AutoFarmButtonSettingsGetGoldOffOn_2.GetGoldAutoFarmV1 
	local script = Instance.new('LocalScript', AutoFarmButtonSettingsGetGoldOffOn_2)

	while wait(0.1) do
		if script.Parent.BackgroundColor3 == Color3.fromRGB(0, 255, 0) then
			workspace.ClaimRiverResultsGold:FireServer()
		end
	end
end
coroutine.wrap(IGADITM_script)()
local function EUAOTE_script() -- AutoFarmV2.AutoFarmSciptGettingSettingsAndOffOnV2 
	local script = Instance.new('LocalScript', AutoFarmV2)

	function autofarmV2()
		local tweenService = game:GetService("TweenService")
		game.workspace.Gravity = 0
		game.Players.LocalPlayer.Character:WaitForChild("HumanoidRootPart").CFrame = CFrame.new(-51, 80, -536)
		local tweenInfo = TweenInfo.new(30, Enum.EasingStyle.Linear)
		local tween =
			tweenService:Create(
				game:GetService("Players")["LocalPlayer"].Character:WaitForChild("HumanoidRootPart"),
				tweenInfo,
				{CFrame = CFrame.new(-60, 53, 8666)}
			)
		tween:Play()
		wait(30)
		if script.Parent.settings.AutoFarmButtonSettingsCollectchestOffOn.BackgroundColor3 == Color3.new(0, 1, 0) then
			tweenService, tweenInfo = game:GetService("TweenService"), TweenInfo.new(0, Enum.EasingStyle.Linear)
			tween =
				tweenService:Create(
					game:GetService("Players")["LocalPlayer"].Character:WaitForChild("HumanoidRootPart"),
					tweenInfo,
					{CFrame = CFrame.new(-55, -360, 9489)}
				)
			tween:Play()
		end
		game.workspace.Gravity = 196.2
	end
	game.Players.LocalPlayer.CharacterAdded:Connect(function()
		repeat
			wait(0)
		until game.Players.LocalPlayer.Character
		wait(3)
		if script.Parent.AutoFarmButtonOffOnV2.BackgroundColor3 == Color3.fromRGB(0, 255, 0) then
			autofarmV2()
		end
	end)
	script.Parent.AutoFarmButtonOffOnV2.MouseButton1Click:Connect(function()
		if script.Parent.AutoFarmButtonOffOnV2.BackgroundColor3 == Color3.fromRGB(255, 0, 0) then
			game.Players.LocalPlayer.Character.Humanoid.Health = 0
		end
	end)
end
coroutine.wrap(EUAOTE_script)()
local function CUMGNME_script() -- MainFrame.AutoFarmButtonOpenCloseScript 
	local script = Instance.new('LocalScript', MainFrame)

	script.Parent.AutoFarmButton.MouseButton1Click:Connect(function()
		if script.Parent.AutoFarmFrame.Visible == true then
			script.Parent.AutoFarmFrame.Visible = false
		else
			script.Parent.AutoFarmFrame.Visible = true
			script.Parent.TelleportsFrame.Visible = false
			script.Parent.QuestsFrame.Visible = false
			script.Parent.AutoBuyFrame.Visible = false
		end
	end)
end
coroutine.wrap(CUMGNME_script)()
local function OOJHT_script() -- StagesV1.TelleportStages 
	local script = Instance.new('LocalScript', StagesV1)

	local stages = {game.Workspace.BoatStages.NormalStages.CaveStage1.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage2.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage3.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage4.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage5.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage6.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage7.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage8.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage9.StonePart.CFrame, game.Workspace.BoatStages.NormalStages.CaveStage10.StonePart.CFrame}
	script.Parent.Stage1.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[1] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage2.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[2] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage3.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[3] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage4.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[4] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage5.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[5] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage6.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[6] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage7.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[7] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage8.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[8] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage9.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[9] + Vector3.new(0, 0, 50)
	end)
	script.Parent.Stage10.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
		wait(0.05)
		hrp.CFrame = stages[10] + Vector3.new(0, 0, 50)
	end)
	script.Parent.endstage.MouseButton1Click:Connect(function()
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame + Vector3.new(0, 10, 0)
	end)
end
coroutine.wrap(OOJHT_script)()
local function DQFLCE_script() -- TeamsV1.TelleportsScript 
	local script = Instance.new('LocalScript', TeamsV1)

	while wait(0.1) do
		local hrp = game.Players.LocalPlayer.Character:WaitForChild('HumanoidRootPart')
		script.Parent.White.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams.WhiteTeam.Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
		script.Parent.Blue.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams["Really blueTeam"].Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
		script.Parent.Green.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams.CamoTeam.Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
		script.Parent.Red.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams["Really redTeam"].Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
		script.Parent.Black.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams.BlackTeam.Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
		script.Parent.Yellow.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams["New YellerTeam"].Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
		script.Parent.Magenta.MouseButton1Click:Connect(function()
			hrp.Anchored = true
			hrp.CFrame = game:GetService("Workspace").BoatStages.NormalStages.TheEnd.WaterSand.CFrame
			hrp.Anchored = false
			wait(0.1)
			hrp.CFrame = game:GetService("Workspace").Teams.MagentaTeam.Baseplate.CFrame + Vector3.new(0, 15, 0)
		end)
	end
end
coroutine.wrap(DQFLCE_script)()
local function AKVDESU_script() -- MainFrame.QuestsButtonOpenCloseScript 
	local script = Instance.new('LocalScript', MainFrame)

	script.Parent.QuestsButton.MouseButton1Click:Connect(function()
		if script.Parent.QuestsFrame.Visible == true then
			script.Parent.QuestsFrame.Visible = false
		else
			script.Parent.QuestsFrame.Visible = true
			script.Parent.AutoFarmFrame.Visible = false
			script.Parent.TelleportsFrame.Visible = false
			script.Parent.AutoBuyFrame.Visible = false
		end
	end)
end
coroutine.wrap(AKVDESU_script)()
local function IWYXWO_script() -- ChestsV1.ChangeColor 
	local script = Instance.new('LocalScript', ChestsV1)

	script.Parent.Cammon.MouseButton1Click:Connect(function()
		if script.Parent.Cammon.BackgroundColor3 == Color3.new(1, 0, 0) then
			script.Parent.Cammon.BackgroundColor3 = Color3.new(0, 1, 0)
		else
			script.Parent.Cammon.BackgroundColor3 = Color3.new(1, 0, 0)
		end
	end)
	script.Parent.Uncammon.MouseButton1Click:Connect(function()
		if script.Parent.Uncammon.BackgroundColor3 == Color3.new(0.803922, 0, 0) then
			script.Parent.Uncammon.BackgroundColor3 = Color3.new(0, 0.803922, 0)
		else
			script.Parent.Uncammon.BackgroundColor3 = Color3.new(0.803922, 0, 0)
		end
	end)
	script.Parent.Rare.MouseButton1Click:Connect(function()
		if script.Parent.Rare.BackgroundColor3 == Color3.new(1, 0, 0) then
			script.Parent.Rare.BackgroundColor3 = Color3.new(0, 1, 0)
		else
			script.Parent.Rare.BackgroundColor3 = Color3.new(1, 0, 0)
		end
	end)
	script.Parent.Epic.MouseButton1Click:Connect(function()
		if script.Parent.Epic.BackgroundColor3 == Color3.new(0.803922, 0, 0) then
			script.Parent.Epic.BackgroundColor3 = Color3.new(0, 0.803922, 0)
		else
			script.Parent.Epic.BackgroundColor3 = Color3.new(0.803922, 0, 0)
		end
	end)
	script.Parent.Legendary.MouseButton1Click:Connect(function()
		if script.Parent.Legendary.BackgroundColor3 == Color3.new(1, 0, 0) then
			script.Parent.Legendary.BackgroundColor3 = Color3.new(0, 1, 0)
		else
			script.Parent.Legendary.BackgroundColor3 = Color3.new(1, 0, 0)
		end
	end)
end
coroutine.wrap(IWYXWO_script)()
local function JMYKP_script() -- ChestsV1.OpenScript 
	local script = Instance.new('LocalScript', ChestsV1)

	while wait(1) do
		local count = 1
		if script.Parent.Cammon.BackgroundColor3 == Color3.new(0, 1, 0) then
			local args = {
				[1] = "Common Chest",
				[2] = count
			}
			workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
		end
		if script.Parent.Uncammon.BackgroundColor3 == Color3.new(0, 0.803922, 0) then
			local args = {
				[1] = "Uncommon Chest",
				[2] = count
			}
			workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
		end
		if script.Parent.Rare.BackgroundColor3 == Color3.new(0, 1, 0) then
			local args = {
				[1] = "Rare Chest",
				[2] = count
			}
			workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
		end
		if script.Parent.Epic.BackgroundColor3 == Color3.new(0, 0.803922, 0) then
			local args = {
				[1] = "Epic Chest",
				[2] = count
			}
			workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
		end
		if script.Parent.Legendary.BackgroundColor3 == Color3.new(0, 1, 0) then
			local args = {
				[1] = "Legendary Chest",
				[2] = count
			}
			workspace.ItemBoughtFromShop:InvokeServer(unpack(args))
		end
	end
end
coroutine.wrap(JMYKP_script)()
local function LTEVAER_script() -- MainFrame.AutoBuyButtonOpenCloseScript 
	local script = Instance.new('LocalScript', MainFrame)

	script.Parent.AutoBuyButton.MouseButton1Click:Connect(function()
		if script.Parent.AutoBuyFrame.Visible == true then
			script.Parent.AutoBuyFrame.Visible = false
		else
			script.Parent.AutoBuyFrame.Visible = true
			script.Parent.AutoFarmFrame.Visible = false
			script.Parent.QuestsFrame.Visible = false
			script.Parent.TelleportsFrame.Visible = false
		end
	end)
end
coroutine.wrap(LTEVAER_script)()
local function NRDAZQ_script() -- OpenMainFrame.DragScript 
	local script = Instance.new('LocalScript', OpenMainFrame)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(NRDAZQ_script)()
local function CMYBTJT_script() -- Reversal.OpenClosemainFrameUseingOpenMainFrame 
	local script = Instance.new('LocalScript', Reversal)

	script.Parent.OpenMainFrame.MouseButton1Click:Connect(function()
		if script.Parent.MainFrame.Visible == false then
			script.Parent.MainFrame.Visible = true
		else
			script.Parent.MainFrame.Visible = false
		end
	end)
end
coroutine.wrap(CMYBTJT_script)()
