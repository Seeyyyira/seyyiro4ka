<p align="center">
    <img src="https://media.tenor.com/ojPOglrv2AEAAAAM/ahegao.gif" alt="Ahegao" width="500">
</p>
# Ahegao by Razy.#0139
redacted by seeyira 

# Library core
first we have to add a loadstring for library usage

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Seeyyyira/seyyiro4ka/main/Ahegao.lua"))()
```


# Creating a window

```lua
Window = Library.Main("Your Text","LeftAlt") -- change "LeftAlt" to key that you want will hide gui
```

# Adding Tab
```lua
local Tab = Window.NewTab("Your Tab Text")
```
# Adding Section
```lua
local Section = Tab.NewSection("Section Text")
```

# Adding Button 
```lua
local Button = Section.NewButton("Button Text",function()
  print("yo")
end)
```

# Adding Toggles
```lua
--//Toggles
local EnabledToggle = Section.NewToggle("Enabled Toggle",function(bool)
-- code here
end,true) -- "true" is the default value of toggle

local DisabledToggle = Section.NewToggle("Disabled Toggle",function(bool)
-- code here
end,false) -- "false" is the default value of toggle
```

# Adding Sliders

```lua
local SliderPrecise = section.NewSlider("Slider precise",0,100,true,function(value)

end,25)
local SliderNotPrecise = section.NewSlider("Slider not precise",0,100,false,function(value)

end,75)
```
