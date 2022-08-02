creating the ui library
```
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/laagginq/ui-libraries/main/coastified/src.lua"))()
local Window = Lib:Window("ui lib", "Name", Enum.KeyCode.RightShift)
local Test = Window:Tab("Tab1")
```

making the Button
```
Test:Button('Enabled',function()
    print("ayyy")
end)
```
making the toggle
```
Test:Toggle('Enabled',function(state)
    print(state)
end)
```
making the sliders
```
Test:Slider('Fov Size',1,200,75,function(Value)
    print(Value)
end)
```
making the color picker
```
Test:Colorpicker("Color",Color3.fromRGB(0,0,0), function(color)
    print(color)
end)
```
making the dropdown
```
Test:Dropdown("Part",{'Head',"UpperTorso","HumanoidRootPart","LowerTorso"}, function(objective)
    print(objective)
end)
```
making the label
```
local Test = Window:Tab("Fov Set")
```
