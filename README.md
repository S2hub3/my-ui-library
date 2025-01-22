##القائمه

## النافذه
```lua
local Window = redzlib:MakeWindow({
  Title = "redz Hub : Blox Fruits",
  SubTitle = "by redz9999",
  SaveFolder = "testando | redz lib v5.lua"
})
```
## التاب
```lua
local Tab = Window:MakeTab({"Um", "cherry"})
```

## الاكواد
Dark
```lua
  redzlib:SetTheme("Dark")
```
Darkers
```lua
  redzlib:SetTheme("Darker")
```
Purple
```lua
  redzlib:SetTheme("Purple")
```
## بدا التاب
```lua
Window:SelectTab(Tab2)
```
## القسم
```lua
local Section = Tab2:AddSection({"Section"})
```

## بروغراف
```lua
local Paragraph = Tab2:AddParagraph({"Paragraph", "This is a Paragraph\nSecond Line"})
```
## بلوغل
```lua
  local Dialog = Window:Dialog({
    Title = "Dialog",
    Text = "This is a Dialog",
    Options = {
      {"Confirm", function()
        
      end},
      {"Maybe", function()
        
      end},
      {"Cancel", function()
        
      end}
    }
  })
```
## رز
```lua
Tab1:AddButton({"Print", function()
print("Hello World!")
end})
```
## زر
```lua
local Toggle1 = Tab1:AddToggle({
  Name = "Speed",
  Description = "Idk",
  Default = false
})
```
## سبيدر
```lua
Tab1:AddSlider({
  Name = "Speed",
  Min = 1,
  Max = 100,
  Increase = 1,
  Default = 16,
  Callback = function(Value)
  game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
  end
})
```

## منيو صغير
```lua
local Dropdown = Tab2:AddDropdown({
  Name = "Players List",
  Description = "Select the <font color='rgb(88, 101, 242)'>Number</font>",
  Options = {"one", "two", "three"},
  Default = "two",
  Flag = "dropdown teste",
  Callback = function(Value)
    
  end
})
```
