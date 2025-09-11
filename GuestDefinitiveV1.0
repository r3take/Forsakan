-- Guest Definitive V1.0
loadstring(game:HttpGet("https://raw.githubusercontent.com/skibidi399/Auto-gen-and-esp/refs/heads/main/Script"))()

game.StarterGui:SetCore("SendNotification", {
    Title = "Heads up!";
    Text = "You need to customize the auto-gen and esp! A button will pop up in the middle of your screen shortly after you're done.";
    Duration = 20;
})
wait(1)
game.StarterGui:SetCore("SendNotification", {
    Title = "Remember!";
    Text = "Move the Generator UI to access the button.";
    Duration = 20;
})

local player = game.Players.LocalPlayer
local gui = Instance.new("ScreenGui")
gui.Parent = player:WaitForChild("PlayerGui")

local button = Instance.new("TextButton")
button.Size = UDim2.new(0, 200, 0, 50)
button.Position = UDim2.new(0.5, -100, 0.5, -25)
button.Text = "Load Rest"
button.Parent = gui

button.MouseButton1Click:Connect(function()
    button:Destroy()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/skibidi399/Auto-block-script/refs/heads/main/FINAL%20AUTO%20BLOCK"))()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Altairkaaa/c00l/refs/heads/main/c00lguiv1.lua"))()

    task.wait(5)

    game.StarterGui:SetCore("SendNotification", {
        Title = "Credits";
        Text = "Skibi, Altair";
        Duration = 5;
    })
end)
