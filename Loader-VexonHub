loadstring(game:HttpGet("https://api.jnkie.com/api/v1/luascripts/public/9349e983c94d3c5ae3db3bfeb6cf52aa9a02bcf234202f537b9af0347c2318d5/download"))()

local StarterGui = game:GetService("StarterGui")
local bindable = Instance.new("BindableFunction")

bindable.OnInvoke = function(buttonText)
    if buttonText == "Copy Link" then
        if setclipboard then
            setclipboard("https://discord.gg/vexon")
        else
        end
    end
end

StarterGui:SetCore("SendNotification", {
    Title = "VexonHub",
    Text = "VexonHub Server is back! Do you wanna join it?",
    Icon = "rbxassetid://84519376661277",
    Duration = 120,
    Button1 = "Copy Link",
    Button2 = "Not Now",
    Callback = bindable
})
