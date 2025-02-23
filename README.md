# somewhat-of-an-vapev4
me, covron, searching for ui librarys till i came across this: https://github.com/Eazvy/UILibs/blob/main/Librarys/Coasting/Example
i was scrolling and finding good uis till i saw this one,
particially, when i saw it it looked familiar to an script.
what that script is?
# VAPE V4!!!!!!!
SO, i decided to make an documentaton about it!1!!!!!!!11!

# Documentation goes here.
----------------------------
# Source (Or atleast an example of what the script is.)
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/coast%20old"))()
local test = Library:CreateTab("Title", "Description")

test:CreateButton("Button", function()
end)

test:CreateSection("Section")

test:CreateCheckbox("Checkbox", function()
end)

test:CreateSlider("Slider", 50,0,0,0 , function()
    end)
```
# creating an tab
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/coast%20old"))()
```
# create one tab or more
```lua
local tab = Library:CreateTab("Title", "Description")
```
# then just ui stuff
```lua
tab:CreateButton("Button Text", function() 
    -- Code to execute on button click
end)
```
```lua
tab:CreateSection("Section Name")
```
```lua
test:CreateCheckbox("Enable Feature", function(isChecked)
    if isChecked then
        print("Feature enabled")
    else
        print("Feature disabled")
    end
end)
```
```lua
tab:CreateSlider("Slider Label", defaultValue, minValue, maxValue, stepSize, function(value)
    -- Code to execute when slider value changes
end)
```
