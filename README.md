# KynLife
KynLife UI Hub

Library
```lua
local UI = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kynexlz/KynLife/refs/heads/main/KynLifeSource"))()
```

Choose your own Colour
```lua
UI:SetTheme(Color3.fromRGB(15,15,15), Color3.fromRGB(255,255,255))
```

Setup a Title
```lua
UI:SetTitle("Title of your library")
```

Create a Button
```lua
UI:Button("Button Name", function()
    print("Clicked!")
end)
```

Create a Toggle
```lua
UI:Toggle("Toggle Name", function(v)
    print("Toggle:", v)
end)
```

Create a Slider
```lua
UI:Slider("Speed", 1, 100, function(v)
    print("Speed:", v)
end)
```
