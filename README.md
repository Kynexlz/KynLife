# Kynexlz Hub

Library
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kynexlz/KynLife/refs/heads/main/Source"))()
```

Create a Title
```lua
local Window = Library:CreateWindow("Kynexlz Hub", "Made by you")

--[[
"Kynexlz Hub" = Title
"Made by You" = small hover text (optional)
]]
```

Create a Tab
```lua
local MainPage = Window:addPage("Main", 4, true, 6)

--[[
"Main" = Tab name
"4" = scroll size
"true/false" = default open tab
"6" = spacing between elements
]]
```

Create a Label
```lua
MainPage:addLabel("Label")

--[[
"Label" = Label name
]]
```

Create a Button
```lua
MainPage:addButton("Button", function()
    print("Button clicked")
end)

--[[
"Button" = Button name
]]
```

Create a Toggle
```lua
MainPage:addToggle("Toggle", function(state)
    print("Toggle:", state)
end)

--[[
"Toggle" = Toggle name
]]
```

Create a Slider
```lua
MainPage:addSlider("Slider", 0, 100, function(value)
    print("Speed:", value)
end)

--[[
"Slider" = Slider name
"0, 100," = Speed amount
]]
```

Create a Textbox
```lua
MainPage:addTextBox("Textbox", "Type...", function(text)
    print("User typed:", text)
end)

--[[
"Textbox" = Textbox name
]]
```

Create a Dropdown
```lua
MainPage:addDropdown("Dropdown", {"Option 1","Option 2","Option 3"}, 4, function(option)
    print("Selected:", option)
end)

--[[
"Dropdown" = Dropdown name
"Options" = Name it to whatever you want
]]
```
