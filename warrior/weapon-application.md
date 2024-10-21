# Weapon application macro
for consumables like sharpening stones, poisons, oils, etc.

***Left click for main hand, right click for off hand***
#showtooltip *item name*
/use *item name*
/use [button:1]16; [button:2]17
/click StaticPopup1Button1


***Keybind with modifier for off hand. Shift used in this example, can be changed to alt, ctrl, etc.***

#showtooltip *item name*
/use *item name*
/use [nomod]16; [mod:shift]17
/click StaticPopup1Button1
