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
