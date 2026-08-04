-- This file was generated with SKS V1.2.0

local fenv = getfenv();
pcall(function(p1, a, b, c)

end);
writefile(
    "po.mp3",
    game:HttpGet("https://raw.githubusercontent.com/ipadys/core/refs/heads/main/audio_2025-12-04_15-22-47.mp3")
);
local Sound = Instance.new"Sound";
Sound.Parent = workspace;
Sound.SoundId = fenv.getcustomasset"po.mp3";
Sound.Volume = 10;
Sound.Looped = true;
Sound:Play();
writefile(
    "dsf.jpg",
    game:HttpGet("https://raw.githubusercontent.com/ipadys/core/refs/heads/main/photo_2025-12-03_21-03-11.jpg")
);
local ScreenGui = Instance.new"ScreenGui";
ScreenGui.DisplayOrder = 999;
ScreenGui.Parent = game.Players.LocalPlayer.PlayerGui;
local ImageLabel = Instance.new"ImageLabel";
ImageLabel.Image = fenv.getcustomasset"dsf.jpg";
local UDim2_New = UDim2.new;
ImageLabel.Size = UDim2_New(0, 600, 0, 600);
ImageLabel.BackgroundTransparency = 1;
ImageLabel.Position = UDim2_New(0.5, 0, 0.5, 0);
local Vector2_New = Vector2.new;
ImageLabel.AnchorPoint = Vector2_New(0.5, 0.5);
ImageLabel.Parent = ScreenGui;
local TextLabel = Instance.new"TextLabel";
TextLabel.Text = "script made by erm_iPad! body_f3 on discord";
TextLabel.TextScaled = true;
TextLabel.Size = UDim2_New(0, 200, 0, 100);
TextLabel.TextColor3 = Color3.new(1, 1, 1);
TextLabel.BackgroundTransparency = 1;
TextLabel.Position = UDim2_New(0.5, 0, 0.5, 0);
TextLabel.AnchorPoint = Vector2_New(0.5, 0.5);
TextLabel.ZIndex = 999;
TextLabel.Parent = ScreenGui;
