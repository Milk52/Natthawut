-- Gui to Lua
-- Version: 3.2

-- Instances:

local TestUI = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Frame_2 = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Name = Instance.new("TextLabel")
local Name_2 = Instance.new("TextLabel")
local Frame_3 = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Bar = Instance.new("Frame")
local CircleBut = Instance.new("ImageLabel")
local UICorner_4 = Instance.new("UICorner")
local TextBut = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TestBut = Instance.new("TextButton")
local Frame_4 = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local Bar_2 = Instance.new("Frame")
local CircleBut_2 = Instance.new("ImageLabel")
local UICorner_7 = Instance.new("UICorner")
local TextBut_2 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TestBut_2 = Instance.new("TextButton")

--Properties:

TestUI.Name = "TestUI"
TestUI.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
TestUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = TestUI
Frame.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
Frame.Position = UDim2.new(0.0830636099, 0, 0.125208691, 0)
Frame.Size = UDim2.new(0, 588, 0, 427)

UICorner.CornerRadius = UDim.new(0, 5)
UICorner.Parent = Frame

Frame_2.Parent = TestUI
Frame_2.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Frame_2.Position = UDim2.new(0.0830636099, 0, 0.125208691, 0)
Frame_2.Size = UDim2.new(0, 196, 0, 427)

UICorner_2.CornerRadius = UDim.new(0, 5)
UICorner_2.Parent = Frame_2

Name.Name = "Name"
Name.Parent = Frame_2
Name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name.BackgroundTransparency = 1.000
Name.Position = UDim2.new(0.877674818, 0, 0.0344403014, 0)
Name.Size = UDim2.new(0, 15, 0, 18)
Name.Font = Enum.Font.GothamBlack
Name.Text = "TM"
Name.TextColor3 = Color3.fromRGB(85, 255, 0)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true

Name_2.Name = "Name"
Name_2.Parent = Frame_2
Name_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name_2.BackgroundTransparency = 1.000
Name_2.Position = UDim2.new(0.107266486, 0, 0.0344403014, 0)
Name_2.Size = UDim2.new(0, 152, 0, 30)
Name_2.Font = Enum.Font.GothamBlack
Name_2.Text = "MAKER HUB"
Name_2.TextColor3 = Color3.fromRGB(255, 255, 0)
Name_2.TextScaled = true
Name_2.TextSize = 14.000
Name_2.TextWrapped = true

Frame_3.Parent = TestUI
Frame_3.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Frame_3.Position = UDim2.new(0.30960086, 0, 0.154262632, 0)
Frame_3.Size = UDim2.new(0, 365, 0, 44)

UICorner_3.CornerRadius = UDim.new(0, 5)
UICorner_3.Parent = Frame_3

Bar.Name = "Bar"
Bar.Parent = Frame_3
Bar.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
Bar.BorderSizePixel = 0
Bar.Position = UDim2.new(0.843509555, 0, 0.275685579, 0)
Bar.Size = UDim2.new(0, 51, 0, 23)

CircleBut.Name = "CircleBut"
CircleBut.Parent = Bar
CircleBut.BackgroundColor3 = Color3.fromRGB(208, 208, 208)
CircleBut.Position = UDim2.new(0.509524941, 0, 0, 0)
CircleBut.Size = UDim2.new(0, 25, 0, 23)
CircleBut.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"
CircleBut.ImageTransparency = 1.000

UICorner_4.CornerRadius = UDim.new(0, 500)
UICorner_4.Parent = CircleBut

TextBut.Name = "TextBut"
TextBut.Parent = Bar
TextBut.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBut.BackgroundTransparency = 1.000
TextBut.Size = UDim2.new(0, 57, 0, 23)
TextBut.Font = Enum.Font.SourceSans
TextBut.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBut.TextScaled = true
TextBut.TextSize = 14.000
TextBut.TextTransparency = 1.000
TextBut.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 50)
UICorner_5.Parent = Bar

TestBut.Name = "TestBut"
TestBut.Parent = Bar
TestBut.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TestBut.BackgroundTransparency = 1.000
TestBut.Position = UDim2.new(-5.90586805, 0, -0.342914075, 0)
TestBut.Size = UDim2.new(0, 135, 0, 34)
TestBut.Font = Enum.Font.SourceSansSemibold
TestBut.Text = "AutoFarm Level"
TestBut.TextColor3 = Color3.fromRGB(214, 214, 214)
TestBut.TextScaled = true
TestBut.TextSize = 14.000
TestBut.TextWrapped = true

Frame_4.Parent = TestUI
Frame_4.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Frame_4.Position = UDim2.new(0.30960086, 0, 0.241219163, 0)
Frame_4.Size = UDim2.new(0, 365, 0, 44)

UICorner_6.CornerRadius = UDim.new(0, 5)
UICorner_6.Parent = Frame_4

Bar_2.Name = "Bar"
Bar_2.Parent = Frame_4
Bar_2.BackgroundColor3 = Color3.fromRGB(85, 255, 0)
Bar_2.BorderSizePixel = 0
Bar_2.Position = UDim2.new(0.843509555, 0, 0.275685579, 0)
Bar_2.Size = UDim2.new(0, 51, 0, 23)

CircleBut_2.Name = "CircleBut"
CircleBut_2.Parent = Bar_2
CircleBut_2.BackgroundColor3 = Color3.fromRGB(208, 208, 208)
CircleBut_2.Position = UDim2.new(0.509524941, 0, 0, 0)
CircleBut_2.Size = UDim2.new(0, 25, 0, 23)
CircleBut_2.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"
CircleBut_2.ImageTransparency = 1.000

UICorner_7.CornerRadius = UDim.new(0, 500)
UICorner_7.Parent = CircleBut_2

TextBut_2.Name = "TextBut"
TextBut_2.Parent = Bar_2
TextBut_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBut_2.BackgroundTransparency = 1.000
TextBut_2.Size = UDim2.new(0, 57, 0, 23)
TextBut_2.Font = Enum.Font.SourceSans
TextBut_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBut_2.TextScaled = true
TextBut_2.TextSize = 14.000
TextBut_2.TextTransparency = 1.000
TextBut_2.TextWrapped = true

UICorner_8.CornerRadius = UDim.new(0, 50)
UICorner_8.Parent = Bar_2

TestBut_2.Name = "TestBut"
TestBut_2.Parent = Bar_2
TestBut_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TestBut_2.BackgroundTransparency = 1.000
TestBut_2.Position = UDim2.new(-5.90586805, 0, -0.342914075, 0)
TestBut_2.Size = UDim2.new(0, 135, 0, 34)
TestBut_2.Font = Enum.Font.SourceSansSemibold
TestBut_2.Text = "AutoFarm Level"
TestBut_2.TextColor3 = Color3.fromRGB(214, 214, 214)
TestBut_2.TextScaled = true
TestBut_2.TextSize = 14.000
TestBut_2.TextWrapped = true

-- Scripts:

local function OSXKQW_fake_script() -- TextBut.NewLocalScript 
	local script = Instance.new('LocalScript', TextBut)

	local TS = game:GetService("TweenService")
	local circleBut = script.Parent.Parent.CircleBut
	local barF = script.Parent.Parent
	local tI1 = TweenInfo.new(0.5,Enum.EasingStyle.Circular,Enum.EasingDirection.Out)
	local tweenSettings1 = {
		Position = UDim2.new(-0.15, 0,-0.364, 0)
	}
	local tween1 = TS:Create(circleBut,tI1,tweenSettings1)
	local tI2 = TweenInfo.new(0.5,Enum.EasingStyle.Circular,Enum.EasingDirection.Out)
	local tweenSettings2 = {
		Position = UDim2.new(0.592, 0,-0.364, 0)
	}
	local tween2 = TS:Create(circleBut,tI2,tweenSettings2)
	local open = true
	
	function colorAnimate(frame,colorN)
		local tI3 = TweenInfo.new(0.5,Enum.EasingStyle.Circular,Enum.EasingDirection.Out)
		local tweenSettings3 = {
			BackgroundColor3 = colorN
		}
		local tween3 = TS:Create(frame,tI3,tweenSettings3)
		tween3:Play()
	end
	
	script.Parent.MouseButton1Click:Connect(function()
		if open == true then
			open = false
			colorAnimate(barF,Color3.fromRGB(255,0,0))
			tween1:Play()
			script.Parent.Parent.Parent.Parent.TestBut.Visible = false
		elseif open == false then
			open = true
			colorAnimate(barF,Color3.fromRGB(0,255,0))
			tween2:Play()
			script.Parent.Parent.Parent.Parent.TestBut.Visible = true
		end
	end)
end
coroutine.wrap(OSXKQW_fake_script)()
local function VWAE_fake_script() -- TextBut_2.NewLocalScript 
	local script = Instance.new('LocalScript', TextBut_2)

	local TS = game:GetService("TweenService")
	local circleBut = script.Parent.Parent.CircleBut
	local barF = script.Parent.Parent
	local tI1 = TweenInfo.new(0.5,Enum.EasingStyle.Circular,Enum.EasingDirection.Out)
	local tweenSettings1 = {
		Position = UDim2.new(-0.15, 0,-0.364, 0)
	}
	local tween1 = TS:Create(circleBut,tI1,tweenSettings1)
	local tI2 = TweenInfo.new(0.5,Enum.EasingStyle.Circular,Enum.EasingDirection.Out)
	local tweenSettings2 = {
		Position = UDim2.new(0.592, 0,-0.364, 0)
	}
	local tween2 = TS:Create(circleBut,tI2,tweenSettings2)
	local open = true
	
	function colorAnimate(frame,colorN)
		local tI3 = TweenInfo.new(0.5,Enum.EasingStyle.Circular,Enum.EasingDirection.Out)
		local tweenSettings3 = {
			BackgroundColor3 = colorN
		}
		local tween3 = TS:Create(frame,tI3,tweenSettings3)
		tween3:Play()
	end
	
	script.Parent.MouseButton1Click:Connect(function()
		if open == true then
			open = false
			colorAnimate(barF,Color3.fromRGB(255,0,0))
			tween1:Play()
			script.Parent.Parent.Parent.Parent.TestBut.Visible = false
		elseif open == false then
			open = true
			colorAnimate(barF,Color3.fromRGB(0,255,0))
			tween2:Play()
			script.Parent.Parent.Parent.Parent.TestBut.Visible = true
		end
	end)
end
coroutine.wrap(VWAE_fake_script)()
