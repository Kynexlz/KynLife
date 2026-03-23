# KynLife
KynLife UI Hub

Library
```lua
local UI = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kynexlz/KynLife/refs/heads/main/Source"))()
```

Setup a Title
```lua
UI:SetTitle("Title of your library")
```

Choose your own Colour
```lua
UI:SetTheme(
    Color3.fromRGB(15,15,15), -- background
    Color3.fromRGB(255,255,255) -- accent
)
```

Create a Tab
```lua
local main = UI:CreateTab("Main")
local player = UI:CreateTab("Player")
local misc = UI:CreateTab("Misc")
```

Create a Button
```lua
main:Button("Button Name", function()
    print("Button clicked")
end)
```

Create a Toggle
```lua
main:Toggle("Toggle Name", function(state)
    print(state) -- true / false
end)
```

Create a Slider
```lua
main:Slider("Slider Name", MIN, MAX, function(value)
    print(value)
end)
```









